React Environment using webpack and babel
https://scotch.io/tutorials/setup-a-react-environment-using-webpack-and-babel

cordova create <path> --template <react_project_path>


- to generate dist source<br>
npm run dist

- to run web server (hot deploy)<br>
npm start

- to run dev mode (hot deploy into distribution directory)<br>
npm run dev

to start<br>
- npm dist
- cordova platform add android

https://github.com/nordnet/cordova-hot-code-push
apply mobile hot deploy plugin<br>
- cordova plugin add cordova-hot-code-push-plugin
- cordova plugin add cordova-hot-code-push-local-dev-addon
- npm install -g cordova-hot-code-push-cli

start local mobile server<br>
- cordova-hcp server

