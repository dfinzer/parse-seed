# parse-seed
A parse seed template for iOS apps with common dynamic functionality

# Notes
• Put your Parse keys in the config file
• Remember to update your Facebook ids in the info.plist
• Use Parse UI controllers as the starting point for tableviews and collectionviews


Parse-Seed
=======

<h1>Install Instructions</h1>
### Prerequisites
* <b>CocoaPods</b> You need to have node Cocoapods on your machine, get it here: [https://cocoapods.org](https://cocoapods.org)
* <b>Xcode</b> You need to have Xcode installed on your machine, get it here: [https://developer.apple.com/xcode/](https://developer.apple.com/xcode/)

### Setup
* <b>Parse Keys</b> Parse keys are added to the Config.swift file. You will need the App Id and ClientKey from the Parse web interface.
* <b>Facebook</b> If your app requires Facebook, you need to modify three fields in the Info.plist file as according to the iOS [https://developers.facebook.com/docs/ios/getting-started](SDK integration guide). They are "FacebookAppId", "FacebookDisplayName", and the "Item 0" under "URL types -> Item 0 -> URL Schemes".

### Code
* <b>TableViews</b> Subclass the PFQueryTableViewController and you will be a happy person.
* <b>CollectionViews</b> Subclass the PFQueryCollectionViewController and you will be a happy person.