start project with `npx create-expo-app my-app`

installed automatically `create-expo-app@2.1.1`

run command `npx expo config --type public`

run `expo start` and see application on my mobile with expo client

Development build: Unable to get the default URI scheme for the project. Please make sure the expo-dev-client package is installed.
run `npm install expo-dev-client` because of above warning

run `expo login` my credential in chrome google password manager

document for build react native app with expo-eas https://docs.expo.dev/build/setup/
run `npm install -g eas-cli`
run `eas login`
run `eas build:configure`
run `eas build` # note: failed because I get 403, so I used 403.online

build was successful after 8 minute
and result aab file is available here
https://expo.dev/artifacts/eas/vxfbj1D4viWcG1aURV5sh4.aab
