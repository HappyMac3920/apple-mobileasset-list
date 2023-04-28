# List of Apple MobileAssets
This is a list of MobileAssets to check if these MobileAssets moved to the Pallas (gdmf.apple.com) server or not.

## Why?

With iOS/iPadOS/tvOS/audioOS 14, watchOS 6 and macOS 11, Apple decided to introduce a new software update fetching mechanism codenamed Pallas.
This requires a POST request to gdmf.apple.com with required data. Before that, mesu.apple.com was used to fetch for iOS/iPadOS/watchOS/tvOS/watchOS, and swscan.apple.com for macOS.
However, with iOS/iPadOS/tvOS/audioOS 16, watchOS 9 and macOS 13, Apple decided to also implement Pallas to other MobileAssets (like Translation, Siri and even game controller assets) were moved to Pallas too.
This also made me challenging and even those who are archiving such files. Since Apple is currently in the transition phase, I decided to create a list of Apple MobileAssets and to indicate which asset is used for what and if it moved to Pallas or not.
If there is a MobileAsset that moved to pallas, I have also attached a curl command to send a request to the Apple server.

The list is incomplete for now. If I have time, I will expand this gist with more MobileAssets.
