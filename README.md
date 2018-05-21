# Basic boilerplate for a webapp in typescript

## back-end

Uses:

* Express
* Apollo Server Express
* Graphiql tool

Commands | Description
---------|----------------
`yarn` | install dependencies
`yarn dev` | starts the development server with hot reloading
`yarn build` | compiles the typescript into the `dist` folder
`yarn build:watch` | compiles with automatically recompiling on changes
`yarn start` | runs the compiled backend from the `dist` folder

## front-end

Uses:

* Parcel
* React
* Radium

Commands|Description
--------|-----------
`yarn` | install dependencies
`yarn dev` | builds the font end with hot reloading and starts a dev server
`yarn build` | bundles the front end into the `dist` folder
`yarn build:watch` | bundles the front end into the `dist` folder, automatically rebuilding on changes