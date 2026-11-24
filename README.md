# Turn Right 好轉燈：舊手機變身 AI 腳踏車方向燈

**Good Sign 好兆系列｜Turn Right — AI bicycle turn signal made from old phones**

> 轉彎先打燈，就是做一件好事。

兩支手機就能組成腳踏車方向燈：龍頭手機遙控，車尾手機顯示流水箭頭，並用 AI 偵測後方來車。

- 立即使用：**https://is.gd/turnright**
- 完整網址：https://robothandyman.github.io/goodturn/

## 怎麼用

1. 車尾手機（可用舊手機）開啟網站，點「我是車尾手機」，畫面會顯示 4 位數號碼和 QR code。
2. 龍頭手機用相機掃描 QR code，或開啟網站後點「我是龍頭手機」並輸入號碼。
3. 點龍頭手機左半邊是左轉，右半邊是右轉，長按任一邊開警示燈；也可以用聲控說「左轉、右轉、取消」。
4. 轉完彎後，系統依指南針判斷並自動關燈。
5. 在龍頭手機開啟「來車偵測」後，車尾手機用鏡頭辨識後方車輛；車輛快速靠近時，龍頭手機會震動並語音提醒。

## 功能

| 功能 | 說明 |
|---|---|
| 大面積觸控 | 左右各半個螢幕，戴手套也點得到 |
| 流水箭頭 | 車尾全螢幕琥珀色箭頭，夜間醒目 |
| 自動關燈 | 指南針偵測轉彎完成後自動熄燈，30 秒保底關閉 |
| 轉彎聲音 | 答答聲、語音「腳踏車左轉／右轉」、BBB，可由龍頭切換 |
| 聲控 | 說「左轉／右轉／取消／警示」即可操作 |
| AI 來車偵測 | COCO-SSD 在手機上即時辨識汽車、機車、公車、卡車 |
| QR 配對 | 掃描即配對，不必輸入號碼 |

## 技術

HTML／CSS／JavaScript、MQTT over WebSocket、TensorFlow.js + COCO-SSD、Web Speech API、DeviceOrientation、Vibration、Wake Lock。

- 純靜態網頁，不需安裝 App，也沒有後端伺服器。
- AI 影像辨識全部在手機上執行，影像不會上傳。
- 每組號碼各自獨立連線，可多人同時使用。

---
Good Sign 好兆系列：https://is.gd/goodsign
