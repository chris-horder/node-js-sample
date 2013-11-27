# node-js-sample

This is a barebones Node.js app using the [Express](http://expressjs.com/) framework.

## Running Locally

Asumming you have [Node.js](http://nodejs.org/) and [Heroku Toolbelt](https://toolbelt.heroku.com/) installed on your machine:

```sh
git clone git@github.com:heroku/node-js-sample.git # or clone your own fork
cd node-js-sample
npm install
foreman start
```

Your app should now be running on [localhost:5000](http://localhost:5000/).

Also have added recluster (whcih uses cluster) do do hot code deploys