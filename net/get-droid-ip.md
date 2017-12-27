### Get Android IP via Command Line

```sh
ifconfig wlan0 | grep 'inet addr:' | cut -d: -f2
adb shell ifconfig wlan0 | grep 'inet addr:' | cut -d: -f2
```
