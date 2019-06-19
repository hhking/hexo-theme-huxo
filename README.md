# Hexo Theme Huxo
> 移植的主题 Hux Blog(V1.8), 感谢 Huxpro 设计这样一个完美的主题。同时也感谢 [Kaijun](https://github.com/Kaijun/hexo-theme-huxblog) 提供的参考。

### [Demo &rarr;](https://blog.hhking.cn/)

![](http://huangxuan.me/img/blog-desktop.jpg)

## Usage
```
npm install hexo-renderer-scss --save
git clone https://github.com/hhking/hexo-theme-huxo.git themes/huxo
```

修改配置文件中的 theme 字段为 huxo:

```
# Extensions
## Plugins: http://hexo.io/plugins/
## Themes: http://hexo.io/themes/
theme: huxo
```

直接修改主题 `_config.yml`, 或者在 `source` 目录下新建 `_data/huxo.yml` 来配置主题

详细配置可以参考我的博客配置：https://github.com/hhking/hhking.github.io/tree/hexo

## 做了一些微小的工作
- 重构了部分代码
- 修改百度和谷歌统计的配置，增加屏蔽 localhost 环境
- 增加 gitalk 支持
- 修改社交链接配置，更自由方便
- 增加 [不蒜子](https://busuanzi.ibruce.info/) 统计
- 增加文章版权声明 creativecommons
