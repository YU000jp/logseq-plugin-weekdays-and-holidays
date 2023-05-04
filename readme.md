# Logseq Plugin: Weekdays and Holidays (Templates) 🛌

- Plugin for switching journal templates for weekdays and weekends, public holidays. Possible to set templates for each day of the week. This plugin is capable of corresponding to holidays in various countries around the world, thanks to the library we utilize.

[![latest release version](https://img.shields.io/github/v/release/YU000jp/logseq-plugin-weekdays-and-weekends)](https://github.com/YU000jp/logseq-plugin-weekdays-and-weekends/releases)
[![License](https://img.shields.io/github/license/YU000jp/logseq-plugin-weekdays-and-weekends?color=blue)](https://github.com/YU000jp/logseq-plugin-weekdays-and-weekends/LICENSE)
[![Downloads](https://img.shields.io/github/downloads/YU000jp/logseq-plugin-weekdays-and-weekends/total.svg)](https://github.com/YU000jp/logseq-plugin-weekdays-and-weekends/releases)
 [日本語ドキュメント](https://github.com/YU000jp/logseq-plugin-weekdays-and-weekends/wiki/%E6%97%A5%E6%9C%AC%E8%AA%9E%E3%83%89%E3%82%AD%E3%83%A5%E3%83%A1%E3%83%B3%E3%83%88)📝
 
## Demo

![image](https://user-images.githubusercontent.com/111847207/235460001-a731d9eb-8b45-4c55-8789-d73e24bb655a.gif)

## Features

- On pages other than journal, rendering waits. When loaded as today's journal, the designated template is reflected. And, as usual, the template can be called manually at any time.

Offer four templates:

1. Weekdays templates `Main-Template`
1. Main/Sub templates `Sub-Template`
1. weekends template `Weekends-Template`
1. Public holiday template `Holidays-Template`

- possible to specify conditions using multiple templates and change days of a week

## Setup 🖥️

- [Engilsh Document](https://github.com/YU000jp/logseq-plugin-weekdays-and-weekends/wiki/English-Document)📝
- [日本語ドキュメント](https://github.com/YU000jp/logseq-plugin-weekdays-and-weekends/wiki/%E6%97%A5%E6%9C%AC%E8%AA%9E%E3%83%89%E3%82%AD%E3%83%A5%E3%83%A1%E3%83%B3%E3%83%88)📝

## Questions

- Always turn on this plugin for execute rendering when journal template is called. For Logseq mobile version, please manually call the template.
- At the moment, integration with existing plugins such as smart-blocks is not possible. We plan to address this in future updates.
- In the current version, standard Dynamic variables are not supported.
- For those who live every day like a holiday, this plugin may not be necessary.🤣

## Plugin Changes Due to `@logseq/libs` Upgrade v0.0.15 TODO:

- This plugin utilizes `@logseq/libs` plugin API library. Currently, the older version of the SDK is unable to load templates as templates, so they are being loaded simply as block trees. However, there are plans to provide the functionality to load templates as templates in the future. This will enable integration with existing plugins such as `smart-blocks`. There is a possibility that changes in usage and the need for resetting configuration items may occur.

## Install from Logseq Marketplace

- Press [`---`] on the top right toolbar to open [`Plugins`]
- Select marketplace
- Type `week` in the search field, select it from the search results and install

![image](https://user-images.githubusercontent.com/111847207/236143556-6404ec21-5e5f-457f-9193-f89f00330ff0.png)

## Link

- [Ramses Oudt / How to Set Up an Automated Daily Template in Logseq](https://thinkstack.club/how-to-set-up-an-automated-daily-template-in-logseq/)

## My plugins

- [Weekdays and Holidays (Templates)](https://github.com/YU000jp/logseq-plugin-weekdays-and-weekends)
- [Sticky Popup](https://github.com/YU000jp/logseq-plugin-sticky-popup)
- [SomeMenuExtender](https://github.com/YU000jp/logseq-plugin-some-menu-extender)
- [Column Layout](https://github.com/YU000jp/Logseq-column-Layout)
- [Panel Coloring](https://github.com/YU000jp/logseq-plugin-panel-coloring)
- [Page-tags and Hierarchy](https://github.com/YU000jp/logseq-page-tags-and-hierarchy)
- [Rakuten-books](https://github.com/YU000jp/logseq-plugin-rakuten-books) (Only for Japanese site)
- [booklog-jp-import](https://github.com/YU000jp/logseq-plugin-booklog-jp-import) (Only for Japanese site)

## Prior art & Credit

### Library

- [@logseq/libs](https://logseq.github.io/plugins/) v.0.0.14
- [date-holidays](https://github.com/commenthol/date-holidays)
- [SweetAlert2](https://sweetalert2.github.io/)

### Logseq Plugin

Not Support - **TODO:**

- [stdword / Full House Templates](https://github.com/stdword/logseq13-full-house-plugin)
- [hkgnp / powerblocks](https://github.com/hkgnp/logseq-powerblocks-plugin)
- [sawhney17 / SmartBlocks](https://github.com/sawhney17/logseq-smartblocks)

### Icon

- [icooon-rainbow.com](https://icon-rainbow.com/%e3%82%a4%e3%83%93%e3%82%ad%e3%82%92%e3%81%8b%e3%81%84%e3%81%a6%e5%af%9d%e3%81%a6%e3%82%8b%e4%ba%ba%e3%81%ae%e3%82%a2%e3%82%a4%e3%82%b3%e3%83%b3%e7%b4%a0%e6%9d%90/)

### Special Thanks

- [xyhp915](https://github.com/xyhp915) for @Logseq/libs
