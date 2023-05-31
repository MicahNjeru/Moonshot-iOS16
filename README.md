#  Moonshot iOS 16

## About Moonshot
- This is an app that shows details about the Apollo missions and their crew
- It has some data on the crew member and the missions, such as the:
    1. Mission dates and short descriptions
    2. Crew member names, roles and ranks
- It is a static application that does not let the user add/modify anything in anyway

## What I've learnt
- Using the `JSONDecoder()` provided by Swift is very useful and reinforces Swift's safe type feature by having you explicitly declare all attributes `keys`
that Swift should expect by having the struct conform to the `Codable` protocol. 
- The `JSONDecoder()` also helps convert data from `JSON` files into Swift data types for manipulation
- `NavigationLink` & `NavigationView` help abstract all the complex code needed to navigate from one view to another 
- Also, SwiftUI's modifiers are very structured and easy to use and allows us to design the view however we want programatically and not have to worry about
fine graining the views to fit every Apple Device.
- GeometryReader also helps a lot with fine tuning views to conform to our liking especially when modifying images to fit to specific constraints. 
 

