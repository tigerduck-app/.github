<div align="center">
  <a href="https://tigerduck.app/">
    <img width="2000" src="https://github.com/user-attachments/assets/cf6a1d18-a348-4b83-adfd-81c6dc82855f" />
  </a>
<br>

[![Website](https://img.shields.io/badge/Website-tigerduck.app-00BB00?style=for-the-badge)](https://tigerduck.app/)
[![iOS TestFlight](https://img.shields.io/badge/iOS-TestFlight-0D96F6?style=for-the-badge&logo=apple&logoColor=white)](https://testflight.apple.com/join/eVt9Gjkw)
[![Android](https://img.shields.io/badge/Google_Play-Play-414141?style=for-the-badge&logo=googleplay&logoColor=white)](https://play.google.com/store/apps/details?id=org.ntust.app.tigerduck)
[![License](https://img.shields.io/badge/License-AGPL--3.0-blue?style=for-the-badge)](https://www.gnu.org/licenses/agpl-3.0)

</div>

## 我們是誰

TigerDuck 是一群臺灣科技大學學生共同開發的校園助手  
為了解決校內資源零散、通知不及時、介面不直觀等痛點，我們把各項資源整合在同一個原生體驗中！

> 有用過 [TAT](https://github.com/morris13579/tat_ntust) 嗎？我們希望讓你 **OAO**。

## 取得 App

| 平台 | 狀態 | 連結 |
|:---:|:---:|:---:|
| **iOS** | 公測中 | [![TestFlight](https://img.shields.io/badge/Join-TestFlight-0D96F6?style=flat-square&logo=apple&logoColor=white)](https://testflight.apple.com/join/eVt9Gjkw) |
| **Android** | Google Play & F-Droid 已上架 | [![Google Play](https://img.shields.io/badge/Get_it_on-Google_Play-414141?style=flat-square&logo=googleplay&logoColor=white)](https://play.google.com/store/apps/details?id=org.ntust.app.tigerduck) [![F-Droid](https://img.shields.io/badge/Get_it_on-F--Droid-1976D2?style=flat-square&logo=fdroid&logoColor=white)](https://f-droid.org/packages/org.ntust.app.tigerduck.fdroid/) |
| **Web** | 官方網站 | [tigerduck.app](https://tigerduck.app/) |

## 主要功能

- 📚 **作業** — 自動同步 Moodle 作業與截止日期，動態島 / 推播提醒
- 📋 **課表** — 從選課系統同步，今日課程顯示在動態島與時光機軸
- 📣 **公告** — 後端 LLM 自動分類、去重、可訂閱類別
- 📊 **歷年成績** — GPA / 排名 / 各科成績與互動式圖表
- 🏛️ **圖書館** — 秒開入館 QR-Code
- 🌏 **多語言** — 內建 67+ 種語系、課程 / 教室名稱自動簡寫
- 🎨 **客製化** — 拖放排序、編輯 Tab、選擇主題色

## 專案組成

| Repo | 內容 | 技術棧 |
|---|---|---|
| [`tigerduck-app`](https://github.com/tigerduck-app/tigerduck-app) | iOS App 主專案 | Swift 5 · SwiftUI |
| [`tigerduck-app-android`](https://github.com/tigerduck-app/tigerduck-app-android) | Android App | Kotlin 2.3 · Jetpack Compose · Material 3 · Hilt · Room |
| [`tigerduck-web`](https://github.com/tigerduck-app/tigerduck-web) | 官方網站 | Vite + React · Cloudflare Workers |
| [`app-translation`](https://github.com/tigerduck-app/app-translation) | 67+ 語系翻譯 | JSON · 自動產生 `.strings` / `strings.xml` |
| [`name-abbr`](https://github.com/tigerduck-app/name-abbr) | 課程 / 教室名稱簡寫字典 | JSON |

## 貢獻

歡迎 PR、Issue、翻譯、回報 Bug。

- **新功能 / Bug 修復** — 到對應 repo 開 Issue 或 PR，目標分支為 `dev`
- **翻譯** — 改 [`app-translation`](https://github.com/tigerduck-app/app-translation)，不要直接改 App 內的 `.lproj` / `strings.xml`
- **課程 / 教室簡稱** — 改 [`name-abbr`](https://github.com/tigerduck-app/name-abbr)
- 分支命名請使用 `feature/your-feature` 或 `fix/your-fix`

## 聯絡與資源

- 🌐 官方網站：<https://tigerduck.app/>
- ✉️ 聯絡信箱：<tigerduckapp@gmail.com>
- 📍 Taiwan · NTUST

## 授權

所有專案皆採用 [GNU Affero General Public License v3.0](https://www.gnu.org/licenses/agpl-3.0)。
