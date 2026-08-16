# PDF Vault — Mobile + Render + Cloudflare R2

الرابط: `https://YOUR-DOMAIN/myvault`

التدفق: رابطك → كلمة السر → الخزنة → رفع PDF → R2 → تحميل/حذف.

Render:
Build = `pip install -r requirements.txt`
Start = `python -m app`

Environment Variables:
VAULT_SLUG, VAULT_PASSWORD, SESSION_SECRET, MAX_FILE_MB, COOKIE_SECURE,
R2_ENDPOINT, R2_ACCESS_KEY_ID, R2_SECRET_ACCESS_KEY, R2_BUCKET

لا ترفع `.env` أو مفاتيح R2 إلى GitHub.
