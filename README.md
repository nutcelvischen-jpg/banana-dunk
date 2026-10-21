# 香蕉神射手：餵飽這隻巨象！🍌🐘 (Banana Dunk!)

一個使用 Blender 5.1 與 Three.js 製作的 3D 歡樂網頁小遊戲，使用 [shotgameskill](https://github.com/nutcelvischen-jpg/shotgameskill) 架構開發。

## 🎮 線上直接遊玩
👉 **[點此在 GitHub Pages 開始遊戲](https://nutcelvischen-jpg.github.io/banana-dunk/)**

---

## 🕹️ 遊戲玩法
- **彈弓拋物線投擲**：滑鼠或觸控往下拉開拋物線，放開即可將香蕉發射出去！
- **蓄力按鈕 / 空白鍵**：長按右下角按鈕或鍵盤 `Space` 空白鍵進行蓄力投擲。
- **視角切換 & 360° 旋轉**：
  - `🎯 投擲視角`：標準瞄準角度。
  - `🐒 小猴視角`：小猴子搭檔正面特寫。
  - `🔄 360°旋轉`：啟用 `OrbitControls`，自由環繞旋轉縮放全場！

---

## 🎙️ 魔性配音與台詞（Gemini 3.8 Flash TTS）
- **💥 打到頭**：大象生氣大喊：「`Phah tio̍h thâu--ah la! Kòng tio̍h thâu--ah la!`」（打到頭了啦！誰丟的！？）
- **💨 丟太遠超過**：大象無情吐槽：「`Lí kám ē-hiáu tàn--ah!? Tàn kah hiah-nī hn̄g!`」（你會不會丟啊！？丟那麼遠！）
- **🍌 完美進球**：大象歡呼：「`O-hó! Tsit ki tsioh-tsia̍h kài tiⁿ! Tsán--lah!`」（喔好！這根香蕉蓋甜！讚啦！）
- **💨 連擊打飽嗝**：「`嗝～～！Tsa̍p hun pá! Phah tsit ê tuā phú-kik!`」
- **🐒 小猴搭檔**：開場喊話、進球歡呼與失誤抓頭反應。

---

## 🛠️ 技術棧
- **3D 建模**：Blender 5.1 + Python API (bmesh, PBR, GLB 匯出)
- **3D 引擎**：Three.js 0.170.0 + WebGL + OrbitControls
- **物理計算**：象鼻區域座標系命中判定 (`worldToLocal`)、空氣阻力與側風模擬
- **音效與音樂**：Web Audio API 程序化合成器 (Jungle Bassline + SFX)
- **語音生成**：OpenRouter Google Gemini 3.8 Flash TTS
