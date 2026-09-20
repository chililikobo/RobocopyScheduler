# Robocopy Scheduler

[English](https://www.google.com/search?q=%2523english&utm_source=gemini) | [日本語](https://www.google.com/search?q=%2523%25E6%2597%25A5%25E6%259C%25AC%25E8%25AA%259E&utm_source=gemini)

---

## English

Robocopy Scheduler is an intuitive GUI frontend and scheduling management tool designed to automate and simplify Windows standard "Robocopy" command tasks. Without remembering complex command-line arguments, you can easily configure advanced file transfer settings and run automated background backups.

### Key Features

* **Intuitive GUI & Advanced Options**: Easily configure backup modes such as **Mirror (/MIR)**, **Safe Add (/E)**, or **Update (/E /XO)**, as well as multi-threading, SMB compression (`/COMPRESS`), and bypassing access denial (`/ZB`).
* **Flexible Automated Scheduling**: Supports Daily, Hourly, Weekly, Monthly, and advanced **Custom (Cron)** schedule expressions.
* **Sleep Prevention & System Tray Residency**: Blocks system sleep while waiting for schedules and supports background startup on Windows boot.
* **Log Management & CSV Export**: Displays execution history and error details in real-time with CSV export capability.
* **Multi-Channel Notifications**: Automatically sends backup results to **Slack Webhooks** or **ntfy.sh**.
* **Native AOT Compiled**: Built with .NET 10 (Native AOT) as a standalone portable application with no external runtime requirements.

### Quick Start

1. Extract the downloaded archive and place the entire folder in any directory, then run `RobocopyScheduler.exe` inside it.
2. Click **Add New** in the "Job Settings" tab to create a backup job, then select your Source and Destination folders.
3. Configure your desired backup mode, performance options, and schedule settings.
4. Check **Enable schedule for this job** and click **Save Job** (or click **Run Now** for manual execution).

### Editions & Licensing

* **Free Edition**: Fully free for personal environments and non-managed devices. In corporate environments, all features except scheduled automatic execution are available (manual execution only).
* **Pro Edition**: Unlocks all features, including automated scheduled execution, in corporate environments (e.g., domain-joined PCs or Entra ID environments).

### Terms & Disclaimer

* **License**: Provided as Free and Pro Editions. Secondary distribution is prohibited.
* **Data Privacy**: No external transmission of log data (excluding license validation and optional user-configured notifications via Slack/ntfy.sh).
* **Warranty**: Provided "As-Is". The author assumes no responsibility for any damages resulting from the use of this software.

### Credits (External Libraries)

* Avalonia UI Framework (MIT License)
* CommunityToolkit.Mvvm (MIT License)
* Cronos (MIT License)
* DynamicData (MIT License)
* QRCoder (MIT License)

### Links & Contact

* **Developer**: chilili kobo
* **Website**: [https://chililikobo.github.io/en/](https://www.google.com/search?q=https://chililikobo.github.io/en/&utm_source=gemini)
* **X (Twitter)**: [@chililikobo](https://www.google.com/search?q=https://x.com/chililikobo&utm_source=gemini)
* **Email**: chilili.kobo@gmail.com

---

## 日本語

Robocopy Scheduler（ロボコピー・スケジューラー）は、Windows標準の強力なファイルコピーコマンド「Robocopy」を直感的かつ手軽に操作・自動化するためのスケジュール管理＆GUIフロントエンドツールです。複雑なコマンドラインオプションを覚えることなく、完全同期やマルチスレッド転送などの高度な設定をGUI上で構成し、バックグラウンドでの自動バックアップを実現します。

### 主な機能

* **直感的GUI設定と多機能オプション**: **完全同期 (/MIR)**、**安全追加 (/E)**、**最新化 (/E /XO)** などのバックアップ方式をワンクリックで設定可能。マルチスレッド転送、SMB圧縮 (`/COMPRESS`)、アクセス権エラー回避 (`/ZB`) にも対応しています。
* **柔軟な自動スケジュール**: 毎日、毎時、毎週、毎月だけでなく、**カスタム (Cron式)** による高度なスケジュール設定が可能です。
* **スリープ防止＆タスクトレイ常駐**: スケジュール待機中のPC自動スリープをブロックする機能を搭載。Windows起動時のバックグラウンド自動起動にも対応しています。
* **ログ管理とCSVエクスポート**: 実行履歴やエラー詳細をリアルタイムで一覧表示し、CSV形式でファイル出力が可能です。
* **多重外部通知機能**: バックアップ実行結果を **Slack Webhook** や **ntfy.sh** へ自動送信できます。
* **Native AOT コンパイル**: .NET 10 (Native AOT) により単体動作し、.NETランタイムなどの追加インストールは不要です（ポータブル対応）。

### 使い方

1. ダウンロードしたアーカイブを展開し、フォルダごと任意の場所に配置して、その中の `RobocopyScheduler.exe` を起動します。
2. 「ジョブ設定」タブで「新規追加」をクリックし、コピー元フォルダとコピー先フォルダを指定します。
3. バックアップ方式、転送オプション、実行スケジュールを設定します。
4. 「このジョブのスケジュールを有効にする」にチェックを入れて「ジョブを保存」します（「今すぐ手動実行」による即時実行も可能です）。

### エディションとライセンス

* **Free版**: 個人環境や非管理デバイスでは、完全無料で全機能をご利用いただけます。企業環境でもFree版を利用可能ですが、スケジュール自動実行機能は制限されます（手動実行のみ対応）。
* **Pro版**: 企業環境（ドメイン参加PCやEntra ID環境など）において、スケジュール実行機能を含むすべての機能を利用するために必要です。

### 利用規約・免責事項

* **ライセンス**: Free Edition および Pro Edition として提供。二次配布は原則禁止します。
* **外部通信**: ユーザーが任意で設定した外部通知（Slack / ntfy.sh）およびライセンス認証通信を除き、ログ等の情報を無断送信することはありません。
* **免責事項**: 本ソフトウェアは「現状有姿（As-Is）」で提供され、使用により生じた一切の損害について作者は責任を負いません。

### 外部ライブラリ（クレジット）

* Avalonia UI Framework (MIT License)
* CommunityToolkit.Mvvm (MIT License)
* Cronos (MIT License)
* DynamicData (MIT License)
* QRCoder (MIT License)

### リンク・連絡先

* **制作者**: chilili kobo
* **ウェブサイト**: [https://chililikobo.github.io/](https://www.google.com/search?q=https://chililikobo.github.io/&utm_source=gemini)
* **X (旧Twitter)**: [@chililikobo](https://www.google.com/search?q=https://x.com/chililikobo&utm_source=gemini)
* **メール**: chilili.kobo@gmail.com
