# 課堂交接｜進行中

這是待填狀態，不代表已完成；Codex按實際證據更新，沒有證據寫「未驗證」。不填任何keys、私人資料或本機路徑。

- 模板版本：已核對 `0.1.0-rc1`；固定 schema lock 已通過 `0.1.0-rc4`
- 自己的repo／branch：未建立
- 課前整合及env：已核對 Google Sheet、Supabase目標、GitHub及Vercel身份；本機env格式檢查通過（不代表API生成已實測）
- 固定Supabase結構／app登入：指定空project已原封不動執行固定bootstrap；7張表、RLS、runtime函數、Auth trigger及2個private buckets已讀回，security advisor無警告。app Auth用戶及登入仍待使用者完成
- Sheet匯入／讀回：未驗證
- 品牌保存／讀回：未驗證
- 中途push：未驗證
- 文字／圖片／腳本／Newsletter保存：未驗證
- 最後tests／build：現階段92項tests通過，production build通過；堂尾仍需再跑
- 堂尾push：未驗證（最終commit從Git HEAD及遠端核對）
- 個人部署資格：按RELEASE-GATES的學生檢查核對；未核對
- 未完成項目／下一步：由使用者在指定Supabase project建立自己的Auth測試用戶，再到PersonalOS登入；登入後核對自己的workspace已建立及可讀。Performance advisor另有固定SQL內1項未覆蓋FK index提示及空庫unused-index提示，依schema-lock規則未作修改
