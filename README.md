# Online Chat

App developed with MERN-stack and Socket.io.

## Installation

### Clone

- Clone this repo to your local machine using `https://github.com/nikmihalevich/mern-online-chat`

### Setup

1. In first, make `dev.js` file inside server/config folder.
2. Put mongoDB info into `dev.js`.

#### For Example

```javascript
module.exports = {
  mongoURI:
    "mongodb+srv://<user>:<password>@cluster0.zpldj.azure.mongodb.net/<dbname>?retryWrites=true&w=majority",
};
```

Where you should change fields `<user>`, `<password>` and `<dbname>` on yours from MongoDB Atlas.

> Use the package manager [npm](https://www.npmjs.com/get-npm) to install.

3. Type it in root directory for download sever dependencies.

```shell
$ npm install
```

And it for client

```shell
$ npm run frontend:install
```

### Run

> run npm script `start` for launch dev server

```shell
$ npm run start
```

> run npm script `backend` for start [nodemon utility](https://nodemon.io/) on server

```shell
$ npm run backend
```

> run npm script `frontend` for render client

```shell
$ npm run frontend
```

> run npm script `dev` for execute `backend` and `frontend` scripts both.

```shell
$ npm run dev
```

---

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
