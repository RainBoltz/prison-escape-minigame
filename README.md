# prison-escape-minigame

越獄：挖地道 — 獄警不在的時候挖，倒數歸零前把現場收乾淨。

**▶ 線上遊玩：https://rainboltz.github.io/prison-escape-minigame/**

## 操作

- **桌機**：WASD 移動、滑鼠瞄準、左鍵挖、E 互動、Space 跳
- **手機**：橫屏遊玩，左半屏移動、右半屏瞄準

進度會自動存在瀏覽器的 localStorage，下次打開可以「繼續上次」。

## 部署

整個遊戲是單一個自包含的 `index.html`（three.js 已內嵌），由 GitHub Pages 從 `gh-pages` 分支的根目錄直接發佈。
更新遊戲時，替換 `index.html` 後推上 `gh-pages` 即可。
