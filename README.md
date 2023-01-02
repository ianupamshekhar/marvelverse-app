# Marvelverse

## Setup

Create `.env.development.local` in your root directory and place this env config.

```
REACT_APP_PUBLIC_KEY=YourMarvelPublicKey
REACT_APP_HASH_KEY=YourHashFromPrivateKeyAndTimeStamp
```

Create another `.env.production.local` if you want to deploy it in your host. In Vercel host just add in your project setting > Environment Variables > Production and insert the same value as your `.env.development.local`, please remember that the `.env.*` files are exluded in `gitignore`, so you have to add manually the `.env` file in your root project.

Run `yarn install` or `npm install` wait until it finished and `yarn start` or `npm start` to start the development.

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).
