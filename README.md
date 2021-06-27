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
