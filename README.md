# testme

Client:
{
	  "name": "udeliverit-client",
	  "version": "0.0.1",
	  "angular-cli": {},
	  "scripts": {
	    "start": "ng serve",
	    "lint": "tslint \"src/**/*.ts\"",
	    "test": "ng test",
	    "pree2e": "webdriver-manager update  --standalone false --gecko false",
	    "e2e": "protractor"
	  },
	  "repository": {
	    "url": "https://github.com/narenmakwana/udeliverit.git",
	    "type": "git"
	  },
	  "author": "narenmakwana@gmail.com",
	  "private": true,
	  "dependencies": {
	    "@angular/common": "2.4.5",
	    "@angular/compiler": "2.4.5",
	    "@angular/compiler-cli": "2.4.5",
	    "@angular/core": "2.4.5",
	    "@angular/flex-layout": "2.0.0-beta.3",
	    "@angular/forms": "2.4.5",
	    "@angular/http": "2.4.5",
	    "@angular/material": "2.0.0-beta.1",
	    "@angular/platform-browser": "2.4.5",
	    "@angular/platform-browser-dynamic": "2.4.5",
	    "@angular/platform-server": "2.4.5",
	    "@angular/router": "3.4.5",
	    "@ngtools/webpack": "1.2.1",
	   "angular-cli": "^1.0.0-beta.28.3",
	    "angular2-google-maps": "^0.17.0",
	    "angular2-highcharts": "^0.4.1",
	    "angulartics2": "^1.6.3",
	    "chart.js": "^2.5.0",
	    "core-js": "^2.4.1",
	    "font-awesome": "^4.7.0",
	    "google-material-color": "^1.3.1",
	    "hammerjs": "^2.0.8",
	    "highcharts": "^5.0.7",
	    "ng2-charts": "^1.5.0",
	    "ng2-pagination": "^2.0.1",
	    "prismjs": "^1.5.1",
	    "rxjs": "5.0.1",
	    "ts-helpers": "^1.1.2",
	    "typescript": "^2.0.10",
	    "webpack": "^2.2.1",
	    "zone.js": "^0.7.2"
	  },
	  "devDependencies": {
	    "@types/chai": "^3.4.34",
	    "@types/hammerjs": "^2.0.33",
	    "@types/highcharts": "4.2.42",
	    "@types/jasmine": "^2.5.38",
	    "@types/prismjs": "^1.4.18",
	    "@types/node": "^6.0.42",
	    "angular-cli": "1.0.0-beta.26",
	    "autoprefixer": "^6.5.3",
	    "awesome-typescript-loader": "2.2.4",
	    "codelyzer": "~2.0.0-beta.1",
	    "jasmine-core": "2.5.2",
	    "jasmine-spec-reporter": "2.7.0",
	    "karma": "1.3.0",
	    "karma-chrome-launcher": "^2.0.0",
	    "karma-cli": "^1.0.1",
	    "karma-jasmine": "^1.0.2",
	    "karma-remap-istanbul": "^0.2.1",
	    "protractor": "4.0.11",
	    "ts-node": "1.2.1",
	    "tslint": "4.3.0",
	    "typescript": "~2.0.10"
	  }
	}

Server:
{
	  "name": "blueoak-server-template",
	  "version": "1.2.0",
	  "description": "Use this package as a template to create your own BlueOak Server-based project.",
	  "repository": {
	    "type": "git",
	    "url": "git@github.com:BlueOakJS/blueoak-server-template.git"

	  },
	  "license": "MIT",
	  "author": "Sean Kennedy <sean.kennedy@pointsource.com>",
	  "contributors": [
	    "Patrick Wolf <patrick.wolf@pointsource.com>"
	  ],
	  "scripts": {
	    "start": "blueoak-server",
	    "lint": "eslint --ignore-pattern node_modules **/*.js",
	    "test": "mocha --check-leaks --globals services,__appDir test/unit; npm run lint"
	  },
	  "dependencies": {
	    "activedirectory": "^0.7.2",
	    "apicache": "^0.8.3",
	    "blueoak-server": "^2.5.0",
	    "express-jwt": "^5.1.0",
	    "jsondiffpatch": "^0.2.4",
	    "udi-jwt-auth-service": "git+https://b23c2b026fbeebe0534844c1c7a997d24999a745:x-oauth-basic@github.allstate.com/nmakw/udi-jwt-auth-service.git",
	    "udi-mongodb-data-access": "git+https://b23c2b026fbeebe0534844c1c7a997d24999a745:x-oauth-basic@github.allstate.com/nmakw/udi-mongodb-data-access.git",
	    "xml2js": "^0.4.17"
	  },
	  "devDependencies": {
	    "eslint": "^2.7.0",
	    "eslint-config-defaults": "^9.0.0",
	    "mocha": "^2.4.5"
	  }
	}


