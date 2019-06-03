# adBlock
AdBlock is an ad blocking HTTP proxy for your Android device. 

I use this project to create a proxy server on mobile phone
and then proxy the dedicate app in my working pc to internet via adb link.

usage:


1. install adblock.apk
2. link adb to pc
3. enable adb debug on phone
4. start the app, default proxy port 8080
5. configure proxy server on pc 127.0.0.1:5556
6. and run
adb forward tcp:5556 tcp:8080

then the app can use mobile network and avoid to be blocked by enterprise fireware.
at the same time you can use the intranet.
