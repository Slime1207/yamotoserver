---
description: 配套指令都爲 /res 開始
layout:
  title:
    visible: false
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# 📗 領地 Residence

<div data-full-width="true">

<figure><img src="../../picture/wiki/title_residence.png" alt=""><figcaption><p>領地 / Residence</p></figcaption></figure>

</div>

#### 領地可以做什麽？

領地可以防止玩家可以輕易破壞，進入其中一個被您框起來的區域。\
當然，也可以防止怪物以及TNT爆炸或者破壞！

#### 我該怎麽創建領地呢？

首先，你需要準備一個木鋤，讓你可以使用該工具框出一個區域。\
該區域需要大於 `3x3x3`，并且你自己也需要 `2.7` 元眠幣來去創建一個領地。(0.1/格)

接著，玩家需要選中區域中的兩個角落。一個點擊右鍵設定第一個角落，而第二個角落則可以左鍵設定第二個角落\
( 手機版本玩家需要長按第一個角落，然後點擊第二個角落就好。)

<figure><img src="https://raw.githubusercontent.com/Slime1207/yamotoserver/main/picture/wiki/002.png" alt=""><figcaption><p>框選正確會出現視角 (Java與基岩版一致)</p></figcaption></figure>

最後，輸入 /res create <名稱> 就完成了

#### 領地插件指令

<table><thead><tr><th width="282" align="center">指令</th><th>描述</th><th data-hidden></th></tr></thead><tbody><tr><td align="center">/res rename <code>&#x3C;舊領地> &#x3C;新領地></code></td><td><code>重新命名</code>你的領地</td><td></td></tr><tr><td align="center">/res remove <code>&#x3C;領地></code></td><td>刪除<code>領地</code> (不會獲得金錢)</td><td></td></tr><tr><td align="center">/res tpset</td><td>設置領地傳送點 (須在領地裏)</td><td></td></tr><tr><td align="center">/res set <code>&#x3C;權限> </code><em><code>&#x3C;true/false></code></em></td><td>設置領地<code>權限 </code><em><code>&#x3C;開啓/關閉></code></em></td><td></td></tr><tr><td align="center">/res padd <code>&#x3C;領地> &#x3C;玩家></code></td><td>給予<code>領地成員資格</code></td><td></td></tr><tr><td align="center">/res flags</td><td>開啓權限設定菜單</td><td></td></tr><tr><td align="center">/res pset <code>&#x3C;玩家> &#x3C;領地></code></td><td>設置<code>特定玩家</code>的<code>權限</code></td><td></td></tr><tr><td align="center">/res pset <code>&#x3C;玩家> &#x3C;領地> removeall</code></td><td>移除設定<code>特定玩家</code>的<code>所有設置權限</code></td><td></td></tr><tr><td align="center">/res tp <code>&#x3C;領地></code></td><td>傳送至<code>領地</code></td><td></td></tr><tr><td align="center">/res expend <code>&#x3C;格></code></td><td>向玩家方向拓展領地</td><td></td></tr><tr><td align="center">/res contract <code>&#x3C;格></code></td><td>向玩家方向縮小領地</td><td></td></tr><tr><td align="center">/res subzone <code>&#x3C;領地> &#x3C;區域></code></td><td>創建一個<code>領地</code>内的<code>區域</code></td><td></td></tr><tr><td align="center">/res minor <code>&#x3C;領地A> &#x3C;領地B></code></td><td>把 <code>領地A</code> 的權限複製進 <code>領地B</code></td><td></td></tr></tbody></table>
