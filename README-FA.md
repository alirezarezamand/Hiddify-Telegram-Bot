

<p align="center">
  <a href="https://github.com/B3H1Z/Hiddify-Telegram-Bot" target="_blank" rel="noopener noreferrer">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://github.com/B3H1Z/Hiddify-Telegram-Bot/blob/main/Screenshots/icon.png?raw=True">
      <img width="200" height="200" src="https://github.com/B3H1Z/Hiddify-Telegram-Bot/blob/main/Screenshots/icon.png?raw=True">
    </picture>
  </a>
</p>
<p align="center">
	<a href="./README.md">
	English
	</a>
	|
	<a href="./README-FA.md">
	فارسی
	</a>
<br>
  <a href="https://t.me/HidyBotGroup">گروه تلگرام</a>

</p>

<h1 align="center"/>هیدی بات</h1>

با استفاده از این ربات می‌توانید پنل هیدیفای خود را از طریق تلگرام مدیریت کنید.

بعضی از ویژگی‌ها عبارتند از:
-  مدیریت چند پنل
-  فروش کانفیگ
-  افزودن کاربران
-  حذف کاربران
-  ویرایش کاربران
-  نمایش لیست کاربران
-  جستجوی کاربران (بر اساس نام، تنظیمات، UUID)
-  نمایش اطلاعات کاربران (نام، ترافیک، تاریخ و غیره)
-  نمایش پیکربندی‌ها و لینک‌های اشتراک کاربر
-  دریافت پشتیبان از پنل شما
-  نمایش وضعیت سرور (رم، پردازنده، دیسک)
- چند زبانه (انگلیسی، فارسی)
- ربات کاربران

## نصب 
برای نصب ربات دستور زیر را اجرا کنید:
 
```bash
sudo bash -c "$(curl -Lfo- https://raw.githubusercontent.com/B3H1Z/Hiddify-Telegram-Bot/main/install.sh)"
```
<br>

## دستورات
 به‌روزرسانی ربات
```bash
cd /opt/Hiddify-Telegram-Bot/ && curl -fsSL -o /opt/Hiddify-Telegram-Bot/update.sh https://raw.githubusercontent.com/B3H1Z/Hiddify-Telegram-Bot/main/update.sh && chmod +x /opt/Hiddify-Telegram-Bot/update.sh && bash /opt/Hiddify-Telegram-Bot/update.sh
```
 راه‌اندازی مجدد ربات
```bash
cd /opt/Hiddify-Telegram-Bot/ && chmod +x restart.sh && ./restart.sh
```
 متوقف کردن ربات

```bash
pkill -9 -f hiddifyTelegramBot.py
```
 مشاهده لاگ های ربات
```bash
cat /opt/Hiddify-Telegram-Bot/Logs/hidyBot.log
```
 مشاهده و تغییر پیکربندی ربات
```bash
cd /opt/Hiddify-Telegram-Bot/ && python3 config.py && chmod +x restart.sh && ./restart.sh
```
 نصب مجدد ربات
```bash
cd /opt/ && rm -rf /opt/Hiddify-Telegram-Bot/ && sudo bash -c "$(curl -Lfo- https://raw.githubusercontent.com/B3H1Z/Hiddify-Telegram-Bot/main/install.sh)"
```
  حذف ربات
```bash
cd /opt/Hiddify-Telegram-Bot/ && chmod +x uninstall.sh && ./uninstall.sh
```
