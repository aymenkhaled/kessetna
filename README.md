# Kessetna

Kessetna is an offline-first Windows application for Tunisian shops. It brings sales, stock, customer credit, expenses, cash control and reports into one French or Arabic interface.

## Download

The current merchant-validation build is **Kessetna 0.4.0 beta 1**.

[Download Kessetna for Windows](https://github.com/aymenkhaled/kessetna/releases/download/v0.4.0-beta.1/Kessetna-Setup.exe)

- Windows 10 or Windows 11, 64-bit
- Approximately 210 MB
- French and Arabic with right-to-left support
- Works without an internet connection after installation
- Business data remains on the shop computer

This is a pilot release. Test it with a backup or non-critical catalogue before relying on it in daily business.

## Windows Installation

The pilot installer is not yet signed by a recognized publisher. Windows may therefore show **Unknown publisher** even when the official file is intact.

1. Download only from this repository or the official Kessetna website.
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

[تنزيل Kessetna لـ Windows](https://github.com/aymenkhaled/kessetna/releases/download/v0.4.0-beta.1/Kessetna-Setup.exe)

- Windows 10 أو Windows 11 بنظام 64-bit
- الحجم حوالي 210 MB
- واجهة عربية وفرنسية مع دعم اتجاه الكتابة من اليمين إلى اليسار
- تعمل دون اتصال بالإنترنت بعد التثبيت
- تبقى بيانات المتجر على حاسوب التاجر

هذه نسخة تجريبية مخصصة للتحقق مع التجار. اختبرها على نسخة احتياطية أو بيانات غير حساسة قبل اعتمادها في العمل اليومي.

قد يعرض Windows عبارة **ناشر غير معروف** لأن النسخة التجريبية غير موقعة بعد من ناشر معتمد. نزّل البرنامج من هذا المستودع أو من موقع Kessetna الرسمي فقط، وتأكد أن اسم الملف هو `Kessetna-Setup.exe`.

للمساعدة في التثبيت، تواصل مع Kessetna عبر [WhatsApp](https://wa.me/21626286045?text=Bonjour%2C%20je%20souhaite%20installer%20Kessetna.).
