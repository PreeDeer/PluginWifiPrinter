## PluginWifiPrinter

Cordova Plugin สำหรับพิมพ์ผ่าน Wi-Fi Printer

### Install
```bash
ionic cordova plugin add https://github.com/PreeDeer/pluginwifiprinter.git

### remove
ionic cordova plugin remove com.yourcompany.pluginwifiprinter

### Usage
cordova.plugins.PluginWifiPrinter.print(
  ip,
  port,
  data,
  success => console.log(success),
  err => console.error(err)
);

## รองรับแพลตฟอร์ม
- Android
- iOS
