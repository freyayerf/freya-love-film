# FREYA LOVE FILM

用自己的剧照制作电影票根。可以调整构图、编辑票根文字、自动取色或手动选色，并批量导出 300 DPI PNG 和多页 PDF。

[在线使用](https://freyayerf.github.io/freya-love-film/) · [下载单文件离线版](../../releases/latest/download/index.html) · [查看源代码](index.html)

## 使用

打开在线版，或下载 `index.html` 后用浏览器打开。HTML 内含全部代码和一张示例剧照，可以离线运行。

- 在编辑器里添加票根、上传剧照和填写电影信息。拖动预览中的剧照或使用滑杆来调整构图。
- 用「保存项目」下载包含图片和编辑内容的项目文件，之后点「打开项目」继续编辑。浏览器也会在当前地址自动保存草稿，换地址或换设备时可以用项目文件迁移。
- 导出成品的裁切尺寸为 70 × 150 mm，四周各留 2 mm 白边。打印 PDF 时选 100% 或实际大小。

## 发布自己的版本

1. Fork 此仓库，在 **Settings → Pages → Build and deployment → Source** 选择 **GitHub Actions**。
2. 把修改推送到 `main`，或在 **Actions → Deploy to GitHub Pages → Run workflow** 手动发布。
3. 工作流会检查内联 JavaScript 的语法，并把 `index.html` 发布到 Pages。发布链接可在 **Settings → Pages** 查看。单文件也可以放到其他静态网站托管服务。

项目文件和上传的剧照存放在你使用的浏览器或你下载的项目文件里。发布工作流只上传网站的 `index.html`。

## English

FREYA LOVE FILM is a browser-based movie ticket maker. Download and open `index.html` to use it offline. Save and reopen projects as JSON, and export tickets as print-ready PNGs or a multi-page PDF. To host a copy, fork the repository, set the Pages source to GitHub Actions, then push to `main` or run the Pages workflow manually.

## License

[MIT](LICENSE)
