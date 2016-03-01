# angular2-form-dynamic
A modified content based on: http://www.syntaxsuccess.com/angular-2-samples/#/demo/survey

## Documentation

### Setup

Dependencies:
```
npm init -y
npm install typescript typings@1.8 tslint lite-server modernizr --save-dev
```
Configurations:
```
./node_modules/typescript/bin/tsc --init
./node_modules/typings/dist/bin/typings init
mkdir config
cd config/
../node_modules/tslint/bin/tslint --init
../node_modules/browser-sync/bin/browser-sync.js init
cd ../
cd src/vendor/js
../../../node_modules/modernizr/bin/modernizr -c ../../../config/modernizr-config.json
```
(a project template would be nice btw.)

## Author
@peterblazejewicz
