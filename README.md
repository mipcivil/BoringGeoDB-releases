# BoringGeoDB - 地質調査データベースソフト

複数のボーリングXMLを一括管理し、地図表示・断面図・地盤モデル・納品データ生成までをひとつのアプリで完結できるWindowsデスクトップソフトです。

## ダウンロード

**[最新版をダウンロード](https://github.com/mipcivil/BoringGeoDB-releases/releases/latest)**

> Windows 10/11 (64-bit) 対応 | インストール不要（ZIP展開のみ）

## 主な機能

- 🗺️ **地図ビューでボーリング地点を一覧** — 全地点を地図上に表示、クリックで詳細確認
- 📐 **断面図の生成** — ボーリング地点を選択してDXF/P21形式で出力
- 🏗️ **3D地盤モデル構築** — 表層面の補間、基盤岩定義、断層管理
- 📦 **納品データの一括生成** — 納品要領準拠のフォルダ構成でBRG・GTST・データシートを出力
- 💧 **地下水データの可視化** — 時系列チャート・等高線図
- 💰 **積算・見積機能** — 調査費用の自動積算、カスタム単価テーブル対応
- ✏️ **XMLエディタ内蔵** — BoringXMLEditorの全機能を搭載（柱状図PDF/DXF出力含む）
- 🔍 **データ検索・クエリ実行** — SQLライクなクエリで複数ボーリングデータを横断検索

## 使い方

1. [Releases](https://github.com/mipcivil/BoringGeoDB-releases/releases/latest) から最新のZIPをダウンロード
2. ZIPを展開
3. `BoringGeoDB.exe` を起動
4. 納品要領準拠のフォルダを指定してプロジェクトを作成
5. ボーリングXMLを読み込み

## BoringXMLEditorとの関係

BoringGeoDBには **BoringXMLEditorの全機能** が内蔵されています。

- **BoringXMLEditor**: 1ファイルずつXMLを編集。柱状図プレビュー・PDF/DXF出力。[無料ダウンロード](https://mipcivil.github.io/BoringXMLTool-JP/)
- **BoringGeoDB**: XMLエディタ＋複数XMLの統合管理・地図・断面図・地盤モデル・納品生成

個別にXMLを編集したい場合は、無料の BoringXMLEditor 単体でもお使いいただけます。

## 料金（ベータ版価格）

| プラン | 価格（税込） |
|--------|-------------|
| 月額プラン | ¥4,000/月 |
| 年額プラン | ¥48,000/年 |

> ※ 現在ベータ版のため特別価格で提供しています。正式リリース後に価格を調整する場合があります。

- いつでもキャンセル可能
- ライセンスは1台のPCに紐づきます
- 銀行振込にも対応

## 動作環境

- Windows 10 / 11 (64-bit)
- インストール不要（ZIPを展開するだけ）
- レジストリへの書き込みなし

## お問い合わせ

- 不具合報告・ご質問: [info@strataworks.dev](mailto:info@strataworks.dev)
- ホームページ: [https://mipcivil.github.io/BoringGeoDB-releases/](https://mipcivil.github.io/BoringGeoDB-releases/)

## ライセンス

本ソフトウェアは商用ソフトウェアです。利用規約はホームページをご確認ください。
