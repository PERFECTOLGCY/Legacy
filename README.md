<h1 align="center">
WG Tunnel
</h1>

<div align="center">

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Discord Chat](https://img.shields.io/discord/1108285024631001111.svg)](https://discord.gg/rbRRNh6H7V)

</div>

<div align="center">


[![Google Play](https://img.shields.io/badge/Google_Play-414141?style=for-the-badge&logo=google-play&logoColor=white)](https://play.google.com/store/apps/details?id=com.zaneschepke.wireguardautotunnel)
[![Fire TV](https://img.shields.io/badge/fire%20tv-fc3b2d?style=for-the-badge&logo=amazon%20fire%20tv&logoColor=white)](https://www.amazon.com/gp/product/B0CFGGL7WK)
[![F-Droid](https://img.shields.io/static/v1?style=for-the-badge&message=F-Droid&color=1976D2&logo=F-Droid&logoColor=FFFFFF&label=)](https://f-droid.org/packages/com.zaneschepke.wireguardautotunnel/)


</div>

<div align="center">

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/N4N8NMJN2)

</div>


<div align="left">

This is an alternative Android Application for [WireGuard](https://www.wireguard.com/) with added features. Built using the [wireguard-android](https://github.com/WireGuard/wireguard-android) library and [Jetpack Compose](https://developer.android.com/jetpack/compose), this application was inspired by the official [WireGuard Android](https://github.com/WireGuard/wireguard-android) app.

</div>

<div align="center">

## Screenshots

<p float="center">
  <img label="Main" style="padding-right:25px" src="asset/main_screen.png" width="200" />
  <img label="Config" style="padding-left:25px" src="asset/config_screen.png" width="200" />
  <img label="Settings" style="padding-left:25px" src="asset/settings_screen.png" width="200" />
  <img label="Support" style="padding-left:25px" src="asset/support_screen.png" width="200" />
</p>

<div align="left">

## Inspiration

The inspiration for this app came from the inconvenience of constantly having to turn VPN off and on while on different networks. With there being no free solution to this problem, this app was created to meet that need.

## Features

* Add tunnels via .conf file
* Auto connect to VPN based on Wi-Fi SSID
* Split tunneling by application with search
* Always-on VPN for Android support
* Quick tile support for vpn toggling
* Dynamic shortcuts support for automation integration
* Configurable Trusted Network list 
* Optional auto connect on mobile data
* Automatic service restart after reboot
* Service will stay running in background after app has been closed


## Building
    
```
$ git clone https://github.com/zaneschepke/wgtunnel
$ cd wgtunnel
$ ./gradlew assembleRelease
```

</span>
