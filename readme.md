## Before You Begin
Before you begin we recommend you read about the basic building blocks that assemble a 10ttech esim backend restful application:
* MongoDB - Go through [MongoDB Official Website](http://mongodb.org/) and proceed to their [Official Manual](http://docs.mongodb.org/manual/), which should help you understand NoSQL and MongoDB better.
* Express - The best way to understand express is through its [Official Website](http://expressjs.com/), which has a [Getting Started](http://expressjs.com/starter/installing.html) guide, as well as an [ExpressJS](http://expressjs.com/en/guide/routing.html) guide for general express topics. You can also go through this [StackOverflow Thread](http://stackoverflow.com/questions/8144214/learning-express-for-node-js) for more resources.
* Node.js - Start by going through [Node.js Official Website](http://nodejs.org/) and this [StackOverflow Thread](http://stackoverflow.com/questions/2353818/how-do-i-get-started-with-node-js), which should get you going with the Node.js platform in no time.


## Prerequisites
Make sure you have installed all of the following prerequisites on your development machine:
* Git - [Download & Install Git](https://git-scm.com/downloads). OSX and Linux machines typically have this already installed.
* Node.js - [Download & Install Node.js](https://nodejs.org/en/download/) and the npm package manager. If you encounter any problems, you can also use this [GitHub Gist](https://gist.github.com/isaacs/579814) to install Node.js.
* MongoDB - [Download & Install MongoDB](http://www.mongodb.org/downloads), and make sure it's running on the default port (27017).

## Downloading project-10ttech-esim-android-app

### Cloning The GitHub Repository
The recommended way to get 10ttech esim backend restful is to use git to directly clone the project-10ttech-esim-android-app backend restful repository:

```bash
$ git clone https://github.com/Penpenny/project-10ttech-esim-android-app.git
```

This will clone the latest version of the project-10ttech-esim-android-app repository to a **project-10ttech-esim-android-app** folder.


## Quick Install
Once you've downloaded the project and installed all the prerequisites, you're just a few steps away from starting to develop your project-10ttech-esim-android-app application.

The project comes pre-bundled with a `package.json` files that contain the list of modules you need to start your application.

To install the dependencies, run this in the application folder from the command-line:

![temp 1](https://user-images.githubusercontent.com/101380637/183403837-5f29113d-e158-45e8-8ea8-2652a75a41b5.jpg)


```bash
$ npm install
```

This command does a few things:
* First it will install the dependencies needed for the application to run.
* If you're running in a development environment, it will then also install development dependencies needed for testing and running your application.
* To update these packages later on, just run `npm update`

## Running Your Application

Run your application using npm:

```bash
$ npm start
```

Your application should run on port 3011 with the *development* environment configuration, so in your browser just go to [http://localhost:3011](http://localhost:3011)

That's it! Your application should be running. To proceed with your development, check the other sections in this documentation.
If you encounter any problems, try the Troubleshooting section.

Explore `.env` for development environment configuration options.

## Testing Your Application
You can run the full test suite included with project-10ttech-esim-android-app restful with the test task:

```bash
$ npm test
```
This will run the server-side tests (located in the `app/tests/` directory)

To execute only the server tests and run again only changed tests, run the test:server:watch task:


### Amazon S3 configuration

To save the profile images to S3, simply set those environment variables:
UPLOADS_STORAGE: s3
S3_BUCKET: the name of the bucket where the images will be saved
S3_ACCESS_KEY_ID: Your S3 access key
S3_SECRET_ACCESS_KEY: Your S3 access key password


### Stripe Information

To save your stripe key , simply set those environment variables:
STRIPE_SECRETKEY: Your stripe access secretkey


### Simple Mail Transfer Protocol (SMTP)
[Simple Mail Transfer Protocol-JavaPoint](https://www.javatpoint.com/simple-mail-transfer-protocol),

This protocol is used by most e-mail clients to deliver messages to the server, and is also used by servers to forward messages to their final destination.
To save your SMTP env, simply set those environment variables:
SMTP_HOST: Your SMTP host
SMTP_USER: Your SMTP user mail
SMTP_PASS: Your SMTP password
SMTP_PORT: Your SMTP port


### SSL Certificate
SSL is used to secure the site.
SSL certificates are what enable websites to move from HTTP to HTTPS, which is more secure. 
An SSL certificate is a data file hosted in a website's origin server.
SSL certificates make SSL/TLS encryption possible, and they contain the website's public key and the website's identity, along with related information
