1.**Olesia Buldakova**
2.phone: +375298702002, email: olesiabuldakova.work@gmail.com
3.my goal is to learn obj-с and to understand how platform is working from the inside. 
I’m tended to be a reliable, conscientious, persistent and resilient person, can effectively find a solution for issues in a limited period of time. Interested in everything new about technologies and always "hungry" to education
4.Skills: 
    Swift, 
    Xcode
    UIKit
    AutoLayout
    MVC, MVVM
    Parsing JSON
    GIT 
    Core Animation,
    Core Location,
    AVFoundation,
    MapKit,
    Firebase,
    Realm,
    Cocoa Pods
5. here is some code as an example, projects will be below
```swift
fileprivate func allModels(for contents: [Nextradiotv.TemplateContentModel]) -> [Nextradiotv.VideoModel] {
      return contents.flatMap { content -> [Nextradiotv.VideoModel] in
        content.elements.flatMap { element -> [Nextradiotv.VideoModel] in
          switch element.items {
          case .video(let models):
            return models
          default: return []
          }
        }
      }
```
6. [Stendford courses projects] (https://bitbucket.org/olesiaBuldakova/internship/src/master/)
   [weather app example] (https://bitbucket.org/olesiaBuldakova/weather/src/master/)
   [travel diary app] (https://bitbucket.org/olesiaBuldakova/l01_travel_buldakovaop/src/master/)
7. BSEU, TeachMeSkills, Udemy, swiftBook.ru
8. Upper-intermediate
