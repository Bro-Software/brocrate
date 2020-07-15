# BroCrate
A unofficial desktop version of Github

## Clone and test directly from the source
1. Clone the repository
2. Run `npm init`
3. Run `npm install --save-dev electron`
4. Run `npm start`

## Build
For build the app, you need to install `electron-packager`:
`npm install electron-packager --save-dev`

### For you machine
Run `electron-packager . BroCrate --icon=icon.png`

### For Windows

* x32:
Run `electron-packager . BroCrate --plaform=win --arch=x32 --icon=icon.png`

* x64:
Run `electron-packager . BroCrate --plaform=win --arch=x64 --icon=icon.png`

### For Mac

* x32:
Run `electron-packager . BroCrate --plaform=darwin --arch=x32 --icon=icon.png`

* x64:
Run `electron-packager . BroCrate --plaform=darwin --arch=x64 --icon=icon.png`

### For Linux

* x32:
Run `electron-packager . BroCrate --plaform=linux --arch=x32 --icon=icon.png`

* x64:
Run `electron-packager . BroCrate --plaform=linux --arch=x64 --icon=icon.png`