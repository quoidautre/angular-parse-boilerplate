AngularJS Parse Boilerplate
===========================
[![Gitter](https://badges.gitter.im/Join Chat.svg)](https://gitter.im/jbeurel/angular-parse-boilerplate?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

[Demo :-)](http://jbeurel.github.io/angular-parse-boilerplate)

# Use cases 

 * https://github.com/jbeurel/rider-ranking - Use Instagram to rank BMX riders by number of followers

# Technologies

## Languages
- [Coffeescript](http://coffeescript.org/)
- [Jade](http://jade-lang.com/)
- [Less](http://www.lesscss.org/)

## Framework|Tools
- [AngularJS](http://angularjs.org/)
- [AngularUI (Bootstrap)](http://angular-ui.github.io/bootstrap/)
- [Bootstrap3](http://getbootstrap.com/)
- [Gulp](http://gulpjs.com/)
- Livereload

# Requirements

- [NodeJS](http://nodejs.org/)

# Installation

  `npm install`

# Development server

  `npm run-script watch`

Access to the application at this address: http://127.0.0.1:8008
The livereload update your browser each time you change source files.

# Deploy 

## GitHub Pages

  `npm run-script deploy-client`

## Parse.com

The first time, install Parse CLI

  `curl -s https://www.parse.com/downloads/cloud_code/installer.sh | sudo /bin/bash`

and

  `npm run-script deploy-server`
  
## both

  `npm run-script deploy`
  
# Codeship: Continuous Delivery

Deployment > Custom script

```
git remote set-url origin git@github.com:johndoe/angular-parse-boilerplate.git
git config --global user.email "john.doe@email.com"
git config --global user.name "John Doe"
curl https://www.parse.com/downloads/cloud_code/parse -o ${HOME}/bin/parse
chmod 755 ${HOME}/bin/parse
npm run deploy
```

  
