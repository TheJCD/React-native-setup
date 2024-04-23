1. Create an app with - npx create-expo-app MyApp
2. Then run this to generate the native android directory - npx expo run:android
3. Run this command to generate the native ios directory - npx expo run:ios
4. You might need to add this line in the podfile to get ios to work - `use_frameworks! :linkage => :static` add it after `config = use_native_modules`
