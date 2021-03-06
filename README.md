# RESTFormsUI-react

This project is implementation of RESTForms UI built with React.
It also uses [Antd](https://ant.design/) as main UI library.

In future project will migrate to React 16 and Antd 3+.

**To build this project you need Node 6+ installed. Or you can grab latest stable version from Releases tab.**

You can **build** the project by your own (notice, it might be not stable version in master branch) or you can download production bundle from [Releases](https://github.com/intersystems-ru/RESTFromsUI-react/releases) tab.

## How to build

1. Pull the repository and navigate to the repository folder
2. Open `index.csp` and change server line to address of your rest application.
3. Open a local terminal or command line and execute next commands:
```
npm install
npm run build
```

The production files will be placed in `dist` folder. Copy it to your CSP-application folder and use as general CSP-app.

**For authentication**
Use built `login.csp` page as custom Caché Login Page for your application. Set cookies path to the same value for both rest and client app. 

**README will be updated**
