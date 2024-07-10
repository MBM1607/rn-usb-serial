# Installation

You should run

```sh
npm add rn-usb-serial
```

or

```sh
yarn add rn-usb-serial
```

or

```sh
pnpm add rn-usb-serial
```

## Expo

If you are using Expo then installation is complete and you don't need to make any further changes

## Bare React Native

### Automatic Installation

```
react-native link react-native-serialport
```

### Manual Installation

#### 1. Open up `android/app/src/main/java/[...]/MainActivity.java`

- Add `import com.reactlibrary.RNSerialportPackage;` to the imports at the top of the file
- Add `new RNSerialportPackage()` to the list returned by the `getPackages()` method

#### 2. Append the following lines to `android/settings.gradle`

```
include ':react-native-serialport'
project(':react-native-serialport').projectDir = new File(rootProject.projectDir,
'../node_modules/react-native-serialport/android')
```

### 3. Insert the following lines inside the dependencies block in `android/app/build.gradle`

```
implementation project(':react-native-serialport')
```
