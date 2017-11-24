## Cordova Jailbreak Detection Plugin

This plugin is combination of

https://github.com/leecrossley/cordova-plugin-jailbreak-detection.git

and 

https://github.com/masbog/isJB

## Install

cordova plugin add https://github.com/martinkasa/cordova-plugin-jailbreak-detection.git

### isJailbroken

```js
jailbreakdetection.isJailbroken(successCallback, failureCallback);
```

- => `successCallback` is called with true if the device is Jailbroken, otherwise false
- => `failureCallback` is called if there was an error determining if the device is Jailbroken

## Platform Support

iOS only.

## License

[MIT License](http://ilee.mit-license.org)
