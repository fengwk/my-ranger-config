# My Ranger Config

个人ranger配置。

# Installation

ranger

```
yay -S ranger
git clone git@github.com:fengwk/my-ranger-config.git ~/.config/ranger
```

特性

- 图标
- 图片预览：`yay -S ueberzugpp`
- 视频缩略图预览：`yay -S ffmpegthumbnailer`
- 代码高亮：`yay -S highlight`
- 压缩包预览：`yay -S atool`
- PDF预览：`yay -S poppler`
- 使用`ctrl+f`进行fzf搜索：`yay -S fzf fd`
- 拖拽`curl+d`：`yay -S dragon-drop`
- udisk menu：`yay -S udisk2`

ubuntu

```
apt install ffmpegthumbnailer highlight atool poppler-utils fzf fd-find udisks2
```

- ueberzugpp-new https://github.com/jstkdng/ueberzugpp-new
- dragon https://github.com/mwh/dragon

macos

- brew install jstkdng/programs/ueberzugpp
- dragon-drop 使用`https://github.com/ciaran/drag.git`
    - 编译方法: `cd dragterm && clang -o dragterm main.m DTDraggingSourceView.m -framework Foundation -framework AppKit`
    - 编译完成后将编译生成的`dragterm`放在可执行位置
    - 将适配器脚本脚本也放到可执行位置`ln -s ~/scripts/dragon-drop-mac /usr/local/bin/dragon-drop`
- udisk2 暂无替代方案

# Reference

- [ranger配置和使用](https://www.zssnp.top/2021/06/03/ranger/)
- [ranger的配置与使用](https://zhuanlan.zhihu.com/p/105731111)
