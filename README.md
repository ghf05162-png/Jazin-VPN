# 💜 Jazin VPN

<p align="center">
  <img src="https://img.shields.io/badge/Cloudflare-Workers-F38020?style=for-the-badge&logo=cloudflare&logoColor=white" alt="Cloudflare Workers">
  <img src="https://img.shields.io/badge/Cloudflare-Warp-orange?style=for-the-badge&logo=cloudflare&logoColor=white" alt="Warp">
  <br>
  <img src="https://img.shields.io/badge/Protocol-VLESS-00ADD8?style=for-the-badge" alt="VLESS">
  <img src="https://img.shields.io/badge/Protocol-Trojan-00ADD8?style=for-the-badge" alt="Trojan">
  <br>
  <img src="https://img.shields.io/badge/Fragment-Anti--Filtering-blueviolet?style=for-the-badge" alt="Fragment">
</p>

<p align="center">
  <strong>🇬🇧 English</strong> &nbsp;•&nbsp;
  <a href="#فارسی">🇮🇷 فارسی</a> &nbsp;•&nbsp;
  <a href="#русский">🇷🇺 Русский</a> &nbsp;•&nbsp;
  <a href="#中文">🇨🇳 中文</a>
</p>

A free, self-hosted VLESS / Trojan proxy panel designed for Cloudflare Workers.

---

## 💜 Jazin VPN

Jazin VPN is a Cloudflare Workers based VLESS / Trojan proxy panel.

It provides a simple web interface for managing VPN configuration and related settings.

### ✨ Features

- ⚡ Cloudflare Workers support
- 🔐 VLESS protocol
- 🔐 Trojan protocol
- 🌐 Warp / Warp Pro support
- 🔗 Subscription links
- ⚙️ UUID management
- 🔑 Password management
- 🌍 DNS and routing settings
- 🧩 Fragment and noise settings
- 🖥️ Web-based management panel
- 🔒 Optional panel password
- 📱 Mobile-friendly interface

---

## 🚀 Deploy

1. Create a new Cloudflare Worker.
2. Copy the contents of `worker.js` into the Worker editor.
3. Create a new Workers KV namespace.
4. Open your Worker settings.
5. Go to **Settings → Bindings**.
6. Add a **KV Namespace** binding.
7. Set the variable name to:

`kv`

8. Deploy the Worker.
9. Open your Worker address and add:

`/panel`

Example:

`https://your-worker.workers.dev/panel`

The Jazin VPN panel should then be available.

---

## ⚠️ Important

The KV binding variable name must be exactly:

`kv`

Without the correct KV binding, the Worker may not work correctly.

---

## 🔐 Security

- Use a strong panel password.
- Do not share your panel URL publicly.
- Change default VPN credentials before sharing subscription links.
- Keep your configuration information private.

---

## 🇮🇷 فارسی

<a id="فارسی"></a>

# 💜 پنل Jazin VPN

پنل پروکسی VLESS و Trojan که برای اجرا روی Cloudflare Workers طراحی شده است.

### ✨ امکانات

- ⚡ اجرا روی Cloudflare Workers
- 🔐 پشتیبانی از VLESS
- 🔐 پشتیبانی از Trojan
- 🌐 پشتیبانی از Warp و Warp Pro
- 🔗 ساخت لینک Subscription
- ⚙️ مدیریت UUID
- 🔑 مدیریت رمز عبور
- 🌍 تنظیم DNS و Routing
- 🧩 تنظیمات Fragment و Noise
- 🖥️ پنل مدیریت وب
- 🔒 امکان تعیین رمز برای پنل
- 📱 سازگار با موبایل

### 🚀 نصب

1. یک Cloudflare Worker جدید بسازید.
2. محتوای فایل `worker.js` را داخل Worker قرار دهید.
3. یک Workers KV بسازید.
4. وارد تنظیمات Worker شوید.
5. به قسمت **Settings → Bindings** بروید.
6. یک **KV Namespace** اضافه کنید.
7. نام متغیر را دقیقاً این قرار دهید:

`kv`

8. Worker را Deploy کنید.
9. در انتهای آدرس Worker عبارت زیر را اضافه کنید:

`/panel`

مثال:

`https://your-worker.workers.dev/panel`

---

## 🔐 نکات امنیتی

- برای پنل یک رمز قوی انتخاب کنید.
- آدرس پنل را عمومی منتشر نکنید.
- قبل از استفاده، اطلاعات پیش‌فرض اتصال را تغییر دهید.
- لینک‌های Subscription خود را خصوصی نگه دارید.

---

## 🇷🇺 Русский

<a id="русский"></a>

# 💜 Jazin VPN

Панель VLESS / Trojan для работы на Cloudflare Workers.

Поддерживаются управление настройками, UUID, паролями, DNS, маршрутизацией, подписками и настройками панели.

---

## 🇨🇳 中文

<a id="中文"></a>

# 💜 Jazin VPN

基于 Cloudflare Workers 的 VLESS / Trojan 管理面板。

支持 UUID、密码、DNS、路由、订阅以及面板安全设置等功能。

---

## ❤️ Jazin VPN

Made with ❤️ for Jazin VPN.
