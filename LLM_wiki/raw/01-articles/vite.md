plugins: [react()]
引入了 `@vitejs/plugin-react`
- **作用**：這是讓 Vite 看懂 React 語法的關鍵。它負責處理 JSX/TSX 檔案的編譯，並啟用 **熱更新（HMR, Hot Module Replacement）**，讓你在修改 React 元件時，瀏覽器不用整個重新整理就能即時看到變化。
-TypeScript 的 `import` ==用來載入其他檔案（模組）裡匯出的變數、函式、類別或型別== 。

現代 Vite 專案都採用這種「方案模式（Solution Mode）」來管理 TypeScript。