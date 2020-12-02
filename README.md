# sampleVueAmplify

```sh
$ nvm install v12.19.1
$ nvm alias default v12.19.1
$ npm update -g npm
$ npm i -g npm
$ npm --version
$ npm install -g @aws-amplify/cli
$ npm install -g @vue/cli
```

```sh
$ vue create sample-vue-amplify
Vue CLI v4.5.9
? Please pick a preset: Manually select features
? Check the features needed for your project: Choose Vue version, Babel, TS, Router, Vuex
? Choose a version of Vue.js that you want to start the project with 2.x
? Use class-style component syntax? Yes
? Use Babel alongside TypeScript (required for modern mode, auto-detected polyfills, transpiling JSX)? Yes
? Use history mode for router? (Requires proper server setup for index fallback in production) Yes
? Where do you prefer placing config for Babel, ESLint, etc.? In package.json
? Save this as a preset for future projects? No
$ cd sample-vue-amplify/
$ npm run serve
```

```sh
$ npm i --save aws-amplify @aws-amplify/ui-vue
$ amplify init
? Enter a name for the project sample
? Enter a name for the environment dev
? Choose your default editor: None
? Choose the type of app that you're building javascript
Please tell us about your project
? What javascript framework are you using vue
? Source Directory Path:  src
? Distribution Directory Path: dist
? Build Command:  npm run-script build
? Start Command: npm run-script serve
Using default provider  awscloudformation
? Do you want to use an AWS profile? Yes
? Please choose the profile you want to use default
```

```sh
$ amplify add auth
 Do you want to use the default authentication and security configuration? Default configuration
 How do you want users to be able to sign in? Username
 Do you want to configure advanced settings? No, I am done.
$ amplify push
? Are you sure you want to continue? Yes
```

```sh
$ amplify delete
? Are you sure you want to continue? This CANNOT be undone. (This would delete all the environments of the project from the cloud and wipe out all the local files created by Amplify CLI) Yes
⠋ Deleting resources from the cloud. This may take a few minutes...
Deleting env:dev
✔ Project deleted in the cloud
Project deleted locally.
```

#### Link

- [Amplify公式: setup](https://docs.amplify.aws/start/getting-started/setup/q/integration/vue)
- [Amplify公式: auth](https://docs.amplify.aws/start/getting-started/auth/q/integration/vue)
