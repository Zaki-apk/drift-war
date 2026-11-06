ساحل الدرفت: حرب (PWA)

1) أنشئ مستودعاً جديداً على GitHub باسم drift-war وارفع كل محتويات هذا المجلد إليه.
2) Settings > Pages > Deploy from a branch > main > / (root).
3) الرابط سيكون: https://zaki-apk.github.io/drift-war/
4) افتحه على الهاتف وتأكد أنه يعمل وأن خيار "تثبيت التطبيق" يظهر.
5) ادخل pwabuilder.com وضع الرابط، ثم Package for stores > Android، واختر حزمة موقّعة.
6) لإخفاء شريط المتصفح داخل التطبيق: ضع assetlinks.json في الجذر https://zaki-apk.github.io/.well-known/assetlinks.json
   (أي في مستودع باسم zaki-apk.github.io، وليس داخل drift-war)، ويجب أن يحتوي ملف .nojekyll أو ما يعادله حتى يظهر المجلد المخفي.
