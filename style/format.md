# 1.3 格式化.md

1. 工具：dartfmt
2. 每行不超过80个字符
3. if语句除非能在一行写完，否则，一定要用大括号，加换行

```dart
// good
if (overflowChars != other.overflowChars) {
  return overflowChars < other.overflowChars;
}

// bad
if (overflowChars != other.overflowChars)
  return overflowChars < other.overflowChars;

// ok
if (arg == null) return defaultValue;

```