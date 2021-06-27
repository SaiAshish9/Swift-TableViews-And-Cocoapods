# Linking two files at storyboard file

```
select the left most icon of one screen at storyboard and drag it to other screen present in the same file.
```

# Rebuild the app

```
cmd + B
```

# Triggered segue and navigation controller

```
select left most icon of the screen and pick embed in navigation controller option.
```

# Swift loops

```
for _ in 1...5{print("s")}

override func viewDidLoad(){
   super.viewDidLoad()
   Timer.scheduledTime(withTimeInterval:0.1*charIndex,repeats:false){
     (timer) in self.titleLabel.text?.append(letter)
   }
}

override func viewWillAppear(_ animated:Bool){
   super.viewWillAppear(animated)
   navigationController?.isNavigationBarHidden = true
}

override func viewDidAppear(_ animated:Bool){
   super.viewDidAppear(animated)
   navigationController?.isNavigationBarHidden = false
}

while now < s{
 now = Date().timeIntervalsince1970
 print("...")
}
```

# Third Party Libraries

```
cocoapods.org

package dependency manager

Interface for ruby gems is a command line tool called gem which can install & manage libraries

Cocoapods manages library dependencies for xcode projects. Dependencies for project are specified in a single text file called a podfile

required ios version of a dependency can be checked at .podspecfile

following statements will be present at such files:
ios,'10.0'
```

# pod commands

```
pod init
pod install
pod update
sudo arch -86_64x gem install fi
arch -86_64x pod install
when a line of code which defines a package is removed from podfile , close the xcode , execute pod install and reopen it
```


# Package Manager Options

```
Cocoapods , carthage and swift package manager.

as of now very few supports swift package manager

file -> swift packages -> add package dependency -> select project -> github url

.podspec file -> cocoapods 
Package.Swift -> SPM
```

# Firebase Configuration

```
add project ->
request ios app bundle app id->
download GoogleService-Info.plist configuration file
Update AppDelegate.swift

pod 'Firebase/Auth'
pod 'Firebase/Firestore'
pod install
```

# Global Constants

```
struct K {
  static let a = "A"
  static A {
    static let b = "B"
  }
}
```

# UITableView

```
func tableView(.... numOfRowsInSelection

func tableView(.... cellForRowAtIndexPath

func tableView(.... didSelectRowAtIndexPath
```

# Custom TableViewCell

```
Views -> New Cocoa Touch Class -> Message Cell (Subclass of UITableViewCell)
check allow create xib file
``` 

# hackiftakhar/IQKeyboardManager

```
File ->Swift Packages -> Add Package Dependency
Edit AppDelegate.swiift
TableViewCell xib file -> interactions -> disable
```

# ViewControllerLifeCycle

```
viewDidLoad()
viewWillAppear()
viewDidAppear()
viewWillUnappear()
viewDidDisappear()
```

# App Life Cycle Methods

```
Upto ios 12 , all life cycle methods used to be at AppDelegate.swift but as of ios13 , especially ipadOS there may be multiple instances of the app. If one of the window goes in background then scene delegate gets notified.
It treats each window as a separate screen.

N/W changes are handled by sceneDelegate.swift

Mutiple view controllers in one screne, multiple scenes in a app. -> SceneDelegate
func sceneWillResignActive( sceneDidEnterBackground(
```
