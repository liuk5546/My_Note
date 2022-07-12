# File Objects and Methods in Python

## pathlib
1. 如果你想要操作Windows路径子在一个Unix机器上，或者Unix路径在Windows机器上，你不能直接使用`WindowsPath/PosixPath`，但是你可以直接使用`PureWindowsPath/PurePosixPath`。 
2. 不用通过操作系统操作路径

## 对于文件的操作`open()`
open函数有以下几个参数
1. file, 这是一个`path-like object`
2. mode 是一个可选的参数，默认是r（可读） w可写，x，a，b，t，+
返回一个相应的file object
