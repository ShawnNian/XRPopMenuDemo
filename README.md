# XRPopMenuDemo V1.0
带动画效果的简易弹出菜单demo, 多按钮自适应
A pop menu with aniamtion

# Usage
(1). import XRPopMenuView.h

(2). Init the menu

``` 
    XRPopMenuView *menuView = [[XRPopMenuView alloc] init];
``` 

(3). Add buttons
``` 
    [menuView addMenuItemWithTitle:@"创建标签" andIcon:[UIImage imageNamed:@"editButton"] andSelectedBlock:^{
        NSLog(@"创建标签 selected");
    }];
    [menuView addMenuItemWithTitle:@"添加标签" andIcon:[UIImage imageNamed:@"markButton"] andSelectedBlock:^{
        NSLog(@"添加标签 selected");
    }];
``` 

(4). Show the menu
``` 
    [menuView show];
``` 
# License
本项目采用 MIT license 开源，你可以利用采用该协议的代码做任何事情，只需要继续继承 MIT 协议即可。
