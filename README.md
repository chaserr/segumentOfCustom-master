# segumentOfCustom-master
自定义segument控件

--------
怎么使用它

```
- (LXDSegmentControl *)segmentControl
{
    LXDSegmentControlConfiguration * configuration = [LXDSegmentControlConfiguration configurationWithItems: @[@"a", @"b", @"c", @"d"]];
    configuration.itemSelectedTextColor = configuration.slideBlockColor = [UIColor colorWithRed: 74/255. green: 200/255. blue: 250/255. alpha: 1.];
    configuration.backgroundColor = [UIColor groupTableViewBackgroundColor];
    LXDSegmentControl * segmentControl = [LXDSegmentControl segmentControlWithFrame: CGRectMake(0, 0, [UIScreen mainScreen].bounds.size.width, 45) configuration: configuration delegate: nil];
    return segmentControl;
}
```

