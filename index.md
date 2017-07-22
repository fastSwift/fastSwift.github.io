---
layout: default
---

<img src="http://coldg.ddns.net/wp-content/uploads/2017/05/fastSwift-1.png" width="200px">
<br/>
<br/>
<img class="alignnone wp-image-113" src="http://coldg.ddns.net/wp-content/uploads/2017/05/IMG_2420.png" alt="" width="168" height="299"><img class="alignnone size-medium wp-image-114" src="http://coldg.ddns.net/wp-content/uploads/2017/05/IMG_2421.png" alt="" width="169" height="300"><img class="alignnone size-medium wp-image-115" src="http://coldg.ddns.net/wp-content/uploads/2017/05/IMG_2422.png" alt="" width="169" height="300">
<br/>

## Features
- With fastSwift you can compile and run multiple Swift files with our server or a custom server, the program can ask for user input.
- Is easy to share scripts.
- The app supports UIDocumentBrowserViewController.

## FFKit
FFKit is an auto imported library from server side, before the compilation.

```swift
try session?.channel.execute("cp /home/fastswift/FFKit.swift '\((UIDevice.current.identifierForVendor!.uuidString))'"
```
Code from [DocumentViewController.swift](https://github.com/ColdGrub1384/fastSwift/blob/master/fastSwift/DocumentViewController.swift)

FFKit alows to interact with fastSwift app doing things such as clearing the shell, downloading executable file into the device or showing an activity indicator and also to manage files in server side.

[FFKit.swift](https://github.com/ColdGrub1384/fastSwift-Server-Installer/blob/master/FFKit.swift)

## Host a server
If you want to host a fastSwift server go [here](https://github.com/ColdGrub1384/fastSwift-Server-Installer/blob/master/README.md)

### Why host a fastSwift server?
If you host a server you can customize FFKit, if your server is private, you can run scripts as admin user to get privileges, control scripts database manually and more things, just make your imagination fly.
