# react-native-maple-lock

## Getting started

`$ npm install react-native-maple-lock --save`

### Mostly automatic installation

`$ react-native link react-native-maple-lock`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-maple-lock` and add `MapleLock.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libMapleLock.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainApplication.java`
  - Add `import ca.maplepost.MapleLockPackage;` to the imports at the top of the file
  - Add `new MapleLockPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-maple-lock'
  	project(':react-native-maple-lock').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-maple-lock/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-maple-lock')
  	```


## Usage
```javascript
import MapleLock from 'react-native-maple-lock';

// TODO: What to do with the module?
MapleLock;
```
