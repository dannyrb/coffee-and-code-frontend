# coffee-and-code-frontend

### Blank Project Setup Steps

A record of the steps followed to add the apps dependencies and init scaffolded code from scratch.

- `npm install --save yarn`
- `yarn add framework7`
- `yarn global add vue-cli@latest` and/or `npm install --save -g vue-cli`
- `vue init webpack src`
- `cd src`
- `npm install`
- `npm run dev`
- Create new blank XDK HTML + Cordova project at `/app`


- [yarn](https://www.npmjs.com/package/yarn)
- [Framework7](http://framework7.io/docs/)
- [vue-cli](https://github.com/vuejs-templates/webpack)


### To Do:

- Gulp to pull files from node_modules into `/src/static`
- Remove packages.json at top app level
- Get basic routing and magic working with the Framework7 + vue setup
- Configure environment for testing on app
- Setup build credentials for android app stuff through XDK