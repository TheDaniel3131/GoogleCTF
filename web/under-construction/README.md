This web challenge is worth 50 pts. 

After some researching and attempts, I realized that the user account must be in GOLD tier to get the flag. But getting the tier to gold is
not easy as I have no idea how until I came across to this article from OWASP.

https://owasp.org/www-project-web-security-testing-guide/latest/4-Web_Application_Security_Testing/07-Input_Validation_Testing/04-Testing_for_HTTP_Parameter_Pollution

From my understanding, HTTP Parameter Pollution (HPP) is like sneaking extra instructions into a website's form. 
It's as if you're filling out a survey, and someone adds extra questions without you knowing. 
This can make the website act weird, possibly giving access to things it shouldn't or messing up how it works. 
HPP is a way attackers try to confuse websites and do things they're not supposed to.


So I can add another tier called ?tier=blue&tier=gold to bypass the HTTP parameter and trying out the flask challenge website (didn't manage to login) but in php I am be able
to get the flag.  






