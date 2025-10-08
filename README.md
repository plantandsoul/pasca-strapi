# PASCA CMS 🌸

This is the CMS for [the PASCA website](https://redesign.plantandsoul.org/). The front-end is an Astro app and the repo for that can be found here: https://github.com/plantandsoul/pasca-astro

The CMS is hosted: https://superb-canvas-e9f287e8f1.strapiapp.com/

## 🦾 tech
- [SQLite](https://www.sqlite.org/docs.html)
- [Strapi](https://docs.strapi.io/)

## 🛠️ setup

1. clone repo down locally
3. install deps `npm i`
2. copy the env by running `cp .env.example .env`
4. run strapi in dev mode `npm run develop`. This allows you to make schema changes. These changes, once saved, make changes to json files in `/src/*`. These need to be committed and deployed in order for the schema changes to affect the production database.

## 📜 scripts

### `develop`

Start your Strapi application with autoReload enabled. [Learn more](https://docs.strapi.io/dev-docs/cli#strapi-develop)

```
npm run develop
```

### `start`

Start your Strapi application with autoReload disabled. [Learn more](https://docs.strapi.io/dev-docs/cli#strapi-start)

```
npm run start
```

### `build`

Build your admin panel. [Learn more](https://docs.strapi.io/dev-docs/cli#strapi-build)

```
npm run build
```

## ⚙️ Deployment

We deploy with Strapi Cloud. Previously we've deployed with Railway. Strapi is very flexible and allows for usage of all major databases. Locally, SQLite is used.
