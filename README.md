WiFiInfo
========

Cordova get SSID WiFI information Android and iOS, forked from [KinG-InFeT](https://github.com/KinG-InFeT/WiFiInfo)

# WiFi Info plugin for (Android/iOS)/(Phonegap/Cordova) >= 3.0.0
By Linkpass S.r.l.

## Plugin Installation

### Phonegap/Cordova vers 3.x.x 

* Run terminal

```text
cordova plugins add https://github.com/FranzMari/WiFiInfo.git
```
OR

* Use config.xml
```text
<plugin name="org.apache.cordova.wifiinfo" source="git" spec="git+https://github.com/FranzMari/WiFiInfo.git" />
```

* Call the plugin:

```javascript
WiFiInfo.getInfo( 
    function(wifi_name) {         
     alert(wifi_name);//SSID OF Wireless connection
    }, 
    function() {
        //error get SSID
    });
```

* That's all Folks!! ;)

## CHANGELOG
### 17/03/2020 (vers. 0.1.1)
Fix dependencies' ids to make this plugin work with latest cordova release (9.0.0) and android platform (8.1.0)  

### 29/08/2014 (vers 0.1.0)
* Initial release (Tested with Cordova 3.5.0, platform android v4.4.4)

Thanks for the attention ;)
