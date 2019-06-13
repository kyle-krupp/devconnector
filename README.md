# # DevConnector

> Small social network app built with the MERN stack.

Live app: [DevConnector: A social network for developers](http://developerconnectorapp.herokuapp.com/)

## Instructions for cloning

```bash
# Install dependencies for server
npm install

# Install dependencies for client
npm run client-install

# Run the client & server with concurrently
npm run dev

# Run the Express server only
npm run server

# Run the React client only
npm run client

# Server runs on http://localhost:5000 and client on http://localhost:3000
```

You will need to create a keys_dev.js in the server config folder with

```
module.exports = {
  mongoURI: 'YOUR_OWN_MONGO_URI',
  secretOrKey: 'YOUR_OWN_SECRET'
};
```

## App Info

- Create User accounts and profiles
- Add experience & education
- Adds social network and GitHub links
- Create & delete posts, comments, and likes
- View posts, comments, & likes from other users

## Technologies Used

- Environment: Node.js
- Client: React
- Server routing: Express
- Authentication: Passport.js w/ JSON Web tokens (JwT)
- Database: Mongo DB documents hosted on small cloud AWS environment. (Via [MongoDB Hosting: Database-as-a-Service by mLab](https://mlab.com/))

### Author

Kyle Krupp
[https://github.com/kyle-krupp](https://github.com/kyle-krupp)

### Version

1.0.0

### License

This project is licensed under the MIT License
