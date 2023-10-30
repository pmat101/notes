## General info about iOS
- Any input provided by the user is registered by the phone's sensors this info is sent to the OS which interprets it and sends message to the concerned app asking what it should do
- Main components of an app: **Screen UI, Code and Data** *(also consider events, gestures, OS specifications and background running etc)*
- As an app developer you must have knowledge of DSA so as to make apps that use less data, processing power and resources of the phone

---

> XCode is an IDE used for app development where the code is written in Swift, while SwiftUI is a framework used to rapidly build apps for all of Apple's platforms (iOS, ipad, watch, TV or mac). Apps are distributed using app store by joining the Apple Developer programme.

---

## How to start a new project 
- new project > iOS > app > projects details
- **content view** contains all code and *preview pane*
- top right corner of XCode is the **library** containing all the *views*, *modifiers* (they change attributes of views)
- #### VIEWS
  - Views library can be used to add elements like text, image, button, layout container etc on the screen
  - layout containers help us arrange views in x/y/z axis on the UI
  - Views typically take as much space as their content (similar to inline elements), use *Spacer view* to spread them apart
- #### MODIFIERS
  - Modifiers added to the VIEWS to change their look or behavior eg. aspect ratio, corner radius, size, font weight, (background) color, foreground color or padding of view items
  - *ignoreSafeArea* can be used to cover top & bottom of screen
  - Modifier if added to a container view gets applied to each element inside
- the left panel is the *navigator*, middle is the *editor*, right panel is the *utility area*, *toolbar* at the top and *debug area* at the bottom
- the iOS simulator lets us test our app on an onscreen virtual device
- we can see/edit general settings of the project at the root node of the file navigator 
- **contentView** is the first screen shown when the app is launched
- **assets** folder contains all images, icons etc
- go to windows > documentation if you need any help
- **SF Symbols** are a set of icons provided by Apple
- we can add *action* and *label* modifiers to buttons, action- adds functionality and label- can change its visual representation
- the UI doesn't display integers, convert int to string before displaying (also known as *casting*)
- use **@State** property wrapper to use a variable inside a *struct*
- right click > refactor > rename (to rename something and all its instances)
