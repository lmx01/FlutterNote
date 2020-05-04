# 1.2 代码布局.md

文件的代码布局

```dart
/*
 * 第一片段：import，每一个片段间要用一行空行风格
 * 相同字段按照字母顺序排序
 */
// 1. "dart:" imports
import 'dart:aync';

// 2. "package:" imports,自己的包放最后
import 'package:bar/bar.dart';

// 3. relative imports
import 'util.dart'

/*
 * 第二片段：export
 */
export 'src/error.dart';


```