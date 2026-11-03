# Content Hive Plugin: 小红书

适用于 Content Hive 的小红书内容解析插件，通过抓取笔记页面并提取嵌入的页面状态来获取内容。

Plugin for [Content Hive](https://github.com/content-hive/content-hive).

## Layout

```
plugin/              # plugin source, installed as plugins/xiaohongshu/ by Content Hive
├── manifest.json    # plugin metadata (domain, version, requirements, release_notes)
├── __init__.py
└── ...
contenthive.json     # repository metadata for the Content Hive plugin catalog
```

## Disclaimer

> 本插件通过抓取小红书网页获取内容，使用前请确保符合小红书服务条款及当地法律法规。平台规则变更可能导致插件失效。
