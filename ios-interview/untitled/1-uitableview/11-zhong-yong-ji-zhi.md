# 1-1 重用机制

```objectivec
// Objective - C
NSString *identifier = @"cell";
UITableViewCell *cell = [self.tableView dequeueReusableCellWithIdentifier: identifier];
```

```swift
// Swift
let identifier = "cell"
tableView.dequeueReusableCell(withIdentifier: identifier)
```



