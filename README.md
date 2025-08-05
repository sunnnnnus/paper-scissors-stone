##🥢 猜拳決定吃什麼
線上試用連結[https://paper-scissors-stone-seven.vercel.app]
這是一個創意小工具，專門解決選擇障礙：讓兩方先輸入「想吃的餐點」，再用電腦隨機猜拳，決定要吃哪一個！

#🧱 功能特色
左／右輸入想吃的餐點，例如火鍋、壽司、披薩等
電腦替雙方「隨機出拳」判定勝負
勝方輸入欄的內容就是最後要吃的餐點
中間清晰顯示勝負結果與出拳表情 emoji
使用者介面簡潔可愛、反應迅速

#⚙️ 技術架構
HTML + CSS + JavaScript (Vanilla JS)
CSS 使用 flex 排版、圓角、溫和配色 (藍綠色清新系)
主要程式邏輯
getRandomHand()：隨機回傳 rock/paper/scissors
checkWinner()：判斷勝負邏輯
playGame()：整合使用者輸入、隨機出拳與結果顯示

#📝 專案結構
index.html
│   └── HTML 結構 + CSS 樣式 + JavaScript 邏輯

#🚀 使用方式
打開 線上 demo
輸入左右兩邊想吃的餐點
按下「🥊」按鈕
觀看猜拳 emoji、最後勝敗提示和輸出餐點

#💡 延伸提案（可以繼續開發的方向）
新增平局重試累積機制
增加 emoji 對應餐點的小 icon，例如壽司 → 🍣、火鍋 → 🍲
加入音效或簡單動畫
支援手機橫豎排版、自適應顯示
以 Vue.js / React 重構互動邏輯，方便日後學習前端框架
