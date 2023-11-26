![Wiggle Waggy Walks](https://github.com/ebarinia/CapstoneClient/assets/46579070/40e88575-a88e-4dae-a147-c1d292b95c1e)[YouTube Demo](https://youtu.be/ehOk06gWH44)

# Wiggle Waggy Walks

Welcome to our capstone project for CodeClan software development course: Wiggle Waggy Walks!

🚨 This Full stack web-application was built with React on the front-end. In order for this application to work, it is imperative that you run the the React client on a local machine. You can find the repo here: https://github.com/ebarinia/CapstoneClient.

### What is Wiggle Waggy Walks?

The concept behind the Wiggle Waggy Walks app is to create a platform that connects dog owners for a safe walk within Glasgow. Making it convenient for pet owners to ensure their dogs get to socialise with other dogs, getting the exercise they need. Our goal is to create a reliable and user-friendly platform that bridges the gap between dog owners in Glasgow, whilst ensuring the well-being and happiness of dog and owners.

On WWW, a user is able to create an account (or log in if already registered) and interact with other members - by sending an invitation for a walk, participate to a group walk event and even create one if they can't find a suitable one. They can even use the instant-messaging function within the application in order to chat in with other members in real time!


### The Technical Stuff

Full-Stack web application with a client-server architecture consisting on a REST API that handles client requests and connects to a PostgreSQL database to store data.

For the front-end, we have built our application with React and SassyCSS. Additionally, we are also using Firebase real-time database and storage in order to store our images and new account details.

One of the standout features we've implemented is the live-chat functionality, seamlessly integrated using Snapshots within Firebase. This facilitates real-time communication, enabling our users to engage effortlessly.

This tech stack fusion enables us to deliver a seamless, secure, and feature-rich application, ensuring optimal performance and user satisfaction at every turn.


## How to get started?

### 1. Clone the repository on your local machine

```
git clone git@github.com:ebarinia/CapstoneServer.git
```

Do this for both for the Client and the server. Run the client with the IDE of your choice.

### 2. Create the Database

Check wether PostgreSQL/PSYCOPG2 are installed on the machine
```
psql
```

If not installed, find the installation guide [here](https://www.psycopg.org/docs/install.html)

Then on your terminal, create the database

```
createdb dogapp
```

### 3. Open the server folder with the IDE of your choice

Ensure that you have the correct build installed in your IDE. This project was built with Java version 18. If not, the IDE should prompt you to install the dependencies.

### 3. Starting the server

Once this is done, simply run the application by right clicking on "Capstone Application" and then "Run Capstone Application Main". This will run the REST API on local machine, and you can find explore the API on localhost:8080/api/users (users can be changed with dogs/groupwalkies/notifications...).
