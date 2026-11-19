# Core Vision Technologies

موقع شركة كور فيجن تكنولوجيز: كاميرات مراقبة، شبكات، وبرامج للمحلات والشركات.

## الإعدادات
في آخر ملف `index.html` جوه `<script>`:
- `WA_NUMBER`: رقم الواتساب اللي بيستقبل الطلبات.
- `FORMSPREE_ID`: كود الفورم من formspree.io عشان الطلبات تتحفظ وتوصل على الإيميل.

## النشر
الموقع بيتنشر من فرع `main`، على GitHub Pages وعلى Cloudflare Pages.

النشر على Cloudflare بيتم من GitHub Actions (`.github/workflows/cloudflare-pages.yml`)، ومشروع Cloudflare اسمه `core-vision`.
محتاج 2 Secrets في الريبو (Settings ← Secrets and variables ← Actions):
- `CLOUDFLARE_API_TOKEN`: توكن من Cloudflare بقالب "Edit Cloudflare Workers" أو صلاحية Cloudflare Pages: Edit.
- `CLOUDFLARE_ACCOUNT_ID`: رقم الحساب من الداشبورد.

أي push على `main` بيتنشر لوحده.
