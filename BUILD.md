# mini_chromium

## How to build

仿照gn项目源码中的`simple_build`这个例子中的配置，将缺失的.gn等文件拷贝过来。

执行gn命令生成ninja文件，之后使用ningja进行构建。

```bash
gn gen -C out/
ninja -v
```
