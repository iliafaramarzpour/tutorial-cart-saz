# کارت ساز | Cart-Saz

<div dir="rtl">

## 📖 درباره پروژه

این پروژه یک وب‌سایت آموزشی برای کارآموزان برنامه‌نویسی است که به منظور یادگیری اصولی مفاهیم پایه‌ای طراحی وب طراحی شده است. هدف این پروژه آشنایی دانشجویان و علاقه‌مندان با ساختار استاندارد HTML، نوشتن CSS تمیز و مدیریت منابع در یک پروژه واقعی است.

## 🎯 اهداف آموزشی

این پروژه به شما کمک می‌کند تا مفاهیم زیر را یاد بگیرید:

- ✅ ساختار صحیح و معنایی HTML5
- ✅ سازماندهی و مدیریت فایل‌های CSS
- ✅ استفاده از Flexbox برای چیدمان صفحات
- ✅ طراحی واکنش‌گرا (Responsive Design)
- ✅ کار با فونت‌های فارسی
- ✅ مدیریت رنگ‌ها و متغیرها در CSS
- ✅ سازماندهی پروژه به صورت حرفه‌ای
- ✅ استفاده صحیح از SVG در وب

## 📁 ساختار پروژه

```
cart-saz/
├── src/
│   ├── index.html              # صفحه اصلی
│   ├── faq.html                # صفحه سوالات متداول
│   ├── js/
│   │   └── index.js            # فایل جاوااسکریپت اصلی
│   ├── styles/
│   │   ├── main.css            # استایل اصلی و import ها
│   │   ├── base.css            # استایل‌های پایه
│   │   ├── layout.css          # استایل‌های چیدمان
│   │   ├── utils.css           # کلاس‌های کمکی
│   │   ├── components/         # استایل کامپوننت‌ها
│   │   │   └── sign-in.css
│   │   ├── pages/              # استایل صفحات
│   │   │   ├── index.css
│   │   │   └── faq.css
│   │   └── partial/            # استایل‌های جزئی
│   │       └── layout.css
│   └── public/
│       ├── fonts/              # فونت‌های وب
│       │   └── Yekan.*
│       └── assets/             # تصاویر و ویدیوها
│           ├── images/
│           └── videos/
└── README.md
```

## 🚀 شروع کار

### پیش‌نیازها

برای کار با این پروژه فقط به یک مرورگر وب نیاز دارید. پیشنهاد می‌شود از مرورگرهای زیر استفاده کنید:

- Google Chrome
- Firefox
- Microsoft Edge
- Safari

### نصب و اجرا

1. پروژه را دانلود یا کلون کنید:

```bash
git clone https://github.com/your-username/cart-saz.git
cd cart-saz
```

2. فایل `index.html` را در مسیر `src/` با مرورگر باز کنید.

یا می‌توانید از یک Live Server استفاده کنید:

```bash
# اگر VS Code استفاده می‌کنید، افزونه Live Server را نصب کنید
# سپس روی فایل HTML راست کلیک کرده و "Open with Live Server" را انتخاب کنید
```

## 📚 مفاهیم کلیدی پوشش داده شده

### 1. ساختار HTML معنایی

در این پروژه با استفاده صحیح از تگ‌های معنایی HTML5 آشنا می‌شوید:

- `<header>` - برای هدر صفحه
- `<nav>` - برای منوی ناوبری
- `<main>` - برای محتوای اصلی
- `<section>` - برای بخش‌های مختلف
- `<footer>` - برای فوتر صفحه

### 2. سازماندهی CSS

پروژه از یک ساختار مدولار برای CSS استفاده می‌کند:

- **base.css**: تنظیمات پایه مثل reset، متغیرها، تایپوگرافی
- **layout.css**: چیدمان کلی صفحات
- **components/**: استایل کامپوننت‌های قابل استفاده مجدد
- **pages/**: استایل‌های خاص هر صفحه
- **utils.css**: کلاس‌های کمکی مثل flex, spacing

### 3. Flexbox

یادگیری استفاده از Flexbox برای چیدمان عناصر:

```css
.flex {
  display: flex;
}

.flex-center {
  align-items: center;
}

.flex-between {
  justify-content: space-between;
}
```

### 4. طراحی واکنش‌گرا

استفاده از Media Queries برای سازگاری با دستگاه‌های مختلف:

```css
@media (max-width: 768px) {
  /* استایل‌های موبایل */
}
```

## 🎨 راهنمای سبک

### رنگ‌ها

پروژه از یک پالت رنگی مشخص استفاده می‌کند:

- آبی اصلی: `#0182FE`
- خاکستری تیره: `#171F26`
- سفید: `#FFFFFF`

### فونت

- فونت اصلی: Yekan (فونت فارسی)

### فاصله‌گذاری

از یک سیستم فاصله‌گذاری ثابت استفاده کنید (8px, 16px, 24px, 32px, ...)

## 💡 نکات آموزشی

### برای مبتدیان

1. **شروع با HTML**: ابتدا ساختار HTML را بفهمید
2. **سپس CSS**: بعد به سراغ استایل‌دهی بروید
3. **تمرین کنید**: سعی کنید صفحات جدید اضافه کنید
4. **کد بخوانید**: کدهای موجود را مطالعه و تحلیل کنید

### تمرین‌های پیشنهادی

1. یک صفحه جدید به پروژه اضافه کنید (مثلاً صفحه "تماس با ما")
2. یک کامپوننت جدید طراحی کنید (مثلاً کارت محصول)
3. یک منوی موبایل (Hamburger Menu) اضافه کنید
4. فرم ثبت‌نام یا ورود بسازید
5. انیمیشن‌های ساده با CSS اضافه کنید

## 🔧 ابزارهای توصیه شده

- **ویرایشگر کد**: VS Code
- **افزونه‌های VS Code**:
  - Live Server
  - Prettier
  - HTML CSS Support
  - Auto Rename Tag
- **مرورگر**: Chrome DevTools برای دیباگ

## 📖 منابع آموزشی

برای یادگیری بیشتر:

- [MDN Web Docs](https://developer.mozilla.org/fa/) - مرجع کامل HTML و CSS
- [CSS-Tricks](https://css-tricks.com/) - ترفندها و تکنیک‌های CSS
- [Flexbox Froggy](https://flexboxfroggy.com/) - بازی یادگیری Flexbox
- [Grid Garden](https://cssgridgarden.com/) - بازی یادگیری CSS Grid

## 🤝 مشارکت

این یک پروژه آموزشی است. برای بهبود آن:

1. پروژه را Fork کنید
2. تغییرات خود را اعمال کنید
3. Pull Request ارسال کنید

## 📝 لیست کارها

- [ ] اضافه کردن صفحه تماس با ما
- [ ] پیاده‌سازی منوی موبایل
- [ ] اضافه کردن انیمیشن‌ها
- [ ] بهبود دسترس‌پذیری (Accessibility)
- [ ] اضافه کردن Dark Mode
- [ ] پیاده‌سازی فرم‌های تعاملی

## 📄 مجوز

این پروژه صرفاً برای اهداف آموزشی است.

## 💬 سوالات؟

اگر سوالی دارید یا به کمک نیاز دارید، می‌توانید Issue باز کنید.

---

**موفق باشید! 🚀**

</div>

---

<div dir="ltr">

## 📖 About The Project

This is an educational web project designed for programming interns to learn fundamental web design concepts in a professional way. The goal is to help students and enthusiasts understand standard HTML structure, write clean CSS, and manage resources in a real-world project.

## 🎯 Learning Objectives

This project will help you learn:

- ✅ Proper and semantic HTML5 structure
- ✅ Organizing and managing CSS files
- ✅ Using Flexbox for page layouts
- ✅ Responsive Web Design
- ✅ Working with Persian fonts
- ✅ Managing colors and CSS variables
- ✅ Professional project organization
- ✅ Proper use of SVG in web

## 📁 Project Structure

```
cart-saz/
├── src/
│   ├── index.html              # Main page
│   ├── faq.html                # FAQ page
│   ├── js/
│   │   └── index.js            # Main JavaScript file
│   ├── styles/
│   │   ├── main.css            # Main stylesheet with imports
│   │   ├── base.css            # Base styles
│   │   ├── layout.css          # Layout styles
│   │   ├── utils.css           # Utility classes
│   │   ├── components/         # Component styles
│   │   │   └── sign-in.css
│   │   ├── pages/              # Page-specific styles
│   │   │   ├── index.css
│   │   │   └── faq.css
│   │   └── partial/            # Partial styles
│   │       └── layout.css
│   └── public/
│       ├── fonts/              # Web fonts
│       │   └── Yekan.*
│       └── assets/             # Images and videos
│           ├── images/
│           └── videos/
└── README.md
```

## 🚀 Getting Started

### Prerequisites

You only need a web browser to work with this project. We recommend:

- Google Chrome
- Firefox
- Microsoft Edge
- Safari

### Installation & Running

1. Download or clone the project:

```bash
git clone https://github.com/your-username/cart-saz.git
cd cart-saz
```

2. Open `index.html` from the `src/` directory in your browser.

Or use a Live Server:

```bash
# If using VS Code, install the Live Server extension
# Then right-click on the HTML file and select "Open with Live Server"
```

## 📚 Key Concepts Covered

### 1. Semantic HTML Structure

Learn proper use of HTML5 semantic tags:

- `<header>` - For page header
- `<nav>` - For navigation menu
- `<main>` - For main content
- `<section>` - For different sections
- `<footer>` - For page footer

### 2. CSS Organization

The project uses a modular CSS structure:

- **base.css**: Base settings like reset, variables, typography
- **layout.css**: Overall page layouts
- **components/**: Reusable component styles
- **pages/**: Page-specific styles
- **utils.css**: Utility classes like flex, spacing

### 3. Flexbox

Learn to use Flexbox for element layout:

```css
.flex {
  display: flex;
}

.flex-center {
  align-items: center;
}

.flex-between {
  justify-content: space-between;
}
```

### 4. Responsive Design

Using Media Queries for device compatibility:

```css
@media (max-width: 768px) {
  /* Mobile styles */
}
```

## 🎨 Style Guide

### Colors

The project uses a defined color palette:

- Primary Blue: `#0182FE`
- Dark Gray: `#171F26`
- White: `#FFFFFF`

### Font

- Primary Font: Yekan (Persian font)

### Spacing

Use a consistent spacing system (8px, 16px, 24px, 32px, ...)

## 💡 Learning Tips

### For Beginners

1. **Start with HTML**: First understand the HTML structure
2. **Then CSS**: Move on to styling
3. **Practice**: Try adding new pages
4. **Read Code**: Study and analyze existing code

### Suggested Exercises

1. Add a new page to the project (e.g., "Contact Us")
2. Design a new component (e.g., product card)
3. Add a mobile hamburger menu
4. Create a sign-up or login form
5. Add simple CSS animations

## 🔧 Recommended Tools

- **Code Editor**: VS Code
- **VS Code Extensions**:
  - Live Server
  - Prettier
  - HTML CSS Support
  - Auto Rename Tag
- **Browser**: Chrome DevTools for debugging

## 📖 Learning Resources

For further learning:

- [MDN Web Docs](https://developer.mozilla.org/) - Complete HTML & CSS reference
- [CSS-Tricks](https://css-tricks.com/) - CSS tips and techniques
- [Flexbox Froggy](https://flexboxfroggy.com/) - Learn Flexbox through a game
- [Grid Garden](https://cssgridgarden.com/) - Learn CSS Grid through a game

## 🤝 Contributing

This is an educational project. To improve it:

1. Fork the project
2. Make your changes
3. Submit a Pull Request

## 📝 TODO

- [ ] Add Contact Us page
- [ ] Implement mobile menu
- [ ] Add animations
- [ ] Improve accessibility
- [ ] Add Dark Mode
- [ ] Implement interactive forms

## 📄 License

This project is for educational purposes only.

## 💬 Questions?

If you have questions or need help, feel free to open an Issue.

---

**Good luck! 🚀**

</div>
