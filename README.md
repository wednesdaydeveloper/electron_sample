# electron_sample

npm -g install electron-prebuilt

npm install -g asar

npm i electron-packager -g

electron main.js

asar pack ./electron_sample ./electron_sample.asar

electron-packager ./electron_sample electron_sample --platform=all --arch=x64 --version=0.36.7
