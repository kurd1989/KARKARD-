ساخت APK
1) Android Studio را نصب کنید: https://developer.android.com/studio
2) File > Open و پوشهٔ KarkardApp را انتخاب کنید و صبر کنید Sync تمام شود (اینترنت لازم است).
3) منوی Build > Build Bundle(s) / APK(s) > Build APK(s)
4) پس از پایان، روی Locate بزنید؛ فایل app-debug.apk در app/build/outputs/apk/debug ساخته شده است.
5) فایل را به گوشی منتقل و نصب کنید (اجازهٔ نصب از منابع ناشناس لازم است).
محتوای برنامه: app/src/main/assets/index.html

ساخت با GitHub (بدون Android Studio)
1) در github.com یک مخزن (Repository) جدید بسازید.
2) محتویات همین پوشه (نه خود پوشه) را در مخزن آپلود کنید؛ پوشهٔ .github هم باید باشد.
3) به تب Actions بروید؛ ساخت به‌طور خودکار شروع می‌شود (یا Run workflow را بزنید).
4) بعد از سبز شدن، وارد آن اجرا شوید و از بخش Artifacts فایل karkard-apk را دانلود کنید؛ داخل آن app-debug.apk است.
