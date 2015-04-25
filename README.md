Parse-Seed
=======

<h1>Install Instructions</h1>
### Prerequisites
* <b>CocoaPods</b> You need to have node Cocoapods on your machine, get it here: [https://cocoapods.org](https://cocoapods.org)
* <b>Xcode</b> You need to have Xcode installed on your machine, get it here: [https://developer.apple.com/xcode/](https://developer.apple.com/xcode/)

### Setup
* <b>CocoaPods</b> Once Cocoapods is installed on your computer, cd into the root directory of this project and run ```pod install```

### Keys
* <b>Parse Keys</b> Parse keys are added to the Config.swift file. You will need the App Id and ClientKey from the Parse web interface.
* <b>Facebook</b> If your app requires Facebook, you need to modify three fields in the Info.plist file as according to the iOS [SDK Integration Guide](https://developers.facebook.com/docs/ios/getting-started). They are "FacebookAppId", "FacebookDisplayName", and the "Item 0" under "URL types -> Item 0 -> URL Schemes".

### Code
* <b>TableViews</b> Subclass the PFQueryTableViewController and you will be a happy person. You will need to override the ```tableView:cellForRowAtIndexPath:object:``` method and dequeue the reusable cell there. Remember to register the cell as a nib on load or init.

* <b>CollectionViews</b> Subclass the PFQueryCollectionViewController and you will be a happy person. You will need to override the ```collectionView:cellForRowAtIndexPath:object:``` method and dequeue the reusable cell there. Remember to register the cell as a nib on load or init.