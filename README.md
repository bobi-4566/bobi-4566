<div align="center">

# Hi 👋，我是 **bobi-4566**

**Python 爬虫 · 数据挖掘 · 金融数据自动化**

[![Profile Views](https://img.shields.io/github/profile/views?username=bobi-4566&label=Profile%20Views&color=007ec6)](https://github.com/bobi-4566)
[![Followers](https://img.shields.io/github/followers/bobi-4566?label=Followers&style=social)](https://github.com/bobi-4566?tab=followers)
[![Repos](https://img.shields.io/github/repos/bobi-4566?label=Repos&style=social)](https://github.com/bobi-4566?tab=repositories)

</div>

---

## 🧠 关于

做金融投研数据自动化的散户开发者，常年折腾这些事：

- 把散落的数据源变成可复用的采集脚本
- 把「盯盘」变成自动化任务，机器替人做重复劳动
- 用规则和模型代替情绪做决策

日常环境：**Windows 11 + Python 3.12**，所有工具链围绕本地可复现构建。

## 🛠 技术栈

| 方向 | 技术 |
|---|---|
| **爬虫** | requests · BeautifulSoup · lxml · aiohttp · selenium · DrissionPage |
| **并发** | asyncio · 多线程 · 多进程 · concurrent.futures |
| **数据** | pandas · numpy · akshare · tushare · SQLite |
| **分析** | scikit-learn · statsmodels · matplotlib · seaborn |
| **加解密** | SQLCipher4 · pycryptodome · HMAC-SHA512 密钥校验 |
| **自动化** | Windows 任务计划 · GitHub Actions · 邮件 / 飞书推送 |

## 📌 项目

| 仓库 | 简介 | 亮点 |
|---|---|---|
| [`bigdata`](https://github.com/bobi-4566/bigdata) | 42 个爬虫与数据分析脚本，按 7 大主题归档 | 从 HTTP 基础到量化分析的完整路径 |
| [`wechat-decrypt`](https://github.com/bobi-4566/wechat-decrypt) | 微信 4.x 本地数据库解密与实时消息监听 | 内置 MCP Server，可直接被 AI 查询 |
| [`wechat-mail-notifier`](https://github.com/bobi-4566/wechat-mail-notifier) | 微信新消息邮件提醒 | SQLCipher4 解密 + 未读数比对，零误报 |

## 💡 一些心得

> **加密数据要靠「钢印」验证，不要靠猜。**
> 判断一个密钥对不对，唯一可靠的方式是拿数据库首页的 HMAC 去验算——长度相同、格式相同的东西多了去了，能对上才算数。

> **抓下来的东西要能被验证，也要能被丢弃。**
> 采集脚本和它的产物应该分开管理，`.gitignore` 写清楚，仓库才不会被几十 MB 的临时文件淹没。

> **能只读，就绝不去写。**
> 涉及他人进程的操作，一律走只读路径，不注入、不 hook。

## 📈 GitHub

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=bobi-4566&show_icons=true&hide_border=true&include_all_commits=true&count_private=true" alt="GitHub Stats" />
</div>

## 📫 交流

欢迎通过 [GitHub Issues](https://github.com/bobi-4566/bobi-4566/issues) 提问或讨论。
遇到 bug 也很欢迎直接开 issue，我会尽量回复。

---

<div align="center">
  <sub>用 ❤️ 和 ☕ 支撑这些折腾 · 最后更新于 2026</sub>
</div>
