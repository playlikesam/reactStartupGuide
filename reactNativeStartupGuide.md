Get started with React-Native :

step 1 :
```
npx create-expo-app ./
```
step 2 : this command might takes time so, intall it in components accordingly
```
npx expo install expo-router react-native-safe-area-context react-native-screens expo-linking expo-constants expo-status-bar
```
step 3 : rename your application name by modifying "app.json". After necessary modifications
```
npx expo start -c
```
or
```
npx expo start
```


Steps to Download the react native application in apk format

Step 1 : 
```
npm install -g eas-cli
```
Step 2 : 
```
eas login
```
Step 3 :
```
eas build:configure
```
Step 4 :
```
eas build -p android --profile preview
```
