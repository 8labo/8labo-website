# 8LABO Preview History

- P001 — 2026-08-12 — Production-equivalent baseline before mobile redesign.
- P002 — 2026-08-12 — Mobile redesign: full-screen navigation, reduced mobile typography, preserved intentional line breaks, wider OUR ACTION content layout, visible preview version badge. **Permanent rollback branch: `preview-p002-backup` / commit `fe3c765c98b17b7d0d3c15d343ffd2a61eb130ec`.**
- P003 — 2026-08-14 — Full renewal based on 「８LABO公式ホームページ リニューアル指示書」. Reordered homepage from user needs → value → services → reasons → activity/trust → Mission/Vision; rebuilt ACADEMY around parent needs and child outcomes; mobile-first typography and navigation; photo slots prepared for real 8LABO activity images. **Permanent rollback branch: `preview-p003-backup` / commit `205c5c297508284373c57c56debf9b02374770fe`.**
- P004 — 2026-08-14 — Connected Preview to the ８LABO portal homepage-management CMS. Published news, selected homepage text, and managed activity photos are read from Supabase; homepage and ACADEMY photo slots can be updated without editing GitHub.
- P005 — 2026-08-14 — Fixed CMS photos so placeholder text such as “ACTIVITY PHOTO” and the temporary photo note disappear automatically once a real image is assigned.

運用ルール：Preview更新ごとに P006, P007... と番号を付与します。ユーザーから「P00Xに戻して」と指定された場合、そのPreview状態へ復元します。P002・P003は専用バックアップブランチを作成済みです。
