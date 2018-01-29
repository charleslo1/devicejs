# devicejs
> A client type recognition library

## Install
``` sh
$ npm install devicejs --save
```

## Usage
``` js
import device from 'devicejs'

// usage
console.log( device.phone )
console.log( device.tablet )
console.log( device.pc )
```

## Api

### device
* device.phone
* device.tablet
* device.pc

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
* device.browser.wechat

### device.engine
* device.engine.blink
* device.engine.webkit
* device.engine.gecko
* device.engine.trident

