# openwrt-package

## 使用方法

1. 拉取lede代码

   ```bash
   git clone https://github.com/coolsnowwolf/lede.git
   cd lede
   ```

2. 编辑`feeds.conf.default`文件，追加写入

   ```bash
   src-git lyc https://github.com/lyc0209/openwrt-package
   ```

3. 更新

   ```bash
   ./scripts/feeds clean
   ./scripts/feeds update -a
   ./scripts/feeds install -a
   ```

   