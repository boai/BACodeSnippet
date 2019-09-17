# BACodeSnippet
Xcode  CodeSnippet 汇总

*BACodeSnippet* 是一个 BAHome 团队日常工作中整理出来的用于 Xcode 的 iOS 通用代码片段集。

## 使用方式

Xcode 的 Code Snippets 文件存放于 `~/Library/Developer/Xcode/UserData/CodeSnippets` 目录，只要直接把 `*.codesnippets` 文件放到这个目录下（若没有则自己创建），重启 Xcode 即可生效。

为了方便更新，建议直接将  BACodeSnippet clone 到这个目录内（注意，不是在 CodeSnippets 里创建一个 BACodeSnippet 的目录，这里不支持子目录）：

```
cd ~/Library/Developer/Xcode/UserData/CodeSnippets
git clone https://github.com/boai/BACodeSnippet.git ./
```

其中以 `ba_` 前缀开头的文件是通用的 Code Snippets，以 `ba_` 前缀开头的文件是专用于 ` iOS` 框架的代码片段。在下方的快捷键汇总里，

```
cd ~/Library/Developer/Xcode/UserData/CodeSnippets
git clone https://github.com/boai/BACodeSnippet.git ./
```

注意，Xcode 对每一段 Code Snippet 都有规定适用的语言（Objective-C、Objective-C++、Swift、...）和作用域（如 Class 的 Interface 定义内、Class 的 Implementation 内、方法体内、...），所以测试某段 Code Snippet 不生效时请注意你当前是否处于不匹配的位置。

## 快捷键汇总

##### 2019-09-17 

- `ba_init_tableView` - 快速创建 UITableView 

##### 2019-09-16 

- `ba_init_cell` - 快速创建 自定义 UITableViewCell 的 init 方法

* `ba_ios11_bottom` - 快速创建 ios 11 bottom 布局适配
* `ba_lazy` - 快速创建 一个懒加载
* `ba_min` - 快速创建 frame 需要的 x、y、width、height
* `ba_view_init` - 快速创建 自定义 view 所需的 init 代码
* `ba_view_initData` - 快速创建 自定义 view 所需的 initData 代码
* `ba_wea` - 快速创建 weak（需要 依赖库：`ReactiveObjC`）
* `ba_str` - 快速创建 strong（需要 依赖库：`ReactiveObjC`）