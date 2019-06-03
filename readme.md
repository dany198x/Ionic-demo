//Install cordova & ionic environment:

npm install -g cordova ionic

//Under the project root path run install:

npm install

//Run on localhost:

ionic serve

//Build to static html/js, after this command you will see the 'www' directory:

ionic build

//Add platforms, after this command you will see 'platforms' directory:

ionic cordova platform add ios

ionic cordova platform add android

//After above 2 commands, you can find the android and ios projects under the platforms folder.

//Everytime after update the source code:

ionic cordova build ios //Be noticed this command is only valid on MacOS

ionic cordova build android

The png file under the root path show the directory structure of the project.
