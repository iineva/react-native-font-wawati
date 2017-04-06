
# react-native-wawati

## Getting started

`$ npm install react-native-wawati --save`

### Mostly automatic installation

`$ react-native link react-native-wawati`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-wawati` and add `RNWawati.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNWawati.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNWawatiPackage;` to the imports at the top of the file
  - Add `new RNWawatiPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-wawati'
  	project(':react-native-wawati').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-wawati/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-wawati')
  	```

#### Windows
[Read it! :D](https://github.com/ReactWindows/react-native)

1. In Visual Studio add the `RNWawati.sln` in `node_modules/react-native-wawati/windows/RNWawati.sln` folder to their solution, reference from their app.
2. Open up your `MainPage.cs` app
  - Add `using Com.Reactlibrary.RNWawati;` to the usings at the top of the file
  - Add `new RNWawatiPackage()` to the `List<IReactPackage>` returned by the `Packages` method


## Usage
```javascript
import RNWawati from 'react-native-wawati';

// TODO: What to do with the module?
RNWawati;
```
  