<div align="center">

# 📝 Modawanaty - مدونتي

### منصة تدوين احترافية مبنية بـ MERN Stack

[![React](https://img.shields.io/badge/React-18.0-61DAFB?logo=react&logoColor=white)](https://reactjs.org/)
[![Node.js](https://img.shields.io/badge/Node.js-20.0-339933?logo=node.js&logoColor=white)](https://nodejs.org/)
[![MongoDB](https://img.shields.io/badge/MongoDB-Latest-47A248?logo=mongodb&logoColor=white)](https://www.mongodb.com/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

**منصة تدوين حديثة وسهلة تسمح للمستخدمين بكتابة ومشاركة مقالاتهم بشكل احترافي**

[التجربة المباشرة](#-التثبيت-والتشغيل) • [المميزات](#-المميزات) • [التقنيات](#️-التقنيات-المستخدمة)

</div>

---

## ✨ المميزات

<table>
<tr>
<td width="50%">

### 🔐 أمان عالي
- تسجيل دخول آمن بـ JWT
- تشفير كلمات المرور بـ bcrypt
- حماية الـ Routes

</td>
<td width="50%">

### ✍️ محرر متقدم
- كتابة بتنسيق غني
- دعم Bold، Italic، Lists
- معاينة فورية

</td>
</tr>
<tr>
<td width="50%">

### 🎨 تصميم عصري
- واجهة احترافية بـ Tailwind
- متجاوب مع كل الشاشات
- Animations وتأثيرات حلوة

</td>
<td width="50%">

### ⚡ أداء سريع
- Pagination للمقالات
- بحث ذكي وسريع
- Toast Notifications

</td>
</tr>
</table>

---

## 🛠️ التقنيات المستخدمة

### Frontend
⚛️ React 18 - بناء الواجهة
🎨 Tailwind CSS - التصميم
🔄 React Router - التنقل
📝 React Quill - محرر النصوص
🔔 React Hot Toast - الإشعارات

text

### Backend
🟢 Node.js + Express - الخادم
🍃 MongoDB + Mongoose - قاعدة البيانات
🔐 JWT + bcrypt - الأمان

text

---

## 📦 التثبيت والتشغيل

### المتطلبات
> تأكد من تثبيت Node.js (v16+) و MongoDB

### 1️⃣ نسخ المشروع

git clone https://github.com/kareemelsaeed2004/modawanaty-blog.git
cd modawanaty-blog

text

### 2️⃣ إعداد Backend

cd backend
npm install

text

**إنشاء ملف `.env`:**
PORT=5000
MONGODB_URI=mongodb://localhost:27017/blog-platform
JWT_SECRET=your_super_secret_key_here

text

**تشغيل الخادم:**
npm run dev

text
✅ الخادم شغال على: `http://localhost:5000`

### 3️⃣ إعداد Frontend

**في terminal جديد:**
cd frontend
npm install
npm start

text
✅ التطبيق شغال على: `http://localhost:3000`

---

## 🎯 كيفية الاستخدام

### 🆕 إنشاء حساب جديد
1. افتح `http://localhost:3000`
2. اضغط **Get Started**
3. اكتب بياناتك (الاسم، الإيميل، الباسورد)
4. سجل دخول بالحساب الجديد ✅

### ✍️ كتابة مقال
1. اضغط **New Post** من الأعلى
2. اكتب عنوان المقال
3. استخدم المحرر لكتابة المحتوى (مع Bold، Lists، إلخ)
4. اضغط **Create Post** 🎉

### ✏️ تعديل أو حذف مقال
- افتح أي مقال إنت كاتبه
- هتلاقي أزرار **Edit** و **Delete**
- فقط صاحب المقال يقدر يعدل أو يمسح

### 🔍 البحث
- استخدم شريط البحث في الصفحة الرئيسية
- ابحث حسب العنوان أو المحتوى

---

## 📂 هيكل المشروع

blog-platform/
│
├── 📁 backend/
│ ├── 📁 models/
│ │ ├── User.js # موديل المستخدم
│ │ └── Post.js # موديل المقال
│ ├── 📁 routes/
│ │ ├── auth.js # API تسجيل الدخول
│ │ └── posts.js # API المقالات
│ ├── 📁 middleware/
│ │ └── auth.js # حماية الـ Routes
│ ├── .env # متغيرات البيئة
│ └── server.js # نقطة البداية
│
└── 📁 frontend/
├── 📁 src/
│ ├── 📁 components/ # المكونات
│ ├── 📁 pages/ # الصفحات
│ ├── 📁 context/ # Context API
│ └── App.js # التطبيق الرئيسي
└── 📁 public/

text

---

## 🔌 API Endpoints

### 🔐 Authentication
| Method | Endpoint | الوصف |
|--------|----------|-------|
| `POST` | `/api/auth/register` | تسجيل مستخدم جديد |
| `POST` | `/api/auth/login` | تسجيل دخول |

### 📝 Posts
| Method | Endpoint | الوصف | حماية |
|--------|----------|-------|-------|
| `GET` | `/api/posts` | جلب كل المقالات (مع بحث وpagination) | ❌ |
| `GET` | `/api/posts/:id` | جلب مقال واحد | ❌ |
| `POST` | `/api/posts` | إنشاء مقال جديد | ✅ |
| `PUT` | `/api/posts/:id` | تعديل مقال | ✅ |
| `DELETE` | `/api/posts/:id` | حذف مقال | ✅ |

---

## 👨‍💻 معلومات المطور

<table>
<tr>
<td align="center" width="100%">

### كريم السعيد محمد عبد العظيم

**Student ID:** 2210027  
**الجامعة:** الأكاديمية الدولية للهندسة وعلوم الإعلام  
**التخصص:** الوسائط المتعددة والإنترنت

📧 Email: kemooelsaeed@gmail.com

</td>
</tr>
</table>

---

## 🎓 Assignment Details

**Course:** MERN Stack Development  
**Assignment:** Full-Stack Blog Platform  
**Deadline:** Tuesday, 3 December 2025, 11:59 PM  
**Submitted by:** كريم السعيد محمد عبد العظيم (2210027)

### ✅ Requirements Completed

- [x] User registration and login with JWT authentication
- [x] Password hashing using bcrypt
- [x] Full CRUD operations for blog posts
- [x] Owner-only edit/delete control
- [x] Rich text editor (React Quill)
- [x] Responsive post listing with search
- [x] Pagination implementation
- [x] Protected routes (frontend & backend)
- [x] Loading states and error messages
- [x] Toast notifications
- [x] Clean, professional UI with Tailwind CSS

---

## 🚀 المميزات المستقبلية

- [ ] إضافة تعليقات على المقالات
- [ ] رفع صور للمقالات
- [ ] نظام الإعجابات (Likes)
- [ ] صفحة بروفايل للكاتب
- [ ] Categories للمقالات
- [ ] Dark Mode

---

## 🤝 المساهمة

لو عايز تساهم في المشروع:

1. Fork المشروع
2. أنشئ branch (`git checkout -b feature/amazing`)
3. Commit التغييرات (`git commit -m 'Add feature'`)
4. Push للـ branch (`git push origin feature/amazing`)
5. افتح Pull Request

---

## 📝 الترخيص

هذا المشروع مرخص تحت رخصة MIT

---

## 🙏 شكر وتقدير

- [React Documentation](https://reactjs.org/)
- [MongoDB Docs](https://docs.mongodb.com/)
- [Tailwind CSS](https://tailwindcss.com/)
- [React Quill](https://github.com/zenoamaro/react-quill)
- [React Hot Toast](https://react-hot-toast.com/)

---

<div align="center">

![MERN Stack](https://img.shields.io/badge/MERN-Stack-blue?style=for-the-badge)

---

**© 2025 Modawanaty - Kareem Elsaeed Mohamed Abdelazim**

الأكاديمية الدولية للهندسة وعلوم الإعلام

</div>