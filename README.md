# SwiftUI-StatusBar-Controller
Fork of https://github.com/xavierdonnellon/swiftui-statusbarstyle.git

# Implementation

Add `RootView` To your main Swift file.

```swift
@main
struct MyApp: App {     
    var body: some Scene {
        WindowGroup {
            //wrap main view in RootView
            RootView {
                //Put the view you want your app to present here
                ContentView()
                    //add necessary environment objects here 
            }
        }
    }
}
```

Then you can use `.statusBarStyle(.lightContent)` on your view to implement it

```swift
.statusBarStyle(.lightContent)
```
