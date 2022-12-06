# Flag 3
This obstacle will be dealing with something called forced browsing and will implement techniques such as directory/url brute force discover. 

1. Open up any post.
2. In Burp on the proxy and intercept tabs, toggle the intercept button.
3. Refresh the page. 
4. Right click on the request in Burp and select seld to Intruder. 
5. Select the Intruder tab in Burp. 
6. On the right hand side select 'Clear'.
![Clear]()
7. Highlight the ID number in the request header and then select the 'Add' button on the right hand side. 
8. We can leave the attack type as 'Sniper' and then hit the 'Payloads' tab. 
9. On the payloads screen change the payload type to 'Numbers'. Then enter a starting value, ending value, and increment value for the attack. (I chose 940 to 1000 because I've done this before. You would likely want to want to use a higher range.)
10. Click 'Start Attack'
11. 
