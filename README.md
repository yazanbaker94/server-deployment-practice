PULL REQUEST: https://github.com/yazanbaker94/server-deployment-practice/pull/2
ACTIVE HEROKU: https://yazan-server-deploy-prod.herokuapp.com/




How do I install the app or library?

Basically you need to clone the repo, and then install:

    npm i dotconfig express jest
    
And then run 'npm test', without the quotes, the all the test to verify the server will be tested and passed.

How do I test the app or library?
You can test it by running 'npm test', and if you needed, you can add your own testing conditions in the handlers folder.


For Applications:
How do I run the app?
You can run the app by running the server on your localhost, and then going to the main page. Also you can use ThunderClient to test the GEt, POST etc.

How do I set up the app?
1.  Install your dependencies – npm i dotconfig express jest
2.  Create the files and folders required for the application
3.  Create the correct content in the files
4.  Test your server – npm test
    You should see 100% of tests passing
5.  Start your server – nodemon
6.  Visit http://localhost:3000/data in your browser to confirm that the server is visible
