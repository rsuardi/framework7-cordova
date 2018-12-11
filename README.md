# Framework7 Single View Starter App Template

A simple single view Framework7 starter app template.

## Usage

### 1. Download this repository
```
git clone https://github.com/rsuardi/framework7-cordova.git framework7-cordova
```

Repository will be downloaded into `framework7-cordova/` folder

### 2. Instal dependencies

Go to the downloaded repository folder and run:
```
npm install
```

This will download latest version of Framework7 (to `/www/framework7/`) and required icon fonts (to `/www/fonts/`)

### 3. Install Cordova

```
npm install -g cordova
```

### 4. Install android or IOS plaform

```
npm run add-android-platform
```
or
```
npm run add-ios-platform
```

### 5. Run the app

```
npm run serve
```

### Building/compiling the app into an APK (windows)

```
npm run wind-build
```

### Building/compiling the app into an APK (linux)

```
npm run linux-build
```

App will be opened in browser at `http://localhost:8080/`

## One command install

```
git clone https://github.com/rsuardi/framework7-cordova.git framework7-cordova &&
cd my-app &&
npm install &&
npm install -g cordova &&
npm run add-android-platform &&
npm run serve
```