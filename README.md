# Kessetna

Kessetna is an offline-first Windows application for Tunisian shops. It brings sales, stock, customer credit, expenses, cash control and reports into one French or Arabic interface.

Official website: [kessetna.com](https://kessetna.com/fr/)

## Download

The latest published GitHub Release is **Kessetna 0.4.9** (October 2026). Always confirm the release notes and use a backup before updating business data.

[Download the latest Kessetna release for Windows](https://github.com/aymenkhaled/kessetna/releases/latest)

- Windows 10 or Windows 11, 64-bit
- French and Arabic with right-to-left support
- Works without an internet connection for normal local operations
- Business data remains on the shop computer

The Android companion is prepared separately with Kessetna assistance and does not replace the local Windows application.

Test new releases using a backup or non-critical catalogue before relying on them in daily business.

## Windows Installation

The installer is not yet signed by a recognized publisher. Windows may therefore show **Unknown publisher** even when the official file is intact.

1. Download only from this repository or the [official Kessetna website](https://kessetna.com/fr/).
2. Open `Kessetna-Setup.exe`.
3. If Windows displays a protection warning, select **More info**.
4. Confirm the filename is `Kessetna-Setup.exe`, then select **Run anyway**.

For assisted installation, contact Kessetna on [WhatsApp](https://wa.me/21626286045?text=Bonjour%2C%20je%20souhaite%20installer%20Kessetna.).

## Verify the Download

The release includes `Kessetna-Setup.exe.sha256.txt`. To verify the installer in PowerShell:

```powershell
Get-FileHash .\Kessetna-Setup.exe -Algorithm SHA256
```

The result must match the checksum published with the same GitHub Release.

## About This Repository

This is Kessetna's public product and download repository. Commercial application source code, private signing material, merchant databases and build systems are not published here.

Kessetna is not presented as certified accounting or fiscal software. Merchants remain responsible for their legal, tax and backup obligations.

---

## العربية

Kessetna تطبيق Windows يعمل دون إنترنت ومصمم للمحلات التونسية. يجمع البيع والمخزون وديون العملاء والمصاريف ومراقبة الصندوق والتقارير في واجهة عربية أو فرنسية.

الموقع الرسمي: [kessetna.com](https://kessetna.com/ar/)

[تنزيل آخر إصدار من Kessetna لـ Windows](https://github.com/aymenkhaled/kessetna/releases/latest)

- Windows 10 أو Windows 11 بنظام 64-bit
- واجهة عربية وفرنسية مع دعم اتجاه الكتابة من اليمين إلى اليسار
- تعمل العمليات المحلية العادية دون اتصال بالإنترنت
- تبقى بيانات المتجر على حاسوب التاجر

آخر إصدار منشور على GitHub هو **Kessetna 0.4.9**. احتفظ بنسخة احتياطية واختبر التحديث قبل الاعتماد عليه في العمل اليومي.

قد يعرض Windows عبارة **ناشر غير معروف** لأن النسخة غير موقعة بعد من ناشر معتمد. نزّل البرنامج من هذا المستودع أو من موقع Kessetna الرسمي فقط، وتأكد أن اسم الملف هو `Kessetna-Setup.exe`.

للمساعدة في التثبيت، تواصل مع Kessetna عبر [WhatsApp](https://wa.me/21626286045?text=Bonjour%2C%20je%20souhaite%20installer%20Kessetna.).
