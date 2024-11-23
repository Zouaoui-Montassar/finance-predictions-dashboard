
## Installation

Install with npm

- Setup the backend
```bash
  cd server
  npm install
```
- Setup the frontend 
```bash
  cd client
  npm install
```
## Environment Variables / server

To run this project, you will need to add the following environment variables to your .env file ( which you are going to create in the server folder, server/.env )
```bash
  PORT = 1337
  MONGO_URI = your_mongo_uri
```

## Environment Variables / client

To run this project, you will need to add the following environment variables to your .env.local file ( which you are going to create in the client folder, client/.env.local )
make sure that this environment variable starts with 'VITE_BASE_'.
```bash
  VITE_BASE_URL=http://localhost:1337
```

## Run Locally

Start the server

```bash
  npm run dev
```
Start the client

```bash
  npm run dev
```

## License

[Apache License 2.0](https://choosealicense.com/licenses/apache-2.0/)

