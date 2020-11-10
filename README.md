# Last.fm
![Platform](https://img.shields.io/badge/platform-%EF%A3%BF-white)
[![Travis CI](https://img.shields.io/travis/DevShawnX/Last.fm/master.svg?logo=travis)](https://travis-ci.org/github/DevShawnX/Last.fm)
![Required OS](https://img.shields.io/badge/compatible-iOS%2012+-red)
![Code Size](https://img.shields.io/github/languages/code-size/DevShawnX/Last.fm)
![Last Commit](https://img.shields.io/github/last-commit/DevShawnX/Last.fm)
![MIT License](https://img.shields.io/github/license/DevShawnX/Last.fm)
![Open Source](https://img.shields.io/badge/open%20source-%F0%9F%92%9A-white)

**Last.fm** is a music player designed for iOS users to explore the most popular artists, albums and songs they love.

## Screenshots
![Login](https://user-images.githubusercontent.com/63318866/98600963-97622900-229b-11eb-9203-e80a9269ddf5.jpeg)
![Discover](https://user-images.githubusercontent.com/63318866/98610764-9afeab80-22ad-11eb-85f1-c06966e8276d.jpeg)
![Search Albums](https://user-images.githubusercontent.com/63318866/98600872-77326a00-229b-11eb-83d8-e2b5bc690a62.jpeg)
![Music Playing](https://user-images.githubusercontent.com/63318866/98600745-481bf880-229b-11eb-96fa-becdfeaf0cf1.jpeg)
![Albums](https://user-images.githubusercontent.com/63318866/98601792-c5943880-229c-11eb-9523-c07c67649f07.jpeg)
![Album Detail](https://user-images.githubusercontent.com/63318866/98600739-47836200-229b-11eb-8a8f-ad9dfd2a09ea.jpeg)
![Artists](https://user-images.githubusercontent.com/63318866/98601795-c62ccf00-229c-11eb-8587-1851c35585b0.jpeg)
![Artist Detail](https://user-images.githubusercontent.com/63318866/98600743-481bf880-229b-11eb-97b9-245dd12c56b1.jpeg)
![Profile](https://user-images.githubusercontent.com/63318866/98600746-48b48f00-229b-11eb-8bad-d8cd90d3ca10.jpeg)

## Developing Team
***Names listed in no paticular order***

|![DevShawnX](https://github.com/DevShawnX.png?size=120)<br />[DevShawnX](https://github.com/DevShawnX)|![John-Li-happy](https://github.com/John-Li-happy.png?size=120)<br />[John-Li-happy](https://github.com/John-Li-happy)|![ShawnLiii](https://github.com/ShawnLiii.png?size=120)<br />[ShawnLiii](https://github.com/ShawnLiii)|![lvbeauty](https://github.com/lvbeauty.png?size=120)<br />[lvbeauty](https://github.com/lvbeauty)|
|---|---|---|---|
|**Shawn Yu**|**John Li**|**Shawn Li**|**Tina Yi**|

## Build Information
- **IDE:** Xcode 11, 12
- **Agile Tool:** [Jira](https://www.atlassian.com/software/jira)
- **Git Client:** [SourceTree](https://www.sourcetreeapp.com/)
- **REST APIs:** [Last.fm](https://www.last.fm/api), [Deezer](https://developers.deezer.com)
- **Dependency Manager:** [CocoaPods](https://cocoapods.org/)
- **Languages:** Swift 5.3, Objective-C 2.0
- **Design Patterns:** MVVM, Singleton, Observation, Delegation
- **Frameworks:** UIKit, AVAudioPlayer, MediaPlayer, SafariServices
- **Dependencies:** [Alamofire](https://github.com/Alamofire/Alamofire), [HideShowPasswordTextField](https://github.com/Guidebook/HideShowPasswordTextField), [SkeletonView](https://github.com/Juanpe/SkeletonView), [SVProgressHUD](https://github.com/SVProgressHUD/SVProgressHUD), [SwiftGif](https://github.com/swiftgif/SwiftGif), [SwiftHash](https://github.com/onmyway133/SwiftHash)

## Installation
- **Compatibility:** Requires iOS 12.0 or later
- **Supporting Devices:**

|Screen Size|Device Models|
|---|---|
|4"|iPod Touch (6th & 7th Gen)|
|4"|iPhone 5s / SE (1st Gen)|
|4.7"|iPhone 6 / 6s / 7 / 8 / SE (2nd Gen)|
|5.5"|iPhone 6 Plus / 6s Plus / 7 Plus / 8 Plus|
|5.8"|iPhone X / Xs / 11 Pro|
|6.1"|iPhone XR / 11|
|6.5"|iPhone Xs Max / 11 Pro Max|

## Features
### Launch Screen
- A launchscreen with static and animated Last.fm logos

### Login Screen
- Creating a new account if you don't have one
- Safely logging in Last.fm accounts with user credentials
- Showing or hiding your passwords in the text field
- Resetting password if you forget

### Search Screen
- Searching songs or albums by simply clicking on the magnifying glass icon located at top right corner on **Discover**, **Albums** and **Artists** pages
- Listing relative songs or albums according to input keywords by switching segments on the segmented control

### Discover Screen
- Recommending songs which match users' taste
- Displaying the most popular and trending songs that people loved
- Playing songs with a simple tap on each track item

### Albums Screen
- Recommending trending albums collection which is popular around the community
- Displaying top albums collection which people played the most
- Expanding or collapsing the collection view by hitting the View All button
- Navigating to album detail by tapping on each collection item
- Adding all the songs within the album into playlist and playing
- Sharing the album with your friends via texts or social networking apps

### Artists Screen
- Displaying top artists with high exposure rates among fans
- Navigating to artist detail by tapping on each collection item
- Showing artists' listeners and scrobbles numbers
- Listing artists' top albums and top songs with music playing function integrated
- Recommending similiar artists that listeners might be interested in
- Expanding or collapsing the collection view by hitting the View All button
- Finding cover versions by clicking on the ellipsis "**∙∙∙**" button

### Profile Screen
- Displaying user account info including avatar, real name, account name, gender, age, scrobbles count and country
- Showing recent tracks and top tracks associated to users' Last.fm accounts
- Listing users' top artists which they listen to the most
- Tapping on each tracks item to play the song
- Tapping on each artist to navigate to artist detail page
- Logging out the current account by clicking on Log out button

### Music Playing Screen
- Adjusting playing volume by sliding the white round control on volumn bar
- Displaying track names and artists as well as spinning track cover at the center while playing
- Fast forwarding or reversing the song by sliding the white round control on progress bar
- Music playing controls including Play/Pulse, Previous and Next
- Multiple playing orders available in Sequential, Random and Single Cycle
- Displaying and Controlling the music playing through Notification Center or Control Center
- Easily sharing songs with your friends through texts or social networking apps up to your choices

## License
This project is licensed under the terms of the MIT license. Check the [MIT LICENSE](https://github.com/DevShawnX/Last.fm/blob/master/LICENSE) for more details.
