#Accessing Twitter API with Node and ntwitter

The purpose of this application is to demonstrate two simple examples of how to access Twitter's API from a server written in
Node.js. This application uses ntwitter, which can be found on github [here](https://github.com/AvianFlu/ntwitter). The use cases demonstrated are

1. An application that only makes calls on its own behalf. An example of this would be an analytics application which is using the API on its on behalf. This is referred to as the Single User Example in the Application code.

2. An application which allows users to 'Sign in' with Twitter. An example of this type of application might be a News site which allows its Users to sign-in using their Twitter identies rather than creating their own accounts. This is referred to as the Sign in Twitter Example.

**The Consumer and Ouath Keys in the repository are invalid. They are left in there to make it easier to correlate the screenshots
to the code**

##Setup on Twitter

1. Sign into Twitter

2. Go to https://dev.twitter.com/apps/new to create a new application

3. Create App as seen here

	![Creating a Sample Application](https://dl.dropbox.com/u/15072725/projects/node/Create%20an%20application%20%7C%20Twitter%20Developers-2.jpg)

	This will create the application specific Token and Secret required.

4. Create User Tokens. 

	In addtion to creating Application specific Token and Secret, we also need to generate **user** specific tokens.

	To do this select 'Create my access token' at the bottom of the application overview page.

	![Create Access Token](https://dl.dropbox.com/u/15072725/projects/node/The%20craziest%20App%20Ever%20%7C%20Twitter%20Developers.jpg)

5. Verify you have both a Consumer Secret and an Oauth Token created. 

	Go to the Oauth Tab on the Application Overview page to verify you have all 4 keys/tokens.

	See the screenshot below

	![Verifying Application Setup](https://dl.dropbox.com/u/15072725/projects/node/My%20Sample%20App%20Must%20Be%20Unique%20%7C%20Twitter%20Developers.jpg)


##Setup Local

The two main packages here are express and ntwitter

1. Install Express

	```
	$ npm install express
	```

2. Install ntwitter

	```
	$ npm install ntwitter
	```

3. Run the Server

	```
	$ node app.js
	```

4. Update app.js with correct tokens/keys

	```
	Search for TODO in app.js to find all necessary code that needs to be updated
	```

5. Connect to Server via Browser


	Go to [http://localhost:3000](http://localhost:3000)

