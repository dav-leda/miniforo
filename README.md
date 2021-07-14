# MERN Message Board with React FrontEnd and Apollo Server BackEnd

## Installation

Install the dependencies for the FrontEnd and BackEnd separately:

```sh
cd frontend
npm i
cd backend
npm i
```

Include an .env file in the BackEnd with your MongoDB Atlas credentials and a JWT Secret Key:

```sh
MONGODB_URI=mongodb+srv://username:password@lib-cluster.sdf3n.mongodb.net/mern-graphql?retryWrites=true&w=majority
SECRET_KEY=xxxxxxxxxxxxxxxxxxxxxx
```

First run the BackEnd (it runs on port 5000):

```sh
cd backend
npm run serve
```

Then run the FrontEnd (it runs on port 3000):

```sh
cd frontend
npm start
```

That's it!
