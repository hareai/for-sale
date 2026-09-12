# for-sale

域名出售静态页。

[English](README.md)

## 快速开始

```bash
git clone https://github.com/hareai/for-sale.git
cd for-sale
python3 -m http.server 8080 --directory site
```

打开 `http://127.0.0.1:8080`。标题是打开这个页面时用的主机名。

## 用法

把域名指到本仓库的 Cloudflare Pages 项目。页面会显示该主机名，联系邮箱是 [domains@lifeng.net](mailto:domains@lifeng.net)。

要改联系邮箱，编辑 `site/index.html`。

## 许可证

[MIT](LICENSE)
