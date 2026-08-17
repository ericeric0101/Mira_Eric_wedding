# 📖 Mira & Eric Wedding Story — 喜帖與遊戲客製化指南

歡迎使用本遊戲化電子喜帖！所有設定與文字均集中於 `index.html` 的 `CUSTOMIZE_HERE` 區塊，您可以輕鬆置換真實照片、文案、音樂與圖片。

---

## 📷 1. 替換真實生活 / 婚紗照片 (Real Photos)
過關拍立得卡片支援 **「3D 翻轉看真實照片」**，在最終頁面也會展示浪漫婚紗照。
直接將你們的真實照片放入 `assets/photos/` 並保持以下檔名（或在 `CUSTOMIZE_HERE.photos` 修改路徑）：
- **台灣回憶照**：`assets/photos/taiwan.jpg`
- **德國回憶照**：`assets/photos/germany.jpg`
- **韓國回憶照**：`assets/photos/korea.jpg`
- **婚紗/求婚合照**：`assets/photos/wedding.jpg`

> 💡 **照片文字說明**：可在 `index.html` 中的 `CUSTOMIZE_HERE.photoCaptions` 修改每一張照片下方的拍立得手寫風圖說。

---

## 📝 2. 修改故事文案與婚禮資訊
在 `index.html` 中搜尋 `CUSTOMIZE_HERE`：
- **主角名字**：`playerNames: { p1: 'Eric', p2: 'Mira' }`
- **婚禮資訊**：`weddingInfo: { date: '2026-10-10', location: 'Taipei, Taiwan', rsvpUrl: '您的Google表單網址' }`
- **各關故事文案**：`story.p1` 與 `story.p2`。

---

## 🦘 3. 各國特色彈簧跳板 (Springboards)
遊戲中已內建四國特色跳板道具：
- 🇹🇼 **台灣**：小籠包蒸籠彈簧（蒸氣噴射高跳 🥟）
- 🇩🇪 **德國**：ICE 高鐵極速跳板（加速向前衝刺 🚄）
- 🇰🇷 **韓國**：櫻花旋風跳板（粉紅櫻花懸浮 🌸）
- 💍 **Final**：浪漫愛心彈簧（真愛愛心連擊 💖）

---

## 🎵 4. 8-Bit 婚禮進行曲與背景音樂
- **預設音樂**：內建 Procedural 8-bit 音效合成器，通關抵達結婚殿堂時會自動奏響 **8-bit 復古版《婚禮進行曲》**！
- **若想使用自選 MP3**：將音樂檔放入 `assets/music/bgm.mp3`，並將 `CUSTOMIZE_HERE.audio.src` 設定為 `'assets/music/bgm.mp3'` 即可。

---

## 🎨 5. 替換像素插畫素材
- **關卡背景**：`assets/backgrounds/`（`taiwan.png`, `germany.png`, `korea.png`, `final.png`）
- **主角像素圖**：`assets/players/`（`player1-idle.png`, `player1-run1.png`, `player1-jump.png`, `player2.png`）
- **收集品圖示**：`assets/collectibles/`
