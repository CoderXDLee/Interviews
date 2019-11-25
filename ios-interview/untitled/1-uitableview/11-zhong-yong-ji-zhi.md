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

众所周知，以上两段代码实际上就使用了 `UITableView` 的重用机制。

