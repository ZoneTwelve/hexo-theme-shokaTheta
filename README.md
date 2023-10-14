# 📣 公告
* [ShokaTheta 正在尋找社群維護者](https://github.com/ZoneTwelve/hexo-theme-shokaTheta/discussions/1)

# hexo-theme-shokaX
![LICENSE](https://img.shields.io/github/license/ZoneTwelve/hexo-theme-shokaTheta)
![stars](https://img.shields.io/github/stars/ZoneTwelve/hexo-theme-shokaTheta)
<!-- ![version](https://shields.io/npm/v/hexo-theme-shokax) -->
![build](https://img.shields.io/github/actions/workflow/status/ZoneTwelve/hexo-theme-shokaTheta/build-theme.yml)

語言(language): 繁體中文 | [English](./README_en.MD) \
此項目是 ShokaTheta，一個基於 ShokaX 的專案進行調整的專案，致力於保障使用者隱私以及保留高性能的最佳化體驗\
誕生的原因就是 Shoka 包含一些不太符合本人社群精神的系統更動。

shokaTheta 的社群資源導向與插件儲存庫為 [awesome-shokaTheta](https://github.com/ZoneTwelve/awesome-shokaTheta)

## 💬 和shoka、shokaX的差別
基於原作者所述 shoka 使用了 JavaScript + native + nunjucks 的技術\
而 shokaX 使用的是 TypeScript + Vue 3 + Pug 的技術搭配\
更改了大量難以存取的 CDN 連結
而 shokaTheta 會基於 shokaX 進行大量的修改，以保障使用者隱私以及更高效的服務架構

## ✨ 功能清單

|   功能名稱   | 實現狀態 |     功能名稱     | 實現狀態 |
|:--------:|:----:|:------------:|:----:|
|  PWA支援   |  ✅   |    JSD拆分     |  ✅   |
|  API 注入   |  ✅   |    社群插件系統    |  ✅   |
|  自定義字體   |  ✅*  |    自定義樣式     |  ✅*  |
| 多種評論系統支援 |  ✅   |   AI生成文章大綱   |  🔬  |
|  底部備案號   |  ✅   |    自定義頁尾     |  ✅*  |
| CSS漸變封面  |  ✅   | TypeScript 支援 |  ✅   |

備註:
- *: 需要使用 API 注入才能實現
- 🔬: 實驗中，可能存在問題


## 🔧 如何安裝?
注意: 本項目需要 Node.js 18.x 或者更高版本才能執行 \
目前暫不支援 ShokaTheta-CLI，暫時保留 shokaTheta 的未來說明文件

```bash
npm i shoka-theta --location=global
# hexo init 初始化環境
SXC install shokaTheta
```
[點此](#NotReady)已進行下一步設定

## 📚子項目
- 暫無

## 🛠️二次開發
暫無

參與開發建議閱讀文件:
- [Hexo 官方文件](https://hexo.io/zh-cn/docs/templates)
- [Stylus 中文网](http://stylus.bootcss.com/)
- [Pug 模板引擎中文文档](https://www.pugjs.cn/api/getting-started.html)
- [Typescript 中文网](https://www.tslang.cn/docs/home.html)
- [Easy hexo](https://easyhexo.com/)

# 許可證 License
許可證: AGPL 3 or later

## 特別說明
AGPL許可證主要目的是限制修改後的分發行為，避免未經許可的二次修改封面商業行為 \
僅修改原始程式碼**需要**開源，基於 AGPL 許可，搭建網站需要開源修改部分

## 使用特殊說明
依照AGPLv3 Section 7，我們基於原項目的修改，盡量保留原始說明需求:
請查閱[使用限制](./UsageRestrictions.md)，使用 ShokaTheta 則默認您已經知道此文件內容

# 致謝名單
## 開源項目
| 名稱               | 作者               | 描述                  |
|:------------------|:------------------|:----------------------|
| Hexo              | Hexo contributors | 為本專案提供良好基礎      |
| hexo-theme-shoka  | amehime           | 本項目的父父主題         |
| hexo-theme-shokaX | theme-shoka-x     | 本項目的父主題           |

## 開發者們
<!-- [![](https://contributors-img.web.app/image?repo=theme-shoka-x/hexo-theme-shokaX)](https://github.com/ZoneTwelve/hexo-theme-shokaTheta/graphs/contributors) -->

## 特別感謝
[hexo-theme-shokaX](https://github.com/theme-shoka-x/hexo-theme-shokaX)

## 其他資訊
![Star history chart](https://api.star-history.com/svg?repos=ZoneTwelve/hexo-theme-shokaTheta&type=Date)