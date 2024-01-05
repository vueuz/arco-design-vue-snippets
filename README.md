# Arco Design Vue代码片段简介

> Arco Design Vue Snippets 是一个适用于Visual Studio Code的代码片段集合，可帮助您更轻松、更快速地编写Arco Design组件。

## 安装

### 手动安装

前往GitHub并下载代码片段文件夹，然后将文件夹中的文件直接复制到以下路径：

Mac：`/Users/<your-user-name>/Library/ApplicationSupport/Code/User/snippets/`

Windows：`<your-installed-driver>:\Users\<your-user-name>\AppData\Roaming\Code\User\snippets\`

### 通过VSCode扩展

从网站：前往Visual Studio Code市场，搜索“Arco Design Vue Snippets”，然后点击安装按钮。
从VSCode：点击扩展侧边栏，搜索“Arco Design Vue Snippets”，然后点击安装按钮。

## 特殊说明

对于需要子组件作为其内容的组件（例如a-timeline），请使用`arti` 来用v-for循环生成子组件。

## 代码片段列表

Arco Design的所有标签如下，忽略闭合标签和其他更详细的信息。例如`arbtn`生成`<a-button" type="$1" @click="$2">$3</a-button>`。
代码片段的顺序基本遵循Arco Design官方网站指南中组件的顺序。目前共有88个代码片段。如有必要，会添加更多。目前仅适用于.vue文件。

Arco Design代码片段可帮助您提高开发效率，并确保您始终使用最新版本的Arco Design库。



|Prefix|Body|
|---|---|
|Common|
|`arb`|`<a-button>`|
|`arl`|`<a-link>`|
|`artyp`|`<a-typography>`|
|Layout|
|`arlayout`|`<a-layout>`|
|`arheader`|`<a-layout-header>`|
|`arfooter`|`<a-layout-footer>`|
|`arsider`|`<a-layout-sider>`|
|`arcontent`|`<a-layout-content>`|
|`arrow`|`<a-row>`|
|`arcol`|`<a-col>`|
|`ars`|`<a-space>`|
|`ardiv`|`<a-divider>`|
|Data Display|
|`arav`|`<a-avatar>`|
|`arbad`|`<a-badge>`|
|`arcal`|`<a-calendar>`|
|`arcard`|`<a-card>`|
|`arcar`|`<a-carousel>`|
|`arcollapse`, `arcoll`|`<a-collapse>`|
|`arcollapseitem`, `arcolli`|`<a-collapse-item>`|
|`arcom`|`<a-comment>`|
|`arcoms`|`<a-comment>`|
|`ardes`|`<a-descriptions>`|
|`ardesi`|`<a-descriptions-item>`|
|`arem`|`<a-empty>`|
|`arimg`|`<a-image>`|
|`arlist`|`<a-list>`|
|`arpopover`|`<a-popover>`|
|`arstat`|`<a-statistic>`|
|`art`|`<a-table>`|
|`artab`|`<a-tabs>`|
|`artag`|`<a-tag>`|
|`artags`|`<a-tag>`|
|`artl`|`<a-timeline>`|
|`artli`|`<a-timeline-item>`|
|`artlis`|`<a-timeline-item>`|
|`artooltip`|`<a-tooltip>`|
|`artree`|`<a-tree>`|
|Data Entry|
|`arac`|`<a-auto-complete>`|
|`arcas`|`<a-cascader>`|
|`arc`|`<a-checkbox>`|
|`arcs`, `arcg`|`<a-checkbox-group>`|
|`ardp`|`<a-date-picker>`|
|`ardrp`|`<a-range-picker>`|
|`arf`|`<a-form>`|
|`arfi`|`<a-form-item>`|
|`ari`, `arinput`|`<a-input>`|
|`arip`, `arinputp`|`<a-input-password>`|
|`arin`|`<a-input-number>`|
|`arver`|`<a-verification-code>`|
|`aritag`, `arit`|`<a-input-tag>`|
|`armen`|`<a-mention>`|
|`arr`|`<a-radio>`|
|`arrs`|`<a-radio-group>`|
|`arrg`|`<a-radio-group>`|
|`arrate`|`<a-rate>`|
|`arsel`, `arselect`|`<a-select>`|
|`arselo`, `arselecto`, `aro`|`<a-option>`|
|`arselos`, `arselectos`, `aros`|`<a-option>`|
|`arsl`|`<a-slider>`|
|`arsw`|`<a-switch>`|
|`artext`|`<a-textarea>`|
|`artp`|`<a-time-picker>`|
|`artrans`|`<a-transfer>`|
|`arup`|`<a-upload>`|
|Feedback|
|`aral`|`<a-alert>`|
|`ardrawer`|`<a-drawer>`|
|`arm`|`<a-modal>`|
|`arpc`, `arpopc`|`<a-popconfirm>`|
|`arpr`|`<a-progress>`|
|`arres`|`<a-result>`|
|`arspin`|`<a-spin>`|
|`arske`|`<a-skeleton>`|
|`arskel`|`<a-skeleton-line>`|
|`arskes`|`<a-skeleton-shape>`|
|Navigation|
|`armenu`|`<a-menu>`|
|`armenuitem`, `armenui`|`<a-menu-item>`|
|`armenuis`, `armenuitems`|`<a-menu-item>`|
|`armenusub`|`<a-sub-menu>`|
|`ardd`, `ardrop`|`<a-dropdown>`|
|`arddopt`, `arddo`, `arddi`|`<a-doption>`|
|`arddopts`, `arddos`, `arddis`|`<a-doption>`|
|`arbread`|`<a-breadcrumb>`|
|`arbreaditem`, `arbreadi`|`<a-breadcrumb-item>`|
|`arbreaditems`, `arbreadis`|`<a-breadcrumb-item>`|
|`arph`|`<a-page-header>`|
|`arpag`|`<a-pagination>`|
|`arsteps`|`<a-steps>`|
|`arstepi`|`<a-step>`|
|`arstepis`|`<a-step>`|
