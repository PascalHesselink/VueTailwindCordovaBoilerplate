# VueTailwind Cordova Boilerplate

Boilerplate for Tailwind, Vue, Sass, and Cordova to quickly create applications

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Installing

[Download](https://github.com/PascalHesselink/VueTailwindCordovaBoilerplate/archive/master.zip) the project and open it in your terminal and code editor!


Make sure you have Cordova installed:
```
npm install -g cordova
```
Install the packages via [npm](https://www.npmjs.com/):
```
npm install 
```

Add platforms to Cordova (execute inside the src-cordova folder):
```
cd src-cordova
```
```
cordova platform add android
cordova platform add ios
cordova platform add browser
```


## Start coding


While developing run (in root of project):
```
npm run cordova-serve-browser
```


## Deployment

Before deploying your project run the following command to use PurgeCSS:
```
npm run cordova-build-android
npm run cordova-build-ios
npm run cordova-build-browser
```

## Built Mainly With

  - TailwindCSS [https://tailwindcss.com]
  - VueJS [https://vuejs.org/]
  - SASS [https://sass-lang.com/]
  - Cordova [https://cordova.apache.org/]


## Credits

* **[Pascal Hesselink](https://pascalhesselink.nl)** - *Setting up this boilerplate*


## License

This project is licensed under the MIT License
