# Awesome ChatGPT 中文版

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![English badge](https://img.shields.io/badge/%E8%8B%B1%E6%96%87-English-blue)](./README.md) [![中文版 badge](https://img.shields.io/badge/%E4%B8%AD%E6%96%87-Traditional%20Chinese-blue)](./README-zh-TW.md)

> ChatGPT 相關的優質資源、工具、應用的精選清單。

> English version can be found here：[English version](./README.md)

> **Warning**
>
> 請注意目前下列所有資源都是 **「非官方」** 的（除了「[官方資源](#官方資源)」區塊）。
>
> 使用時請特別小心。

## 目錄

- [官方資源](#官方資源)
- [在任何地方使用 ChatGPT](#在任何地方使用-chatgpt)
    - [瀏覽器擴充套件](#瀏覽器擴充套件)
    - [桌面應用程式](#桌面應用程式)
    - [編輯器](#編輯器)
    - [啟動器（Launcher）擴充套件](#啟動器launcher擴充套件)
    - [聊天機器人](#聊天機器人)
    - [反向代理網站（Reverse Proxy）](#反向代理網站reverse-proxy)
- [擴展 ChatGPT 功能](#擴展-chatgpt-功能)
- [延伸應用](#延伸應用)
- [提示詞（Prompts）](#提示詞prompts)
- [開發工具（API、SDK）](#開發工具apisdk)
- [實驗](#實驗)
- [貢獻](#貢獻)

---

## 官方資源

- [ChatGPT 官方網站](https://chat.openai.com/)
- [ChatGPT 發佈部落格文章](https://openai.com/blog/chatgpt/)

## 在任何地方使用 ChatGPT

### 瀏覽器擴充套件

- [ChatGPT for Google](https://chrome.google.com/webstore/detail/chatgpt-for-google/jgjaeacdkonaoafenlfkkkmbaopkbilf)：Chrome/Edge/Firefox 瀏覽器擴充套件，在 Google 搜索結果旁並列 ChatGPT 回應。（[Firefox擴充套件](https://addons.mozilla.org/en-US/firefox/addon/chatgpt-for-google/)、[程式碼](https://github.com/wong2/chat-gpt-google-extension)）
- [ChatGPT Extension](https://chrome.google.com/webstore/detail/chatgpt-chrome-extension/cdjifpfganmhoojfclednjdnnpooaojb)：Chrome 瀏覽器擴充套件，在右上角彈窗快速使用 ChatGPT。（[程式碼](https://github.com/kazuki-sf/ChatGPT_Extension)）
- [ChatGPT Everywhere](https://github.com/gragland/chatgpt-everywhere)：Chrome 瀏覽器擴充套件，在任何輸入框使用 ChatGPT。（[demo](https://twitter.com/gabe_ragland/status/1599466486422470656)）

### 桌面應用程式

- [ChatGPT Desktop App](https://github.com/sonnylazuardi/chatgpt-desktop)：Windows/MacOS 桌面選單列應用程式。使用 Tauri 和 Rust 開發。
- [chatgpt-mac](https://github.com/vincelwt/chatgpt-mac)：MacOS 選單列應用程式。

### 編輯器

- [ChatGPT for VSCode](https://github.com/mpociot/chatgpt-vscode)：VSCode 擴充套件。（[demo](https://twitter.com/marcelpociot/status/1599180144551526400)）
- [intellij-chatgpt](https://github.com/LiLittleCat/intellij-chatgpt)：JetBrains 編輯器擴充套件。
- [chatgpt.vim](https://github.com/terror/chatgpt.nvim)：Neovim 插件，在 Neovim buffer 裡使用 ChatGPT。
- [docGPT](https://github.com/cesarhuret/docGPT)：Google 文件編輯器插件，在 Google Docs 內使用 ChatGPT。

### 啟動器（Launcher）擴充套件

- [ChatGPT Raycast extension](https://github.com/abielzulio/chatgpt-raycast)：Raycast 擴充套件。

### 聊天機器人

- [Twitter/@ChatGPTBot](https://twitter.com/ChatGPTBot)：Twitter 推特機器人。（[程式碼](https://github.com/transitive-bullshit/chatgpt-twitter-bot)）
- [ChatGPT ProBot](https://github.com/oceanlvr/ChatGPTBot)：GitHub APP。輸入 `/chatgpt` 來與 ChatGPTBot 交談。
- [chatgpt-telegram](https://github.com/m1guelpf/chatgpt-telegram)：執行自己的 GPTChat Telegram 機器人，只需要一行指令。
- [ChatGPT Telegram Bot in AWS Lambda](https://github.com/franalgaba/chatgpt-telegram-bot-serverless): ChatGPT Telegram 機器人，執行在 AWS Lambda 上。支援語音訊息和 Markdown 顯示。
- [chatbot-telegram](https://github.com/Ciyou/chatbot-telegram): 一鍵运行 ChatGPT Telegram Bot，使用 `Deno` 和 `TypeScript` 打造。
- [chatGPT-discord-bot](https://github.com/Zero6992/chatGPT-discord-bot)：整合自己的 Discord 機器人。
- [wechat-chatgpt](https://github.com/fuergaosi233/wechat-chatgpt)：ChatGPT 的微信 Bot。裝完依賴後只需要填寫 OpenAI 帳號密碼和微信掃碼就可以使用。
- [ChatGPT LINE Bot](https://github.com/isdaviddong/chatGPTLineBot)（中文內容）：建立自己的 ChatGPT LINE 機器人。
- [gpt-ai-assistant](https://github.com/memochou1993/gpt-ai-assistant)（中文內容）：在 10 分鐘內打造自己的 GPT LINE 機器人。
- [chatgpt-for-chatbot-feishu](https://github.com/go-zoox/chatgpt-for-chatbot-feishu)：快速將 ChatGPT 接入飛書的應用，基於 OpenAI 官方接口 GPT3 模型，支持私有部署，作為私人工作助理或者企業員工助理。

### 反向代理網站（Reverse Proxy）

- [gpt.chatapi.art](https://gpt.chatapi.art/)：ChatGPT 反向代理網站，在被 OpenAI 限制權限的區域也能使用 ChatGPT，無須登入帳號。

## 擴展 ChatGPT 功能

- [ShareGPT](https://sharegpt.com/): 輕鬆分享 ChatGPT 對話紀錄。（[demo](https://twitter.com/steventey/status/1599816553490366464)）
- [ChatGPT export to PNG/PDF/HTML](https://github.com/liady/ChatGPT-pdf)：Chrome 瀏覽器擴充套件，能將 ChatGPT 紀錄下載成 PNG、PDF 檔，或產生可分享的連結。
- [ChatGPT Advanced](https://github.com/qunash/chatgpt-advanced): Chrome 瀏覽器擴充套件，在 ChatGPT 頁面同時顯示網頁搜尋結果。
- [TampermonkeyUserscripts/ChatGPTVoiceInput](https://github.com/doggy8088/TampermonkeyUserscripts/blob/main/src/ChatGPTVoiceInput.user.js?fbclid=IwAR2sYE_CIOTdhNlRqaYwJ3eh-foa4O7ZHukYcc1dXLcU8IHLIDOt52gdAdQ)（中文內容）: Tampermonkey 腳本，ChatGPT 語音輸入介面（支援中/英/日/韓語言）。

## 延伸應用

- [summarize.site](https://chrome.google.com/webstore/detail/summarize/lmhkmibdclhibdooglianggbnhcbcjeh)：Chrome 瀏覽器擴充套件，總結網頁內容、給出摘要。
- [commitgpt](https://github.com/RomanHotsiy/commitgpt)：自動產生 commit 訊息。
- [chatgpt-action](https://github.com/kxxt/chatgpt-action): Github Action，讓 ChatGPT review 你的 PR。
- [StackExplain](https://github.com/shobrook/stackexplain): 讓 ChatGPT 解釋錯誤訊息的命令列工具。

## 提示詞（Prompts）

- [showGPT](https://showgpt.co/): 蒐集優質提示詞的網站，你也可以輕鬆上傳更多提示詞。
- [awesome-chatgpt](https://github.com/saharmor/awesome-chatgpt): 各種 ChatGPT 提示詞用法的文章和想法。
- [Awesome ChatGPT Prompts](https://github.com/f/awesome-chatgpt-prompts): ChatGPT 提示詞清單。

## 開發工具（API、SDK）

- [PyChatGPT](https://github.com/rawandahmad698/PyChatGPT)（Python）：輕量化、基於 TLS 的 ChatGPT API 可以在您的 CLI 中使用，無需使用瀏覽器或驗證金鑰。
- [pip/revChatGPT](https://github.com/acheong08/ChatGPT)（Python）：與 OpenAI 的 ChatGPT API 互動的輕量化套件。採用逆向工程手法。
- [npm/chatgpt](https://github.com/transitive-bullshit/chatgpt-api)（Node.js）：Node.js 客戶端。
- [ChatGPT API Dart](https://github.com/MisterJimson/chatgpt_api_dart) (Dart): Dart 客戶端。
- [go-chatgpt](https://github.com/abhayptp/go-chatgpt) (Golang): Golang 客戶端。

## 實驗

- [gptlang](https://github.com/forrestchang/gptlang): 驗證是否能利用 ChatGPT 建立一個程式語言的實驗。

---

## 貢獻

如果你創造或找到任何優質的 ChatGPT 相關資源，歡迎開 issue 或 PR 來完善這份列表！
