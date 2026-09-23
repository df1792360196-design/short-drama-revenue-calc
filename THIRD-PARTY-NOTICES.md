# 第三方组件声明

本项目的 `index.html` / `短剧收益核算工具.html` 内联了以下第三方库，以便工具能够完全离线运行。

## SheetJS (xlsx)

- 版本：0.18.5
- 主页：https://sheetjs.com/
- 仓库：https://github.com/SheetJS/sheetjs
- 许可证：**Apache License 2.0**
- 用途：在浏览器内解析 `.xlsx / .xlsm / .xls / .csv`，以及导出 `.xlsx` 结果文件
- 引入方式：以压缩后的 `dist/xlsx.full.min.js` 完整内联进 HTML 的 `<script>` 标签，未做修改

根据 Apache-2.0 第 4 条要求，此处保留其版权与许可声明。完整的 Apache License 2.0 文本可参见：
https://www.apache.org/licenses/LICENSE-2.0

该库源码中的版权声明为：

```
/*! xlsx.js (C) 2013-present SheetJS -- http://sheetjs.com */
```

## 其他

除 SheetJS 外，本项目不包含其他第三方代码，运行时不加载任何外部资源（无 CDN、无字体、无网络请求）。
