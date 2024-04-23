1. Create an app with - npx create-expo-app MyApp
2. Then run this to generate the native android directory - npx expo run:android
3. I then added android and iOS to my .gitignore and ran this command npx expo prebuild --clean
4. npx expo run:ios took longer to work. had to get cocoapods to work. i had to do this in the Podfile use_frameworks! :linkage => :static, and add it after config = use_native_modules
