<h1 align="center">heroku-22-buildpack-wkhtmltopdf</h3>

<div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---

##  About <a name = "about"></a>

Fork of https://github.com/RohanDebroy/heroku-buildpack-wkhtmltopdf to work with heroku-26, heroku-24, heroku-22 and heroku-20 stacks

## Stack Compatibility

The buildpack chooses a prebuilt wkhtmltopdf package based on the Heroku stack:

| Heroku stack | wkhtmltopdf package | Upstream release |
| --- | --- | --- |
| heroku-20 | `wkhtmltox_0.12.6-1.focal_amd64.deb` | 0.12.6-1 |
| heroku-22 | `wkhtmltox_0.12.6.1-2.jammy_amd64.deb` | 0.12.6.1-2 |
| heroku-24 | `wkhtmltox_0.12.6.1-2.jammy_amd64.deb` | 0.12.6.1-2 |
| heroku-26 | `wkhtmltox_0.12.6.1-3.jammy_amd64.deb` | 0.12.6.1-3 |

## License <a name="license"></a>
MIT
