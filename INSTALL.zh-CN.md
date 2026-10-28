# 安装 Read My Markdown 0.4.0

## 安装或手动升级

1. 下载并解压 `read-my-markdown-0.4.0.zip` 到长期保留的文件夹。
2. 在 Chrome 打开 `chrome://extensions/`，或在 Edge 打开 `edge://extensions/`。
3. 开启“开发者模式”，点击“加载已解压的扩展程序”（Edge 中为“加载解压缩的扩展”）。
4. 选择解压后直接包含 `manifest.json` 的目录。
5. 在扩展详情中开启“允许访问文件网址”，即可把本地 `.md` 文件直接拖入浏览器预览。

手动升级时，先关闭阅读器，再用新版文件替换原扩展目录中的文件，最后在扩展管理页点击“重新加载”。请保留原安装目录，不要先移除扩展或清除浏览器数据，以保留本地阅读记录和授权状态。

## 使用

点击扩展图标打开阅读器，然后选择或拖入 Markdown 文件 / 文件夹。拖入阅读器本身不需要开启文件网址权限。若浏览器在修改文件网址权限后关闭了阅读器，重新点击扩展图标即可。

## 校验下载文件

在 macOS 或 Linux 运行：

```bash
shasum -a 256 -c SHA256SUMS-0.4.0.txt
```

Windows PowerShell 可运行：

```powershell
Get-FileHash .\read-my-markdown-0.4.0.zip -Algorithm SHA256
```

核对结果应与 `SHA256SUMS-0.4.0.txt` 中的值一致。

## 隐私

文档在浏览器本地处理。隐私政策：<https://chaoslcc.github.io/read-my-markdown-privacy/>。
