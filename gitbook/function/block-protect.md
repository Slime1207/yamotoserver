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

# 📗 方塊保護 Block Protect

#### 方塊保護是什麽？

方塊保護可以讓您在不宣告領地的狀況下，可以保護您的一些容器以及方塊。

#### 如何保護方塊？

首先，您需要準備一個告示牌 (任何材質都可以)

接著，您需要對著您想要保護的方塊點擊右鍵 (手機版則是輕點) 后，即代表已經成功

<figure><img src="https://raw.githubusercontent.com/Slime1207/yamotoserver/main/picture/wiki/003.png" alt=""><figcaption><p>成功保護視角！會出現 [私有] 然後還有你的名稱 (Java與基岩版本相同)</p></figcaption></figure>

#### 保護範圍

<table><thead><tr><th width="134" align="center">種類</th><th>名稱</th></tr></thead><tbody><tr><td align="center">門</td><td>橡木門，雲杉木門，白樺木門，叢林木門，金合歡木門，深色橡木門，紅樹木門，櫻花木門，竹門，鐵門，緋紅木門，詭異門</td></tr><tr><td align="center">地板門</td><td>橡木地板門，雲杉木地板門，白樺地板木門，叢林木地板門，金合歡地板木門，深色地板橡木門，紅樹地板木門，櫻花地板木門，竹地板門，鐵地板門，緋紅木地板門，詭異地板門</td></tr><tr><td align="center">容器</td><td>箱子 (大)，箱子 (小)，投擲器，發射器，終界箱，木桶，各種界浮盒，漏斗</td></tr><tr><td align="center">其他</td><td>附魔臺，鐵趈</td></tr></tbody></table>

#### 更改分享對象&#x20;

除了只可以給自己查看箱子外，您也可以編輯告示牌的内容來分享給其他玩家們一起查看。\
包括可以使用漏洞 (紅石) 傳輸，甚至可以在指定秒數内釋放紅石訊號！例如 :

```markup
// 分享給其他的玩家
[私人]
SlimeKing1207 <- 這是你
IAmSecondPlayer <- 第二個玩家
ShinyThirdPlayer <- 第三個玩家
```

當然，你也可以加入標簽作爲特別的用途！包括 :

```
[紅石] - 允許紅石訊號傳遞 (如漏斗)
[計時:(秒)] - 在 (秒) 后釋放紅石訊號
[所有人] - 允許所有玩家使用
[更多使用者] - 可以讓更多的使用者使用 (請查看上方私人用法)
```
