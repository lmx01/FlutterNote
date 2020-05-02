# 1.1 命名.md

1. UpperCamelCase
  - 类，枚举，typedef和类型参数应将每个单词的首字母大写（包括第一个单词），并且不使用分隔符.

  ```dart
  class SliderMenu { ... }

  class HttpRequest { ... }

  typedef Predicate<T> = bool Function(T value);
  ```

2. lowercase_with_underscores
  - 文件命名：一些文件系统不区分大小写，因此许多项目要求文件名全部为小写. 使用分隔符可以使名称仍以该形式可读. 
  - 模块导入命名：
  ```dart
  import 'package:angular_components/angular_components'
    as angular_components;
  ```

3. lowerCamelCase
  - 类成员，顶级定义，变量，参数和命名参数
  - 常量变量、枚举值

  ```dart
  const pi = 3.14;
  const defaultTimeout = 1000;
  final urlScheme = RegExp('^([a-z]+):');

  class Dice {
    static final numberGenerator = Random();
  }
  ```

4. 下划线"_"只能用于成员变量，表示为“私有”变量

5. 变量前不要加类型命名

  ```dart
  defaultTimeout  //Error: kDefaultTimeout
  ```