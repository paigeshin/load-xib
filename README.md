# load-xib

```swift
        let customView = UINib(nibName: "MyCustomView", bundle: nil).instantiate(withOwner: nil, options: nil)[0] as! MyCustomView
        
        customView.frame = CGRect(x: view.frame.midX - 100, y: view.frame.midY - 100, width: 200, height: 200)
        
        view.addSubview(customView)
```
