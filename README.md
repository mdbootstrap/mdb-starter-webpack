![MDB Logo](https://mdbootstrap.com/img/Marketing/general/logo/medium/mdb-r.png)

# MDB 5 Webpack Starter

### Webpack boilerplate for Bootstrap 5 & Material Design 2.0 UI Kit

**[>> Support MDB 5 with a STAR](https://github.com/mdbootstrap/mdb-ui-kit/)**

**[>> MDB 5 Demo](https://mdbootstrap.com/docs/standard/#demo)**

<a href="https://npmcharts.com/compare/mdbootstrap?minimal=true"> <img src="https://img.shields.io/npm/dm/mdbootstrap.svg?label=MDB%20Downloads" alt="Downloads"></a>
<a href="https://github.com/mdbootstrap/bootstrap-material-design/blob/master/License.pdf"><img src="https://img.shields.io/badge/license-MIT-green.svg" alt="License"></a>
<a href="https://twitter.com/intent/tweet/?text=Thanks+@mdbootstrap+for+creating+amazing+and+free+Material+Design+for+Bootstrap+4+UI+KIT%20https://mdbootstrap.com/docs/jquery/&hashtags=javascript,code,webdesign,bootstrap"><img src="https://img.shields.io/twitter/url/http/shields.io.svg?style=social&label=Let%20us%20know%20you%20were%20here%21&"></a>
<a href="https://www.youtube.com/watch?v=c9B4TPnak1A&t=6s"><img alt="YouTube Video Views" src="https://img.shields.io/youtube/views/c9B4TPnak1A?label=Bootstrap%205%20Tutorial%20Views&style=social"></a>

___

> :warning: The use of this Starter is at your own risk and assumes basic knowledge of Webpack, JavaScript and CSS preprocessors. We recommend creating custom versions of MDB UI KIT and themes only for advanced developers.

___

### Installation
```
npm install
```
A free version of **MDB UI Kit** is already included as a dependency, to upgrade it to PRO version install the package you own with the command below.

> **Pro Essential installation**
> ```
> npm install git+https://oauth2:ACCESS_TOKEN@git.mdbootstrap.com/mdb/standard/mdb-ui-kit-pro-essential
> ```

> **Pro Advanced installation**
> ```
> npm install git+https://oauth2:ACCESS_TOKEN@git.mdbootstrap.com/mdb/standard/mdb-ui-kit-pro-advanced
> ```

### Dev Server
```
npm run start
```

### Build
```
npm run build
```

### Features:

* Bundling via [Webpack](https://github.com/webpack/webpack) 5.74.0
* ES6+ Support via [babel-cli](https://github.com/babel/babel) v7.18.10
* SASS Support via [sass-loader](https://github.com/webpack-contrib/sass-loader) v13.0.2
* Linting via [eslint-webpack-plugin](https://github.com/webpack-contrib/eslint-webpack-plugin) v3.2.0
* Unit Testing via [jest](https://github.com/facebook/jest) v29.0.1
* Code Formatting via [prettier](https://github.com/prettier/prettier) v2.7.1

### Files structure:

```
my-project/
├── dist/
│   └── index.html
├── src/
│   ├── js/
│   └── scss/
└── webpack.config.js
```
<br><br>

___

# MDB UI KIT - Importing of MDB files

### Importing JS modules
You can import the entire library or just individual modules:
```
import * as mdb from 'mdb-ui-kit'; // lib
import { Input } from 'mdb-ui-kit'; // module
import { Input as CustomInput } from 'mdb-ui-kit'; // module with custom name
```

### Importing CSS file
To import MDB stylesheet please use the following syntax:
```
@import '~mdb-ui-kit/css/mdb.min.css';
```
