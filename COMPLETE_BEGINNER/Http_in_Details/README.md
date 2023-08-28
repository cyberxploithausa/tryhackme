# Complete Beginner

## Http in details

> Yazeed Ahmed | 4 March 2023

```````````````````````
ip = 

```````````````````````

## ATTACK Vector


####  TASKS

1.  What does HTTP stand for? | hyper Text Transfer Protocol

2. What does the S in HTTPS stand for? | secure

3. On the mock webpage on the right there is an issue, once you've found it, click on it. What is the challenge flag? | THM{INVALID_HTTP_CERT}

4.  What HTTP protocol is being used in the above example? | HTTP/1.1

5. What response header tells the browser how much data to expect? | Content-Length

6.  What method would be used to create a new user account? | post

7. What method would be used to update your email address? | put

8. What method would be used to remove a picture you've uploaded to your account? | delete

9. What method would be used to view a news article? | get

10. What response code might you receive if you've created a new user or blog post article? | 201

11. What response code might you receive if you've tried to access a page that doesn't exist? | 404

12. What response code might you receive if the web server cannot access its database and the application crashes? | 503

13. What response code might you receive if you try to edit your profile without logging in first? | 401

14.  What header tells the web server what browser is being used? | user-agent

15. What header tells the browser what type of data is being returned? | content-type

16. What header tells the web server which website is being requested? | host

17.  Which header is used to save cookies to your computer? | set-cookie

18. Make a GET request to /room | THM{YOU'RE_IN_THE_ROOM}

20. Make a GET request to /blog and using the gear icon set the id parameter to 1 in the URL field | THM{YOU_FOUND_THE_BLOG}

21. Make a DELETE request to /user/1 | THM{USER_IS_DELETED}

21. Make a PUT request to /user/2 with the username parameter set to admin | THM{USER_HAS_UPDATED}

22.  POST the username of thm and a password of letmein to /login | THM{HTTP_REQUEST_MASTER}