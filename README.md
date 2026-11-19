# Core Vision Technologies

موقع شركة كور فيجن تكنولوجيز: كاميرات مراقبة، شبكات، وبرامج للمحلات والشركات.

## الإعدادات
في آخر ملف `index.html` جوه `<script>`:
- `WA_NUMBER`: رقم الواتساب اللي بيستقبل الطلبات.
- `FORMSPREE_ID`: كود الفورم من formspree.io عشان الطلبات تتحفظ وتوصل على الإيميل.

## النشر
الموقع بيتنشر من فرع `main`، على GitHub Pages وعلى Cloudflare Pages.

إعدادات Cloudflare Pages (Workers & Pages ← Create ← Pages ← Connect to Git):
- Repository: `elfateh802/Core-Vision-Technologies`
- Production branch: `main`
- Framework preset: `None`
- Build command: فاضي
- Build output directory: `/`

أي push على `main` بيتنشر لوحده.
