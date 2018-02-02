# React Boilerplate 2018

A lightweight starter boilerplate I use to bootstrap React applications using the container and presentational component design pattern.

Uses Babel, Webpack and configured with Airbnb eslint out of the box.

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

ESLint & Style Guide (Airbnb)

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

