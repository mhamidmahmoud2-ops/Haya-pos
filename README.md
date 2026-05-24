# هيا POS - Android APK
## مشروع Android يفتح نظام هيا ERP مع دعم كامل لـ Web Bluetooth

---

## ⚡ البناء عبر GitHub Actions (أسهل طريقة - مجاناً)

### الخطوات:

1. افتح **github.com** وسجّل دخول (أو أنشئ حساب مجاني)

2. اضغط **"New repository"** واسمه `haya-pos`

3. ارفع كل الملفات هذي على الـ repository

4. اذهب لـ **Actions** → ستجد workflow جاهز
   اضغط **"Run workflow"**

5. بعد 3-5 دقائق → اضغط على الـ build → حمّل الـ APK من **Artifacts**

6. نقّل الـ APK للـ Sunmi وثبّته ✅

---

## 🔑 الفرق عن APK السابق (PWABuilder):

| | PWABuilder | هذا المشروع |
|--|--|--|
| Web Bluetooth | ❌ محجوب | ✅ مفعّل |
| صلاحيات BT | ❌ ناقصة | ✅ كاملة |
| شاشة كاملة | ❌ | ✅ |
| شاشة لا تنطفئ | ❌ | ✅ |
| زر رجوع آمن | ❌ | ✅ |

---

## 📁 هيكل المشروع

```
HayaPOS/
├── app/
│   ├── src/main/
│   │   ├── java/com/haya/pos/
│   │   │   └── MainActivity.java     ← الكود الرئيسي
│   │   ├── res/
│   │   │   ├── layout/activity_main.xml
│   │   │   ├── values/strings.xml
│   │   │   ├── values/styles.xml
│   │   │   └── mipmap-*/ic_launcher.png
│   │   └── AndroidManifest.xml
│   └── build.gradle
├── build.gradle
├── settings.gradle
└── .github/workflows/build.yml
```

---

## 🖨️ بعد التثبيت - طريقة الطباعة:

1. شغّل الطابعة البلوتوث
2. من الـ Sunmi: Settings → Bluetooth → اقرن الطابعة
3. افتح تطبيق "هيا وبلقيس"
4. اعمل فاتورة → اضغط "🖨️ طباعة بلوتوث"
5. اختر الطابعة من القائمة → تطبع ✅
