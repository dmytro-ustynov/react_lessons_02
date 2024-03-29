# Continue your journey!

first, you need to init your project with `npm init` or `yarn init` and then install the following packages:

```bash
npm init -y
npm install express lowdb cors
```

Also install dependency for development:

```bash
npm install -D nodemon
```
Edit your package.json file to add the following scripts:

```json
{
  "scripts": {
    "start": "node server.js",
  }
}
```

After all packages were installed, you should follow the step by step guide to create a simple server with a database and a simple API.

Run the server with the following command:

```bash
npm start
```
You should see:

```bash
Server started at 8080 port
```

Now you can open your browser and go to [http://localhost:8080](http://localhost:8080) to see the result.

![img.png](img.png)

This simple server is dedicated to implement API to manage users. You can add, delete, update and get users from the database. 

You should use this server as a backend for your frontend application and implement CRUD operations for users - add button to delete user, add button to edit user's fields, add button to view user details, add button to add new user.
