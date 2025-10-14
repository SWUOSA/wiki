# 仓库说明

每一讲单独放一个文件，文件命名规则为：系列/编号-名称-关键词.md。

系列目前为：cs-tutorials（CS入门）。请按照以下方式组织系列内容：

若“CS入门”系列的文章结构如下：

- 简介
    - 搜索与知识获取
    - Linux基础知识
- 网络安全
    - 搜索引擎陷阱
    - 什么是代理

则其对应的文件组织结构为：

```
cs-tutorials/
│
├── README.md          # 各系列文件夹中的 README.md 文件作为该系列的主页，导航栏中对应系列的入口会指向该 README.md。
├── 01-introduction.md
├── 01-introduction-search.md
├── 01-introduction-linux.md
├── 02-network-security.md
├── 02-network-security-search.md
└── 02-network-security-proxy.md
```

如需使用图片，请统一存放在 assets 目录下，对应路径示例如：`assets/cs-tutorials/01-introduction/a.png` 或
`assets/cs-tutorials/01-introduction-search/a.png`。

新增内容应该开分支，上传，开 PR，Review 后合并。

创建新页面时，请以 [template.md](/template.md) 为模板进行复制，并根据实际情况修改或替换其中的内容。

# 版权说明

本网页基于 [**Docsify**](https://docsify.js.org) 构建，网页源代码采用 MIT License 协议，各章节讲义内容默认遵循 CC BY-NC-SA 4.0 协议。部分章节的许可信息有所不同，具体请参见各章节讲义中的说明。