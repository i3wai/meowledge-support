# meowledge-support — 專案指令

Meowledge iOS app 喺 App Store 嘅支援／marketing URL 目標頁（見 `~/Projects/meowledge-web/docs/MAP.md` family 全圖）。單一 `index.html`：冇 build step、冇依賴、冇 server，特意保持咁簡。

## 慣例

- 淨係得一個 tracked 檔（`index.html`）；唔好引入 framework／build step
- FAQ 答案跟 App Store 規則：app 係 consumable-only IAP（3.1.1），「買咗嘅嘢點攞返」必須指向 app 自己嘅 recovery 機制，唔好寫用 Restore Purchases 攞返（`f51a945`）
- 提到工具要同 meowledge-web 口徑一致（`b39825b`：加入 Portion Calculator，v1.1）
