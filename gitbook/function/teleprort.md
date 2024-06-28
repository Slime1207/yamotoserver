---
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

# 📗 傳送 Teleport

#### 隨機傳送 (/rtp)

您可以在主世界中隨機傳送至世界中的角落，可以幫助你減少跑圖的負擔。

目前隨機傳送的範圍為 **最多 500，最多 2000 格，**使用一次隨機傳送需要支付 **50** 元，并且擁有 **600秒 (5分鐘)** 的冷卻時間

**在地獄以及終界中無法使用。**

#### 私人傳送點 (/home)

您可以在伺服器中設置 10 個家的傳送點，這個傳送點是外人無法傳送的。

目前在設置超過 **5** 個傳送點后，需要支付 100 元來解鎖 1 個新的傳送點，傳送至加則不會有任何收費。

您可以使用指令 `/edithome [家的名稱] privacy [public/private]` 設定為私人傳送點 以及 公共玩家傳送點

#### 玩家公共傳送點 (/phome)

您可以在世界中設置 10 個玩家公共傳送點 (也就是把私人傳送點全部公開)，任何玩家都可以傳送至該地方。

目前需要支付 **50** 元來公開自己的傳送點，其他玩家傳送不會有任何收費。

您可以使用 `/phomelist` 查看玩家公開的傳送點&#x20;

#### 伺服器公共傳送點 (warp)

伺服器都會有官方的傳送點，通常會傳送到伺服器的官方建築。

您可以使用 `/warplist` 來查看伺服器的公共傳送點列表

#### 傳送至玩家的位置 (/tpa)

您可以使用 `/tpa` 來傳送到玩家的位置，需要玩家手動批准傳送請求。

您可以使用 `/tpaccept` 接受玩家的傳送請求。反之使用 `/tpdecline` 拒絕玩家的傳送請求。

#### 讓玩家傳送到你的位置 (/tpahere)

您可以使用 `/tpahere` 來讓玩家傳送到你的位置，需要玩家手動批准要求

您可以使用 `/tpaccept` 接受玩家的傳送請求。反之使用 `/tpdecline` 拒絕玩家的傳送請求。

### 指令魔法

{% hint style="danger" %}
_**以下内容僅在 5/7/2024 才可使用，請暫時不要使用這些指令。**_\
_**若需要，請在前面加上 /huskhomes: (/huskhomes:tpa) 來實現指令效果。**_
{% endhint %}

#### 魔法 1    |    傳送點魔法&#x20;

<table><thead><tr><th width="222">指令</th><th>備注</th></tr></thead><tbody><tr><td>/home (傳送點名稱)</td><td>前往一個私人傳送點</td></tr><tr><td>/sethome (傳送點名稱)</td><td>設置一個私人傳送點</td></tr><tr><td>/delhome (傳送點名稱)</td><td>刪除一個私人傳送點</td></tr><tr><td>/delhome all </td><td>刪除全部的傳送點</td></tr><tr><td>/homelist</td><td>查看所有的傳送點</td></tr><tr><td>/edithome (傳送點名稱)</td><td>設置私人傳送點</td></tr><tr><td>/edithome (傳送點名稱) rename (新名稱）</td><td>更改傳送點名稱</td></tr><tr><td>/edithome (傳送點名稱) description (描述)</td><td>設置一個對傳送點的描述</td></tr><tr><td>/edithome (傳送點名稱) relocate</td><td>重新設置傳送點坐標 (需要站在新坐標上)</td></tr><tr><td>/edithome (傳送點名稱) privacy [public|private]</td><td>設置傳送點為公開或私人傳送點<br><code>public</code> : 公開 | <code>private</code> : 私人</td></tr><tr><td>/phome (傳送點名稱)</td><td>前往一個玩家公開的傳送點</td></tr><tr><td>/phomelist </td><td>查看所有公開傳送點</td></tr><tr><td>/warp (傳送點名稱)</td><td>傳送至伺服器官方傳送點</td></tr><tr><td>/warplist</td><td>查看所有伺服器官方傳送點</td></tr></tbody></table>

#### 魔法 2    |    傳送玩家魔法

<table><thead><tr><th width="223">指令</th><th>描述</th></tr></thead><tbody><tr><td>/tpa (玩家)</td><td>傳送至玩家的位置</td></tr><tr><td>/tpahere (玩家)</td><td>讓玩家傳送到你的位置</td></tr><tr><td>/tpaccept</td><td>接受傳送請求</td></tr><tr><td>/tpaccept (玩家)</td><td>接受該玩家最近的傳送請求</td></tr><tr><td>/tpdecline</td><td>拒絕傳送請求</td></tr><tr><td>/tpdecline (玩家)</td><td>拒絕該玩家最近的傳送請求</td></tr><tr><td>/tpignore</td><td>無視所有玩家的傳送請求</td></tr></tbody></table>

#### 魔法 3    |    其他傳送魔法

<table><thead><tr><th width="171">指令</th><th>描述</th></tr></thead><tbody><tr><td>/rtp</td><td>隨機傳送玩家</td></tr><tr><td>/back</td><td>返回至死亡地點/被傳送走的地點</td></tr></tbody></table>
