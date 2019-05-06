
# react-native-transorm-rn-demo

## Getting started

`$ npm install react-native-transorm-rn-demo --save`

### Mostly automatic installation

`$ react-native link react-native-transorm-rn-demo`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-transorm-rn-demo` and add `RNTransormRnDemo.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNTransormRnDemo.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.communicationtest.RNTransormRnDemoPackage;` to the imports at the top of the file
  - Add `new RNTransormRnDemoPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-transorm-rn-demo'
  	project(':react-native-transorm-rn-demo').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-transorm-rn-demo/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-transorm-rn-demo')
  	```


## Usage
```javascript
import RNTransormRnDemo from 'react-native-transorm-rn-demo';

// TODO: What to do with the module?
RNTransormRnDemo;
```
  第一次尝试RN项目作为第三方的方式上传到gitHub 上.
  使用到的库文件: react-native-create-library ;
  ```
  npm install -g react-native-create-library
  ```
  ```
   react-native-create-library --package-identifier com.xxx --platforms android,ios appName
  ```
  参考文档:[!https://www.jianshu.com/p/091a68ea1ca7](https://www.jianshu.com/p/091a68ea1ca7)
