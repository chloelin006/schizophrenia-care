# 思覺失調症照護知識網

靜態HTML/CSS/JavaScript網站。內容來自本課程中文醫院衛教Wiki，非醫院官方網站。

## 內容

- dist/index.html：疾病認識、症狀分類、照護措施、來源與資源下載。
- dist/presentation.html：14頁中文簡報，內嵌封面圖片。
- dist/assets/：樣式、互動程式與圖片。
- dist/downloads/：notes、逐頁內容與中文AGENTS.md。
- AGENTS.md：AI知識庫工作規範。

## 本機瀏覽

可直接開啟dist/index.html。也可在專案目錄使用python3 -m http.server，再瀏覽dist/。網站不需安裝套件或設定API金鑰。

## GitHub Pages

1. 將完整專案上傳新的GitHub repository。
2. Settings → Pages → Source 選擇 GitHub Actions。
3. 本專案附 .github/workflows/pages.yml，會將dist/發布至GitHub Pages。
4. 首次推送到main後，到Actions確認部署完成，從Pages取得實際網址。

沒有預設GitHub帳號、repository或已發布的GitHub網址。若使用其他分支，請相應修改workflow。網站既有的Sites網址屬另一種可瀏覽部署方式。

## 內容界線

僅使用Wiki已收錄S001–S006。候選文獻R001、R002只列後續參考，未用於正文。S005僅搜尋擷取；醫院衛教起始庫待臨床審閱。S006上傳原檔未另行公開鏡像；頁面僅提供機構名稱及年份。

## 圖片

封面人物為使用者確認的AI生成插畫，非真實病人照片。網站以CSS裁切顯示人物區域。
