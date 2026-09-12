# for-sale

A static page that says a domain is for sale.

[简体中文](README.zh-CN.md)

## Quick start

```bash
git clone https://github.com/hareai/for-sale.git
cd for-sale
python3 -m http.server 8080 --directory site
```

Open `http://127.0.0.1:8080`. The heading is the hostname that served the page.

## Usage

Point a domain at the Cloudflare Pages project for this repo. The page shows that hostname and [domains@lifeng.net](mailto:domains@lifeng.net).

To change the contact address, edit `site/index.html`.

## License

[MIT](LICENSE)
