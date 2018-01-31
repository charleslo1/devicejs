# Inrto
> A client type recognition library

## Install
``` sh
$ npm install devicejs --save
```

## Usage
``` js
import device from 'devicejs'

// usage
console.log( device.mobile )
console.log( device.phone )
console.log( device.tablet )
console.log( device.pc )
```

## Api

### device
* device.mobile       // is mobile (phone or tablet)
* device.phone        // is phone  (only phone)
* device.tablet       // is tablet (only tablet)
* device.pc           // is pc     (only pc)

### device.os
* device.os.andriod
* device.os.ios
* device.os.osx
* device.os.windows
* device.os.windowsPhone

### device.browser
* device.browser.ie
* device.browser.edge
* device.browser.chrome
* device.browser.safari
* device.browser.weixin
* device.browser.wxapp

### device.engine
* device.engine.blink
* device.engine.webkit
* device.engine.gecko
* device.engine.trident

# Links
* [isMobile](https://github.com/kaimallea/isMobile)
* [current-device](https://github.com/matthewhudson/current-device)
* [ua-parser-js](https://github.com/faisalman/ua-parser-js)
