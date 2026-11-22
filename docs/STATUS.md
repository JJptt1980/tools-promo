# STATUS

## 目前進度
- userscripts-3in1：/promo 第 1 步完成（brief、ChatGPT 訊息），等使用者把訊息貼到 ChatGPT

## 已定案的決定
- 以後所有小工具的廣宣都放 `~/Projects/tools-promo/<廣宣名>/promo/`
- 露天、NBA、防彈窗三支腳本合成一份廣宣（一份 brief、一組圖、一個頁面、一篇貼文）
- 合併廣宣主色：深青 #0F766E、輔色暖橘 #F59E0B
- 防彈窗對外不寫影片網站名稱、不放該站畫面

## 下一步
- 使用者貼 ChatGPT、下載參考圖、複製回覆後打 /promo（第 2 步）
- 補露天截圖 `userscripts-3in1/promo/screens/ruten.png`

## 已知問題
- 露天、NBA 兩支腳本的 `@namespace` 還是 `https://github.com/killnopig`（舊帳號名）。改了 Tampermonkey 可能把它當成新腳本、舊的不再自動更新，所以先不動，等使用者決定
- 這個資料夾還沒有 GitHub repo；第 5 步部署 Pages 前再問要不要建
