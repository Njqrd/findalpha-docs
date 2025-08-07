# Heroku Deployment Guide

This Docusaurus project is configured for deployment on Heroku.

## Prerequisites

1. Install the [Heroku CLI](https://devcenter.heroku.com/articles/heroku-cli)
2. Have a Heroku account
3. Have Git installed

## Deployment Steps

### 1. Login to Heroku
```bash
heroku login
```

### 2. Create a new Heroku app
```bash
heroku create your-app-name
```

### 3. Set the Node.js buildpack (if not already set)
```bash
heroku buildpacks:set heroku/nodejs
```

### 4. Deploy to Heroku
```bash
git add .
git commit -m "Prepare for Heroku deployment"
git push heroku main
```

### 5. Open your app
```bash
heroku open
```

## How it works

- The `Procfile` tells Heroku to run `npm start`
- The `start` script in `package.json` builds the Docusaurus project and starts the Express server
- The Express server (`server.js`) serves the static files from the `build` directory
- The server handles client-side routing by serving `index.html` for all routes

## Environment Variables

You can set environment variables in Heroku:
```bash
heroku config:set NODE_ENV=production
```

## Troubleshooting

- Check logs: `heroku logs --tail`
- Restart the app: `heroku restart`
- Check build status: `heroku builds`

## Local Development

For local development, use:
```bash
npm run dev
```

This will start the Docusaurus development server instead of the production build. 