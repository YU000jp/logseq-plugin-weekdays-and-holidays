# Logseq Plugin: Weekdays and Holidays (Templates) 🛌

- 平日と土日、祝日のジャーナルテンプレートを切り替えるためのプラグイン。曜日ごとにテンプレートを設定可能。

[](https://github.com/YU000jp/logseq-plugin-weekdays-and-weekends/releases)![latest release version](https://img.shields.io/github/v/release/YU000jp/logseq-plugin-weekdays-and-weekends) [](https://github.com/YU000jp/logseq-plugin-weekdays-and-weekends/LICENSE)![License](https://img.shields.io/github/license/YU000jp/logseq-plugin-weekdays-and-weekends?color=blue) [](https://github.com/YU000jp/logseq-plugin-weekdays-and-weekends/releases)![Downloads](https://img.shields.io/github/downloads/YU000jp/logseq-plugin-weekdays-and-weekends/total.svg)
 公開日:2023/05/04 /
 [日本語ドキュメント](https://github.com/YU000jp/logseq-plugin-weekdays-and-weekends/wiki/%E6%97%A5%E6%9C%AC%E8%AA%9E%E3%83%89%E3%82%AD%E3%83%A5%E3%83%A1%E3%83%B3%E3%83%88)📝

## デモ

![image](https://user-images.githubusercontent.com/111847207/235460001-a731d9eb-8b45-4c55-8789-d73e24bb655a.gif)

## 機能説明

- ジャーナルテンプレートにレンダリングと呼ぶものを置きます。それによってこのプラグインの機能が呼び出されます。
- ジャーナル以外のページでは、そのレンダリングが待機します。今日のジャーナルが空で呼び出されたときに、指定したテンプレートが反映されます。

4つのテンプレートを用意:

1. 平日のテンプレート `Main-Template`
2. サブのテンプレート `Sub-Template`
3. 週末のテンプレート `Weekends-Template`
4. 祝日のテンプレート `Holidays-Template`

- 複数のテンプレートによる条件指定や曜日変更が可能

## 初期設定

- [Engilsh document](https://github.com/YU000jp/logseq-plugin-weekdays-and-weekends/wiki/English-document)📝
- [日本語ドキュメント](https://github.com/YU000jp/logseq-plugin-weekdays-and-weekends/wiki/%E6%97%A5%E6%9C%AC%E8%AA%9E%E3%83%89%E3%82%AD%E3%83%A5%E3%83%A1%E3%83%B3%E3%83%88)📝

## Q&amp;A

- ジャーナル テンプレートが呼び出されたときにレンダリングを実行する必要があります。常にこのプラグインをオンにしてください。 Logseq モバイル版の場合は、手動でテンプレートを呼び出してください。
- 既存の[Full House Templates](https://github.com/stdword/logseq13-full-house-plugin)、[powerblocks](https://github.com/hkgnp/logseq-powerblocks-plugin)、[SmartBlocks](https://github.com/sawhney17/logseq-smartblocks)との統合が可能です。
- Logseq標準の動的変数をサポートします。
- さまざまな休日パターンに対応しています。

## Logseqマーケットプレースからインストール

- 右上にあるツールバーの[`---`]を押して[`Plugins`]を選択する
- マーケットプレースを選択する
- 検索欄に`week`と入力。<br>検索結果から探してインストール。

![image](https://user-images.githubusercontent.com/111847207/236143556-6404ec21-5e5f-457f-9193-f89f00330ff0.png)

## リンク(英語サイト)

- [templates (Logseq documents)](https://docs.logseq.com/#/page/templates)
- [Ramses Oudt / How to Set Up an Automated Daily Template in Logseq](https://thinkstack.club/how-to-set-up-an-automated-daily-template-in-logseq/)
- [Tempate Gallery plugin](https://github.com/dangermccann/logseq-template-gallery)

## マイプラグイン

- [Weekdays and Holidays (Templates)](https://github.com/YU000jp/logseq-plugin-weekdays-and-weekends)
- [Sticky Popup](https://github.com/YU000jp/logseq-plugin-sticky-popup)
- [SomeMenuExtender](https://github.com/YU000jp/logseq-plugin-some-menu-extender)
- [Column Layout](https://github.com/YU000jp/Logseq-column-Layout)
- [Panel Coloring](https://github.com/YU000jp/logseq-plugin-panel-coloring)
- [Page-tags and Hierarchy](https://github.com/YU000jp/logseq-page-tags-and-hierarchy)
- [Rakuten-books](https://github.com/YU000jp/logseq-plugin-rakuten-books) (Only for Japanese site)
- [booklog-jp-import](https://github.com/YU000jp/logseq-plugin-booklog-jp-import) (Only for Japanese site)

## 先行技術&amp;クレジット

### ライブラリ

- [@logseq/libs](https://logseq.github.io/plugins/) v.0.0.15
- [date-holidays](https://github.com/commenthol/date-holidays)
- [SweetAlert2](https://sweetalert2.github.io/)
- [logseq-L10N](https://github.com/sethyuan/logseq-l10n)

### Logseqプラグイン

- [stdword / Full House Templates](https://github.com/stdword/logseq13-full-house-plugin)
- [hkgnp / powerblocks](https://github.com/hkgnp/logseq-powerblocks-plugin)
- [sawhney17 / SmartBlocks](https://github.com/sawhney17/logseq-smartblocks)

### アイコン

- [icooon-rainbow.com](https://icon-rainbow.com/%e3%82%a4%e3%83%93%e3%82%ad%e3%82%92%e3%81%8b%e3%81%84%e3%81%a6%e5%af%9d%e3%81%a6%e3%82%8b%e4%ba%ba%e3%81%ae%e3%82%a2%e3%82%a4%e3%82%b3%e3%83%b3%e7%b4%a0%e6%9d%90/)

### Special Thanks

- [xyhp915](https://github.com/xyhp915) for @Logseq/libs v0.0.15
