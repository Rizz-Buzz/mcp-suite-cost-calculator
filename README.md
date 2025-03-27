# MCP Suite Cost Calculator

A simple web-based calculator for estimating MCP Suite costs based on different
parameters.

## Features

- Calculate MCP Suite costs based on number of users and other parameters
- Responsive design that works on desktop and mobile
- No server-side processing required - runs entirely in the browser

## Deployment

This calculator is built as a standalone HTML file using React and can be
deployed in multiple ways:

### GitHub Pages

1. Fork or clone this repository
2. Go to repository Settings → Pages
3. Under "Source", select the branch containing the calculator (usually "main")
4. Click Save
5. Your calculator will be available at
   `https://[username].github.io/[repository-name]/`

### Heroku Deployment

1. Create a Heroku account if you don't have one
2. Install the [Heroku CLI](https://devcenter.heroku.com/articles/heroku-cli)
3. Login to Heroku: `heroku login`
4. Create a new Heroku app: `heroku create your-app-name`
5. Deploy to Heroku: `git push heroku main`
6. Your app will be available at `https://your-app-name.herokuapp.com`

For connecting to a private GitHub repository:

1. Go to the Heroku Dashboard
2. Select your app
3. Go to the "Deploy" tab
4. Connect to GitHub and select your private repository
5. Enable automatic deploys or manually deploy

### Other Deployment Options

- Upload to any static web hosting service (Netlify, Vercel, etc.)
- Host on any web server (Apache, Nginx, etc.)
- Integrate into an existing website by copying the HTML file

## Local Development

To run locally:

- For simple viewing: Open the HTML file in your browser
- To test the Heroku setup:
  1. Install dependencies: `npm install`
  2. Start the server: `npm start`
  3. Visit `http://localhost:3000` in your browser

## License

[MIT License](LICENSE)
