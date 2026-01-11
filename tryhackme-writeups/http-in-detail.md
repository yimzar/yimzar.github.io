Morgan Albright

TryHackMe Room: HTTP in Detail

Difficulty Level: Walkthrough

What I learned: How http works and the different types of errors and requests you can make to a web server.

Task 1: What is HTTP(S)?

1\. What does HTTP stand for?

In the first sentence it says in brackets what it stands for ______ _____ _____.

2\. What does the S in HTTPS stand for?

Given that it encrypts http. It makes it ______.

3\. On the mock webpage on the right there is an issue, once you've found it, click on it. What is the challenge flag?

I clicked the text at the top of the screen and it gave me the flag. THM{____________}

Task 2: Requests And Responses

1\. What HTTP protocol is being used in the above example?

In the first line of code I see. It says HTTP/_._. That's how I came to my conclusion.

2\.  What response header tells the browser how much data to expect?

In the list of headers the 4th option ____________ says 98 which is how much to expect.

Task 3: HTTP Methods

1\. What method would be used to create a new user account?

In the 4 different types, I went with the 2nd one the ____ request because it is for submitting data and creating new records.

2\. What method would be used to update your email address?

This one was the ___ request because it's for updating information that already exists.

3\. What method would be used to remove a picture you've uploaded to your account?

This one would be the ______ request, because it's removing information and not updating nor creating new records.

4\. What method would be used to view a news article?

This one would be the ___ request, because there is no modification or creation, or deletion of information. Just getting information from the web server.

Task 4: HTTP Status Codes

1\. What response code might you receive if you've created a new user or blog post article?

After looking at the list of common HTTP codes, the one that most fit was ___, because it's when something has been created whether it's a blog post or not.

2\. What response code might you receive if you've tried to access a page that doesn't exist?

This one would clearly give you a "page not found error" and we all know that one is ___. See I knew from my intuition but I took a peak at the list just to verify.

3\. What response code might you receive if the web server cannot access its database and the application crashes?

This one would be in the 500 range because it's a web server client side issue, the one that most fit's this is "This server cannot handle your request as it's either overloaded or down for maintenance." otherwise known as ___.

4\. What response code might you receive if you try to edit your profile without logging in first?

This one is in the 400 range because it's an error from not being logged in. The answer was ___, because it says "You are not currently allowed to view this resource until you have authorised with the web application, most commonly with a username and password."

Task 5: Headers

1\. What header tells the web server what browser is being used?

This header is the __________. Because it's ".. telling the web server your browser software".

2\. What header tells the browser what type of data is being returned?

The answer for this one is ___________. In the list of common response headers it states "This tells the client what type of data is being returned.."

3\. What header tells the web server which website is being requested?

This one is ____. In the list of common request headers ____ says "Some web servers host multiple websites so by providing the host headers.."

Task 6: Cookies

1\. Which header is used to save cookies to your computer?

The header is _________ because that one is used to remember your computer and http is stateless.

Task 7: Making Requests

1\. Make a GET request to /room page

The flag I received after changing the request command to GET and the /room page was THM{______________}

2\. Make a GET request to /blog page and set the id parameter to 1

After changing the parameters to ID and 1 along with the /blog page I got THM{_____________}

3\. Make a DELETE request to /user/1 page

After changing the request to delete and changing to /user/1 I received THM{_____________}

4\. Make a PUT request to /user/2 page with the username parameter set to admin

After making a put request to /user/2 and changing the parameters accordingly, I got THM{______________}

5\. Make a POST request to /login page with the username of thm and a password of letmein

After making a POST request to /login and changing the parameters accordingly I got THM{______________}
