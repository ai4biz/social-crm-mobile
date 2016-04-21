# social-crm-mobile
Social CRM Mobile

###PhoneGap
http://phonegap.com
http://docs.phonegap.com/getting-started/1-install-phonegap/desktop/

### Install
Run the command line below:

```
npm install -g bower yo gulp generator-mobileangularui
```

Then run the command to install phonegap:
```
sudo npm install -g phonegap
```

Install Gulp
```
npm install gulp
```

### Fix Error below:

```
Caios-MacBook-Pro:Geolocation_Phonegap caiomsouza$ gulp
module.js:341
    throw err;
    ^

Error: Cannot find module 'run-sequence'
    at Function.Module._resolveFilename (module.js:339:15)
    at Function.Module._load (module.js:290:25)
    at Module.require (module.js:367:17)
    at require (internal/module.js:16:19)
    at Object.<anonymous> (/Users/caiomsouza/git/github.com/Geolocation_Phonegap/gulpfile.js:66:22)
    at Module._compile (module.js:413:34)
    at Object.Module._extensions..js (module.js:422:10)
    at Module.load (module.js:357:32)
    at Function.Module._load (module.js:314:12)
    at Module.require (module.js:367:17)

```

Fixed typing:

```
npm install
```

###Error 2

```
Caios-MacBook-Pro:Geolocation_Phonegap caiomsouza$ gulp
[14:04:54] Using gulpfile ~/git/github.com/Geolocation_Phonegap/gulpfile.js
[14:04:54] Starting 'default'...
[14:04:54] Starting 'build'...
[14:04:54] Starting 'clean'...
[14:04:54] Finished 'clean' after 35 ms
[14:04:54] Starting 'html'...
[14:04:54] Finished 'html' after 2.42 ms
[14:04:54] Starting 'fonts'...
[14:04:54] Starting 'images'...
[14:04:54] Starting 'less'...
[14:04:54] Starting 'js'...
[14:04:54] Finished 'js' after 13 ms
[14:04:54] Finished 'fonts' after 24 ms
[14:04:54] Finished 'images' after 23 ms
Potentially unhandled rejection [2] 'mobile-angular-ui/src/less/mobile-angular-ui-base.less' wasn't found. Tried - /Users/caiomsouza/git/github.com/Geolocation_Phonegap/src/less/mobile-angular-ui/src/less/mobile-angular-ui-base.less,/Users/caiomsouza/git/github.com/Geolocation_Phonegap/src/less/mobile-angular-ui/src/less/mobile-angular-ui-base.less,/Users/caiomsouza/git/github.com/Geolocation_Phonegap/bower_components/mobile-angular-ui/src/less/mobile-angular-ui-base.less,mobile-angular-ui/src/less/mobile-angular-ui-base.less in file /Users/caiomsouza/git/github.com/Geolocation_Phonegap/src/less/app.less line no. 1

```

Fixed typing:

```
bower install --save mobile-angular-ui
```

###To Run the app just type the command below in the app folder:

```
gulp
```

Output: 
```
Caios-MacBook-Pro:Geolocation_Phonegap caiomsouza$ gulp
[14:11:26] Using gulpfile ~/git/github.com/Geolocation_Phonegap/gulpfile.js
[14:11:26] Starting 'default'...
[14:11:26] Starting 'build'...
[14:11:26] Starting 'clean'...
[14:11:26] Finished 'clean' after 27 ms
[14:11:26] Starting 'html'...
[14:11:26] Finished 'html' after 3.13 ms
[14:11:26] Starting 'fonts'...
[14:11:26] Starting 'images'...
[14:11:26] Starting 'less'...
[14:11:26] Starting 'js'...
[14:11:26] Finished 'js' after 13 ms
[14:11:26] Finished 'images' after 40 ms
[14:11:29] Finished 'fonts' after 3.75 s
[14:11:35] Finished 'less' after 9.66 s
[14:11:35] Finished 'build' after 9.7 s
[14:11:35] Starting 'weinre'...
2016-04-21T12:11:35.920Z gulp: starting server at http://localhost:8001
[14:11:35] Finished 'weinre' after 87 ms
[14:11:35] Starting 'connect'...
[14:11:35] Finished 'connect' after 8.42 ms
[14:11:35] Starting 'watch'...
[14:11:35] Finished 'watch' after 25 ms
[14:11:35] Finished 'default' after 9.82 s
[14:11:35] Server started http://0.0.0.0:8000
[14:11:35] LiveReload started on port 35729
connect deprecated res.headerSent: use standard res.headersSent node_modules/express/node_modules/connect/lib/http.js:149:22
```

### Type the command below To create:

iOS version
```
phonegap run ios
```

Android version
```
phonegap run android
```

### Open the browser at http://localhost:8000








