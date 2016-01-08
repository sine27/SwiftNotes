# Swift Notes

### UIViewController

### UITableViewController

### NavigationController

##### hide Navigation bar

```Swift
override func viewWillAppear(animated: Bool) {
    super.viewDidDisappear(animated)
    self.navigationController?.navigationBarHidden = true
}
// show navigation bar in following ViewController
override func viewDidDisappear(animated: Bool) {
    super.viewDidDisappear(animated)
    self.navigationController?.navigationBarHidden = false
}

```

### TabBarController

### General

##### Hide status bar

```Swift
override func prefersStatusBarHidden() -> Bool {
    return true
}
```
