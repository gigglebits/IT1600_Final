# Flag 1

Flag 1 focuses on direct object refrencing which can be encompassed into the top vulnerability on the [OWASP Top 10](https://owasp.org/www-project-top-ten/), BAC or broken access control (not blood alcohol content).

1. First things first. From the authenticated state we will click edit on one of our own posts (you'll probably only have one). 
![post]()
2. If we look up at the URL we can see that there is an id parameter being sent with the get request. In this case the parameter value is set to '3'. 
3. Change that parameter value to see if you can access any other posts. 
4. We find that we can get to other peoples posts and even edit them by just directly referencing them. In someone else's post change something about it and hit save. This will bring you Flag 1.
![Flag1]()

---
[Home](./Start.MD) 
[Back](./Flag0) [Next](./Flag2)
