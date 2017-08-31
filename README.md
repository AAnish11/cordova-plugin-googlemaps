# Cordova GoogleMaps plugin for iOS and Android (version 2.0 beta)


### Quick install
$> cordova plugin add https://github.com/AAnish11/cordova-plugin-googlemaps.git#working_map_code --variable API_KEY_FOR_ANDROID="YOUR_ANDROID_API_KEY_IS_HERE" --variable API_KEY_FOR_IOS="YOUR_IOS_API_KEY_IS_HERE"
```

If you re-install the plugin, please always remove the plugin first, then remove the SDK

```bash
$> cordova plugin rm cordova-plugin-googlemaps
$> cordova plugin rm com.googlemaps.ios
$> cordova plugin add cordova plugin add https://github.com/AAnish11/cordova-plugin-googlemaps.git#working_map_code --variable API_KEY_FOR_ANDROID="YOUR_ANDROID_API_KEY_IS_HERE" --variable API_KEY_FOR_IOS="YOUR_IOS_API_KEY_IS_HERE"
```

### Configuration

You can also configure the following variables to customize the iOS location plist entries

- `LOCATION_WHEN_IN_USE_DESCRIPTION` for `NSLocationWhenInUseUsageDescription` (defaults to "Show your location on the map")
- `LOCATION_ALWAYS_USAGE_DESCRIPTION` for `NSLocationAlwaysUsageDescription` (defaults t "Trace your location on the map")