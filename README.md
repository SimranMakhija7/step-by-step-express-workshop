# Step by Step Express

The intent of this project is to take you step-by-step through the process of building an Express app, documenting the changes as bite-sized chunks that you'll ideally be able to pick up and iterate upon rapidly.

## Requirements

- All steps:
  - [Node.js](https://nodejs.org/en/)
  - [Azure account](https://aka.ms/step-by-step-express-azure) (free tier works just fine 💖)

## Step Zero

- Initalize the repo with the universal documents that we should have in every project

Read more in the Step Zero [README.md](./step-zero/README.md)

## Step One

- Set up a very basic HTTP server + add the dependencies

To run the Step One code:

```bash
# make sure your current working directory is the main directory of this repo
cd step-one
node app.js
```

Read more in the Step One [README.md](./step-one/README.md)

## Step Two

- Set up a very basic HTTP server + add the dependencies

To run the Step Two code:

```bash
# make sure your current working directory is the main directory of this repo
cd step-two
node app.js
```

Read more in the Step Two [README.md](./step-two/README.md)

## Step Three

- Start parsing the querystring passed to the web app and – if the querystring `id` is present – passing that value to the API we're hitting, via the `request` module.

To run the Step Three code:

```bash
# make sure your current working directory is the main directory of this repo
cd step-three
node app.js
```

Read more in the Step Three [README.md](./step-three/README.md)

## Step Four

- Add view rendering with `handlebars` (via `express-handlebars`)
- Create our first view
- Start rendering comics with handlebars on the `/comic` path

To run the Step Four code:

```bash
# make sure your current working directory is the main directory of this repo
cd step-four
node app.js
```

Read more in the Step Four [README.md](./step-four/README.md)

## Step Five

- Call Express's `static` method to serve CSS
- Create the `/static` directory + add our CSS file to it

To run the Step Five code:

```bash
# make sure your current working directory is the main directory of this repo
cd step-five
node app.js
```

Read more in the Step Five [README.md](./step-five/README.md)

## Step Six

- Add Added error handling
- Add port detection (`process.env.PORT`) that allows us to ship it to Auzre
- Add `favicon.ico` to make browsers happy

To run the Step Six code:

```bash
# make sure your current working directory is the main directory of this repo
cd step-six
node app.js
```

Read more in the Step Six [README.md](./step-six/README.md)

## Step Seven

- Deploy to [Azure App Service](https://docs.microsoft.com/en-us/azure/app-service/quickstart-nodejs?pivots=platform-linux)
