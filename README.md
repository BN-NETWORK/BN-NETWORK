# 🌐 BN NETWORK

**BN NETWORK** is a Windows network and DNS management utility designed to help users monitor, diagnose, and optimize their network connection.

The project focuses on DNS management, latency testing, network diagnostics, connection stability, and providing a simple and modern interface for everyday users and gamers.

---

## ✨ Features

### 🏠 Network Dashboard
- Real-time connection status
- Active DNS server detection
- Network latency overview
- Public IP detection
- Quick access to network tools

### 🌐 DNS Manager
- Large built-in DNS server database
- DNS latency testing
- Average latency calculation
- Jitter measurement
- Packet loss detection
- Multi-threaded DNS testing
- Automatic DNS ranking
- Multiple scoring profiles for different use cases
- Gaming-oriented DNS evaluation
- Streaming-oriented DNS evaluation
- General browsing profile
- Custom DNS profile
- Automatic best DNS recommendation
- Apply DNS to selected network adapter
- Apply DNS to multiple adapters
- Restore DNS settings to DHCP
- Pin favorite DNS servers
- Add custom DNS servers manually
- Bulk DNS import
- Clipboard-based DNS detection
- Duplicate DNS detection
- Multi-selection and bulk deletion
- DNS search
- DNS list export

### 📡 Network Diagnostics
- Multi-server ping testing
- Google DNS testing
- Cloudflare testing
- Cloudflare Alternate testing
- Quad9 testing
- Multiple ping samples with average result
- Color-coded network status
- Public IP detection and clipboard copy
- DNS cache cleanup
- Complete Windows network reset

### 🛠 Network Reset
BN NETWORK can perform a complete network reset using Windows networking commands:

- `ipconfig /release`
- `ipconfig /renew`
- `ipconfig /flushdns`
- `netsh int ip reset`
- `netsh winsock reset`

### 📊 Monitoring & Logging
- Live operation logs
- Color-coded status messages
- Detailed error reporting
- Error log access
- Log clearing
- Operation timeout handling
- Protection against repeated/spam button presses

### 🎨 User Interface
- Modern dark-blue interface
- GUI-based navigation
- Dedicated DNS Manager
- Tooltips for major controls
- Responsive operation handling
- Administrator elevation through application manifest

---

## ⚡ Performance

BN NETWORK uses multi-threaded operations for DNS and network testing.

DNS testing can dynamically adjust the amount of concurrent work according to the system's available CPU resources, allowing faster systems to process larger DNS lists without unnecessarily stressing weaker systems.

Network operations are also designed to avoid freezing the user interface during long-running operations.

---

## 🎮 Designed For

BN NETWORK can be useful for:

- 🎮 Gamers
- 🌐 Everyday internet users
- 🛠 PC technicians
- 📡 Network troubleshooting
- 🖥 Windows users
- 🔧 Users who frequently change DNS servers

---

## 🚀 Roadmap

The project is actively being developed.

Planned and upcoming features include:

- [ ] Full IPv6 support
- [ ] URL-based DNS testing
- [ ] More advanced network diagnostics
- [ ] Improved GUI and UX
- [ ] Background DNS monitoring
- [ ] Automatic DNS failover
- [ ] Cloud-based DNS monitoring
- [ ] Additional DNS servers and regional testing
- [ ] Further performance optimizations

---

## 🖥️ Platform

**Windows**

BN NETWORK is currently developed for Windows environments and uses Windows networking functionality for several of its diagnostic and configuration features.

---

## 🧰 Technology

- C#
- .NET
- Windows Forms
- Windows Networking APIs / Commands
- Multi-threaded network operations

---

## 👨‍💻 Development Team

### Backend & Core Development
**Mohammad Mahdi Zolmajdi**

Responsible for:
- Backend and core application logic
- Network functionality
- DNS management logic
- Testing and diagnostics
- Performance and stability
- Application architecture

### Frontend & UI
**Mohammad Reza Ramezan Beigy**

Responsible for:
- Frontend
- User interface
- Visual design
- Application icon and graphical elements
- UI/UX improvements

---

## 📌 Project Status

BN NETWORK is an actively developed project.

New versions are released as features are implemented, tested, optimized, and bugs are fixed.

The project is currently focused on improving stability, user experience, DNS testing accuracy, and network management capabilities.

---

# 🇮🇷 توضیحات فارسی

## 🌐 BN NETWORK چیست؟

**BN NETWORK** یک ابزار مدیریت، بررسی و عیب‌یابی شبکه و DNS برای ویندوز است که با هدف ساده‌تر کردن مدیریت اتصال اینترنت، بررسی وضعیت شبکه و پیدا کردن DNS مناسب برای کاربر ساخته شده است.

تمرکز اصلی برنامه روی مدیریت DNS، بررسی پینگ، جیتر، Packet Loss، عیب‌یابی شبکه و ارائه یک محیط کاربری ساده و مدرن است.

---

## ✨ قابلیت‌ها

### 🏠 داشبورد شبکه
- نمایش وضعیت اتصال
- نمایش DNS فعال
- نمایش وضعیت Ping
- دریافت IP عمومی
- دسترسی سریع به ابزارهای شبکه

### 🌐 مدیریت DNS
- لیست آماده از DNSهای مختلف
- تست پینگ DNSها
- محاسبه میانگین پینگ
- بررسی Jitter
- بررسی Packet Loss
- تست چندنخی DNSها
- رتبه‌بندی خودکار DNSها
- سیستم امتیازدهی برای کاربردهای مختلف
- پروفایل مخصوص Gaming
- پروفایل مخصوص Streaming
- پروفایل Web Browsing
- پروفایل عمومی
- امکان اضافه کردن DNS اختصاصی
- انتخاب خودکار بهترین DNS
- اعمال DNS روی کارت شبکه انتخاب‌شده
- امکان اعمال DNS روی چند کارت شبکه
- بازگردانی DNS به حالت DHCP
- Pin کردن DNSهای مورد علاقه
- اضافه کردن دستی DNS
- اضافه کردن گروهی DNS
- تشخیص DNS از Clipboard
- تشخیص موارد تکراری
- حذف گروهی DNSها
- جستجو در لیست DNSها
- خروجی گرفتن از لیست DNSها

### 📡 ابزارهای شبکه
- تست همزمان چند سرور
- تست Google
- تست Cloudflare
- تست Cloudflare Alternate
- تست Quad9
- اجرای چندباره تست و محاسبه میانگین
- نمایش رنگی وضعیت شبکه
- بررسی و کپی IP عمومی
- پاکسازی DNS Cache
- بازنشانی کامل تنظیمات شبکه

### 🛠 بازنشانی شبکه

برنامه امکان اجرای دستورات اصلی بازنشانی شبکه ویندوز را فراهم می‌کند:

- `ipconfig /release`
- `ipconfig /renew`
- `ipconfig /flushdns`
- `netsh int ip reset`
- `netsh winsock reset`

### 📊 لاگ و گزارش خطا
- لاگ زنده عملیات
- نمایش رنگی وضعیت‌ها
- گزارش دقیق خطا
- دسترسی سریع به پوشه گزارش خطا
- پاک کردن لاگ
- مدیریت Timeout عملیات
- جلوگیری از ایجاد مشکل در اثر کلیک‌های پشت‌سرهم

### 🎨 رابط کاربری
- تم Dark Blue
- رابط کاربری مدرن
- بخش‌بندی جداگانه ابزارها
- DNS Manager اختصاصی
- ToolTip برای دکمه‌ها
- مدیریت مناسب عملیات طولانی
- اجرای خودکار با دسترسی Administrator

---

## 🎮 BN NETWORK برای چه کسانی ساخته شده؟

این برنامه می‌تواند برای موارد زیر کاربرد داشته باشد:

- 🎮 گیمرها
- 🌐 کاربران عادی اینترنت
- 🛠 تکنسین‌های کامپیوتر
- 📡 عیب‌یابی شبکه
- 🖥 کاربران ویندوز
- 🔧 افرادی که مرتب DNS خود را تغییر می‌دهند

---

## 🚀 مسیر توسعه

پروژه همچنان در حال توسعه است.

برخی قابلیت‌های در دست توسعه:

- [ ] پشتیبانی کامل از IPv6
- [ ] تست DNS بر اساس URL
- [ ] ابزارهای پیشرفته‌تر عیب‌یابی شبکه
- [ ] بهبود بیشتر رابط کاربری
- [ ] مانیتورینگ DNS در پس‌زمینه
- [ ] سوییچ خودکار در صورت خراب شدن DNS
- [ ] مانیتورینگ Cloud
- [ ] اضافه شدن DNSهای بیشتر
- [ ] بهینه‌سازی بیشتر عملکرد برنامه

---

## 🖥️ سیستم‌عامل

**Windows**

BN NETWORK در حال حاضر برای محیط ویندوز توسعه داده شده و برای برخی قابلیت‌های مدیریت شبکه از امکانات و دستورات داخلی Windows استفاده می‌کند.

---

## 🧰 تکنولوژی

- C#
- .NET
- Windows Forms
- Windows Networking
- Multi-threaded Network Operations

---

# 👨‍💻 تیم توسعه

## Backend & Core Development

**Mohammad Mahdi Zolmajdi**

مسئول:
- توسعه Backend و منطق اصلی برنامه
- قابلیت‌های شبکه
- منطق مدیریت DNS
- سیستم تست و عیب‌یابی
- بهینه‌سازی و پایداری
- معماری و توسعه اصلی برنامه

## Frontend & UI

**Mohammad Reza Ramezan Beigy**

مسئول:
- Frontend
- رابط کاربری
- طراحی ظاهری
- عناصر گرافیکی و آیکون برنامه
- بهبود UI/UX

---

## 📌 وضعیت پروژه

BN NETWORK یک پروژه فعال و در حال توسعه است.

نسخه‌های جدید برنامه با اضافه شدن قابلیت‌های جدید، رفع باگ، بهینه‌سازی عملکرد و بهبود تجربه کاربری منتشر می‌شوند.

هدف فعلی پروژه، افزایش پایداری، بهبود رابط کاربری، دقیق‌تر شدن تست DNS و ارائه ابزارهای کامل‌تر برای مدیریت شبکه است.

---

### ⭐ If BN NETWORK is useful to you, consider giving the project a Star.

### 🇮🇷 اگر BN NETWORK براتون مفید بود، با یک ⭐ از پروژه حمایت کنید.
