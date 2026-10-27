# 購屋房貸試算

純靜態網頁，`index.html` 位於根目錄，無依賴、無建置。所有計算都在瀏覽器內完成。

## GitHub
建立空 repository，把本資料夾內所有檔案（含 `.gitignore`、`_headers`）拖進網頁上傳，Commit 即可。

## Cloudflare
- Pages → Connect to Git：Framework 選 None，Build command 留空，Build output directory 留空或填 `/`。
- 或 Pages → Upload assets：直接拖入本資料夾或 ZIP。
- 若用 Workers 匯入 repo，`wrangler.jsonc` 已設定好。
