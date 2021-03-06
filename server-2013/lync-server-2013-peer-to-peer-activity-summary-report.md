﻿---
title: Lync Server 2013：對等活動摘要報告
TOCTitle: 對等活動摘要報告
ms:assetid: e829a21e-9dfa-46ba-9b5b-077c175d6586
ms:mtpsurl: https://technet.microsoft.com/zh-tw/library/Gg615041(v=OCS.15)
ms:contentKeyID: 49292662
ms.date: 08/24/2015
mtps_version: v=OCS.15
ms.translationtype: HT
---

# Lync Server 2013 中的對等活動摘要報告

 

_**上次修改主題的時間：** 2015-03-09_

對等活動摘要報告提供對等通訊工作階段的整體檢視。對等工作階段通常只包含兩名使用者，且不需要使用 Lync Server 會議服務。比較起來，會議通常包含不只兩名使用者，且需要使用 Microsoft Lync Server 2013 會議服務。會議活動會回報到會議摘要報告。

對等活動摘要報告能協助您回答下列問題：

  - 我的使用者平日會傳送多少對等立即訊息？

  - 真的有使用者會利用 Lync Server 應用程式的共用與檔案傳輸功能嗎？

  - 使用者一直投訴網路在一天的某個時間變慢。在這個時段中，有幾分鐘是專門處理對等音訊與視訊工作階段？

## 存取對等活動摘要報告

您可從監控報告首頁存取對等活動摘要報告。要開啟 [Lync Server 2013 中的對等 IM 報告](lync-server-2013-peer-to-peer-im-report.md)，您可按一下下列其中一個指標：

  - 對等 IM 工作階段總數

  - 對等 IM 訊息總數

同樣地，要開啟對等語音與視訊報告，您可按一下下列其中一個指標：

  - 對等音訊工作階段總數

  - 對等音訊工作階段分鐘總數

  - 對等音訊工作階段總數

  - 對等音訊工作階段分鐘總數

## 充分利用對等活動摘要報告

對等活動摘要報告下方列出各種指標的總數，例如對等 IM 工作階段總數與對等 IM 訊息總數，提供一份摘要方便您快速檢閱報告內容的詳細資訊。

## 篩選器

篩選器可以讓您傳回更精確的資料集或者以不同方法檢視傳回的資料。例如，您可利用「對等活動摘要報告」選擇如何分組資料。在這種情況下，活動會按照小時、日、星期或月而加以分組。

下表列出可用於「對等活動摘要報告」的篩選器。

### 對等活動摘要報告篩選器

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>名稱</th>
<th>說明</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>從</strong></p></td>
<td><p>時間範圍的開始日期與時間。若要按照小時檢視資料，請輸入開始日期和時間，如下所示：</p>
<p>7/17/2012 1:00 PM</p>
<p>如果您未輸入開始時間，報告會自動從指定日期凌晨 12 點開始。若要按照日期檢視資料，只要輸入日期即可：</p>
<p>7/17/2012</p>
<p>若要按星期或月份查看，請輸入當週或該月您想查看的日期 (您不必輸入當週或該月的第一天)：</p>
<p>7/13/2012</p>
<p>星期永遠是從星期日開始星期六結束。</p></td>
</tr>
<tr class="even">
<td><p><strong>到</strong></p></td>
<td><p>時間範圍的結束日期與時間。若要按照小時檢視資料，請輸入開始日期和時間，如下所示：</p>
<p>7/17/2012 1:00 PM</p>
<p>如果您未輸入結束時間，報告會自動在指定日期凌晨 12 點結束。若要按照日期檢視資料，只要輸入日期即可：</p>
<p>7/17/2012</p>
<p>若要按星期或月份查看，請輸入當週或該月您想查看的日期 (您不必輸入當週或該月的第一天)：</p>
<p>7/13/2012</p>
<p>星期永遠是從星期日開始星期六結束。</p></td>
</tr>
<tr class="odd">
<td><p><strong>間隔</strong></p></td>
<td><p>時間間隔。請選取下列其中一項：</p>
<ul>
<li><p>每小時 (最多可以顯示 25 個小時)</p></li>
<li><p>每日 (最多可以顯示 31 天)</p></li>
<li><p>每週 (最多可以顯示 12 週)</p></li>
<li><p>每月 (最多可以顯示 12 個月)</p></li>
</ul>
<p>若開始與結束日期超出所選間隔允許的上限值，將只會顯示上限值 (從開始日期開始顯示)。例如，若您選取 [每日] 間隔，並將開始與結束日期分別設為 7/17/2012 及 2/28/2012，將只會顯示 8/7/2012 12:00 AM 至 9/7/2012 12:00 AM 這段期間的資料 (亦即只會顯示 31 天的資料)。</p></td>
</tr>
</tbody>
</table>


## 計量

下表列出對等活動摘要報告提供的資訊。

### 對等活動摘要報告計量

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th>名稱</th>
<th>可以排序這個項目嗎？</th>
<th>說明</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>每小時</strong></p>
<p><strong>每日</strong></p>
<p><strong>每週</strong></p>
<p><strong>每月</strong></p></td>
<td><p>否</p></td>
<td><p>在篩選工具列上顯示您所選取的時間間隔。在適用的情況下，只要按一下所指出的時間間隔，即可檢視該間隔的詳細資訊。例如，您若是使用 [每日] 間隔，然後按一下 7/17/2012，將會顯示使用者所登錄該日每小時的活動。</p></td>
</tr>
<tr class="even">
<td><p><strong>對等工作階段總數</strong></p></td>
<td><p>否</p></td>
<td><p>進行的對等工作階段總數，不區分工作階段類型。</p></td>
</tr>
<tr class="odd">
<td><p><strong>對等 IM 工作階段總數</strong></p></td>
<td><p>否</p></td>
<td><p>對等立即傳訊 (IM) 工作階段總數。當您按一下此項目時，本報告會顯示該選定時段的對等 IM 報告。</p></td>
</tr>
<tr class="even">
<td><p><strong>對等 IM 訊息總數</strong></p></td>
<td><p>否</p></td>
<td><p>對等工作階段中所傳送之立即傳訊總數。當您按一下此項目時，本報告會顯示該選定時段的對等 IM 報告。</p></td>
</tr>
<tr class="odd">
<td><p><strong>對等音訊工作階段總數</strong></p></td>
<td><p>否</p></td>
<td><p>對等音訊通話總數。當您按一下此欄位時，本報告會顯示該選定時段的對等語音和視訊報告。</p></td>
</tr>
<tr class="even">
<td><p><strong>對等音訊工作階段分鐘總數</strong></p></td>
<td><p>否</p></td>
<td><p>對等音訊工作階段中所花費的時間總數。當您按一下此項目時，本報告會顯示該選定時段的對等語音和視訊報告。</p></td>
</tr>
<tr class="odd">
<td><p><strong>平均對等音訊工作階段分鐘數</strong></p></td>
<td><p>否</p></td>
<td><p>對等音訊工作階段中所花費的時間平均總數。將總音訊工作階段時間除以總音訊工作階段數計算所得。</p></td>
</tr>
<tr class="even">
<td><p><strong>對等視訊工作階段總數</strong></p></td>
<td><p>否</p></td>
<td><p>對等視訊通話總數。請注意，視訊工作階段也會列入音訊工作階段計算：每個視訊工作階段會視為一個視訊工作階段和一個音訊工作階段。當您按一下此項目時，本報告會顯示該選定時段的對等語音和視訊報告。</p></td>
</tr>
<tr class="odd">
<td><p><strong>對等視訊工作階段分鐘總數</strong></p></td>
<td><p>否</p></td>
<td><p>對等視訊工作階段中所花費的時間總數。當您按一下此項目時，本報告會顯示該選定時段的對等語音和視訊報告。</p></td>
</tr>
<tr class="even">
<td><p><strong>平均對等視訊工作階段分鐘總數</strong></p></td>
<td><p>否</p></td>
<td><p>對等視訊工作階段中所花費的時間平均總數。將總訊訊工作階段時間除以總視訊工作階段數計算所得。</p></td>
</tr>
<tr class="odd">
<td><p><strong>對等檔案傳輸工作階段總數</strong></p></td>
<td><p>否</p></td>
<td><p>包含檔案傳輸之對等工作階段總數。</p></td>
</tr>
<tr class="even">
<td><p><strong>對等應用程式共用工作階段總數</strong></p></td>
<td><p>否</p></td>
<td><p>包含應用程式共用之對等工作階段總數。</p></td>
</tr>
</tbody>
</table>

