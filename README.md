4d-plugin-apple-push-notification
=================================
This plugin is a 4D implementation of the ​[Apple Push Notifications API](http://developer.apple.com/library/ios/#documentation/NetworkingInternet/Conceptual/RemoteNotificationsPG/Introduction/Introduction.html). It offers capability to send JSON packets ("payloads") to a specific application installed on a specific device (iPhone or iPad). It is the developer's responsibility to create an iOS application, register it with the appropriate provision, create the right SSL certificates and install it on a device. On the other hand, this plugin will take care of sending TCP data to that device in the expected format, with client side authentication and SSL.

### Platform

| carbon | cocoa | win32 | win64 |
|:------:|:-----:|:---------:|:---------:|
|<img src="https://cloud.githubusercontent.com/assets/1725068/22371562/1b091f0a-e4db-11e6-8458-8653954a7cce.png" width="24" height="24" />|<img src="https://cloud.githubusercontent.com/assets/1725068/22371562/1b091f0a-e4db-11e6-8458-8653954a7cce.png" width="24" height="24" />|||

Commands
---

```c
// --- Apple Push Notification
APN_Get_sandbox_url
APN_SET_PRODUCTION_URL
APN_Get_production_url
APN_Get_pem_path
APN_SET_PEM_PATH
APN_Push_Payload
APN_SET_SANDBOX_PORT
APN_SET_SANDBOX_URL
APN_Get_sandbox_port
APN_SET_PRODUCTION_PORT
APN_Get_production_port
```
