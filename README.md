# Desktop Client

## Install Dependencies

- Fork and clone the ripple-client-desktop repository 
- 安装nvm
- 切换node到0.10.26版本   nvm install 0.10.26   nvm use 0.10.26
- Run `npm install`

- Download [nw.js](https://github.com/nwjs/npm-installer)
  安装nw.js要使用node 4.8.7版本  使用nvm use 4.8.7切换
  npm install nw@0.13.0
  

## Build

- In the ripple-client-desktop repository, make a copy of the `config_example.js` file and name it `config.js`
- Run `gulp` in your command line for development

- Run `gulp packages` in your command line for the production ready client
- Your desktop client is in the `packages/RippleAdminConsole` directory

### Note
- There are breaking changes in the c++ API when using node version 4. You should use node version 0.12.
- The current package.json is intended to pull directly from the develop branch of ripple-lib. You may need to clone the ripple-lib respository into node_modules/ripple-lib and then run npm install in the cloned ripple-lib repository.
