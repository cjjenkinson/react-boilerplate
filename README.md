# React Boilerplate 2018

A lightweight starter boilerplate I use to bootstrap React applications using the container and presentational component design pattern.

Uses Babel, Webpack and configured with [Airbnb](https://github.com/airbnb/javascript/tree/master/react) eslint out of the box.

File structure:

```md
- dist
  -- index.html
- src
  -- components
  -- containers
     -- App.css
     -- App.js
     -- App.test.js
  -- images
  -- utils
  -- api.js
  -- index.js
- .eslintrc
- package.json
- webpack.config.js
```
## File Structure

Learn more about [Presentational & Container Components](|https://medium.com/@dan_abramov/smart-and-dumb-components-7ca2f9a7c7d0)

- Components: presentational components, recieve data via props and are concerned with presentation only
- Containers: container components, provide data and behaviour and are concerned with how things work 
- Images: public image assets
- Utils: helpers, formatters and a place to store useful tools
- api.js: relevant API calls, at some point you may wish to break this into seperate API files e.g products.js, users.js
- index.js: renders your application from the parent component e.g App

## ESLint & Style Guide (Airbnb)

*The jsx file name extensions rule has been turned off to avoid errors that prevent rendering HTML within React components.

```json
{
  "env": {
      "browser": true,
      "node": true
  },
  "extends": "airbnb",
  "parser": "babel-eslint",
  "rules": {
    "react/jsx-filename-extension": [1, { "extensions": [".js", ".jsx"] }]
  }
}
```

