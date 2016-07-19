## Getting started

Install dependencies

`
npm install
`

Install type definitions

`
typings install
`

To build changes

`
npm run build
`

To watch changes

`
npm run watch
`

Compile typescript files

`
npm run tsc
`

Run application

`
npm run start
`


Make Electon Package

`
electron-packager . <AppName> --platform=win32 --arch=x64 --overwrite --version=0.37.4
`
"distributeWin": "electron-packager . MyApp-tool-suite --platform=win32 --arch=x64 --out=releases2/ --overwrite --icon=src/assets/images/icon  --asar"
asar pack someFolderName-win32-x64/resources/app someFolderName-win32-x64/resources/app.asar