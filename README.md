URL shortner coded following this tutorial:
https:/go.microsoft.com/fwlink/?LinkID=135170

Used FastApi to set up a REST API.

Gained knowledge of Uvicorn and its functions for setting up development servers.

Tutorial consisted of setting up main functions of a UrlShortener API. You are able to assign a link a random key which can be used to redirect to the original link. You are able to deactivate links and view specific information through the use of an admin key.

To deactivate links you can post a DELETE request on localhost:8000/docs with the desired secret key.


My features:

Currently have a post request added to allow a user to see the database in JSON format on thier browser.

    Possible future functions:
        Custom URL key: Let your users create custom URL keys instead of a random string.
        Peek URL: Create an endpoint for your users to check which target URL is behind a shortened URL.
        Graceful Forward: Check if the website exists before forwarding.