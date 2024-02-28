# electron-learning

## 1. first check node and npm
```
node -v
npm -v
```

## 2. install electron
```
npm install --save-dev electron

// run app
npm start
```

## 3. package app
```
npm config set registry=https://registry.npmmirror.com/
npm config set ELECTRON_MIRROR=https://npmmirror.com/mirrors/electron/
npm i -g @electron-forge/cli
npm i @electron-forge/plugin-fuses
npx electron-forge import
npm run make
```
