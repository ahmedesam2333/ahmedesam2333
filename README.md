<div align="center">
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&pause=1000&color=22C55E&center=true&vWidth=700&lines=Hey+%F0%9F%91%8B%2C+I'm+Ahmed+Essam;Node.js+Backend+Engineer" alt="Typing SVG" />
</div>

<p align="center">
  <a href="https://linkedin.com/in/ahmed-essam-33b989221"><img src="https://img.shields.io/badge/LinkedIn-Ahmed_Essam-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:ahmedezsam@gmail.com"><img src="https://img.shields.io/badge/Email-ahmedezsam@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://drive.google.com/drive/folders/13tRC5kd76bMTi4Qe91tMb7tCnWYR4GPv?usp=sharing"><img src="https://img.shields.io/badge/Resume-View_PDF-1abc9c?style=for-the-badge&logo=google-drive&logoColor=white" /></a>
</p>

---

## 👨‍💻 About Me

I'm a **Node.js Backend Engineer** based in Cairo, Egypt, passionate about building **secure**, **scalable**, and **production-ready REST APIs**.

- 🚀 Specializing in **Node.js / Express.js** backend systems with **MongoDB**
- 📚 Currently enrolled in a **9-month Full Stack intensive** at **ITI (Information Technology Institute)**
- 🎓 B.Sc. in **Computer Science & AI** — Helwan University | GPA: **3.6/4.0 — Excellent with Honors**

---

## 🚀 Projects

### 🌐 [Social Media App — REST API Backend](https://github.com/ahmedesam2333/Social-Media-REST-API-) &nbsp;![Status](https://img.shields.io/badge/Status-In_Progress-f59e0b?style=for-the-badge)

> A secure, scalable REST API backend for a modern social media platform — built fully in TypeScript for end-to-end type safety, from request validation to database models.

**Stack:** `TypeScript` · `Node.js` · `Express.js` · `MongoDB` · `Mongoose` · `JWT` · `Google OAuth` · `Bcrypt` · `CryptoJS (AES)` · `Zod` · `Nodemailer` · `Multer` · `Cloudinary` · `Helmet` · `Rate Limiting` · `nanoid` · `AWS EC2` · `Nginx` · `PM2`

Fully typed social media backend with JWT access & refresh token pairs, per-token JTI blacklist revocation, Google OAuth unified signup/login, OTP email verification (bcrypt-hashed, 2-min expiry), AES-encrypted phone numbers at rest, Cloudinary profile & cover image uploads, soft-delete + restore across users, and an admin control layer — all behind centralized Zod validation schemas and a global async error handler. Modular architecture built to scale as new social features are added.

---

### 🕵️ [Sarahaa — Anonymous Messaging App Backend](https://github.com/ahmedesam2333/Sarahaa-App) &nbsp;![Status](https://img.shields.io/badge/Status-Completed-22c55e?style=for-the-badge) &nbsp;![Deployed](https://img.shields.io/badge/Deployed-AWS_EC2-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)

> A secure, scalable REST API backend for an anonymous social messaging platform. Users share a public link and receive messages from anyone — senders stay anonymous, recipients stay in control.

**Stack:** `Node.js` · `Express.js` · `MongoDB` · `Mongoose` · `JWT` · `Google OAuth` · `Bcrypt` · `CryptoJS (AES)` · `Nodemailer` · `Multer` · `Cloudinary` · `Helmet` · `Joi` · `Rate Limiting` · `nanoid` · `Chalk` · `AWS EC2` · `Nginx` · `PM2`

Full-featured anonymous messaging backend with JWT access & refresh token pairs, per-token JTI blacklist revocation, Google OAuth unified signup/login, OTP email verification (bcrypt-hashed, 2-min expiry), AES-encrypted phone numbers at rest, Cloudinary profile & cover image uploads, soft-delete + restore across users and messages, and an admin control layer for account management — all behind centralized Joi validation and a global async error handler. Deployed on AWS EC2 with Nginx as a reverse proxy and PM2 in cluster mode.

**Live:**

| Protocol | URL |
|---|---|
| HTTP | [ec2-32-192-124-255.compute-1.amazonaws.com](http://ec2-32-192-124-255.compute-1.amazonaws.com) |
| HTTPS | [bagged-feeble-handcraft.ngrok-free.dev](https://bagged-feeble-handcraft.ngrok-free.dev) |

> ⚠️ Hosted on AWS Free Tier — active until ~November 2026.

---

### 📝 [BlogWave — Blog Platform REST API Backend](https://github.com/ahmedesam2333/Blog-App) &nbsp;![Status](https://img.shields.io/badge/Status-Completed-22c55e?style=for-the-badge)

> A completed blog platform REST API using both MySQL2 (raw SQL) and Sequelize ORM — covering auth, user management, and blog CRUD with model associations, validators, paranoid soft delete, pagination, and eager loading.

**Stack:** `Node.js` · `Express.js` · `MySQL` · `MySQL2` · `Sequelize ORM` · `Bcrypt`

Two-phase architecture — MySQL2 raw SQL for auth (Phase 1), fully migrated to Sequelize ORM for user and blog management (Phase 2) with `paranoid` soft delete, `belongsTo`/`hasMany` associations with CASCADE, paginated search, eager loading, and Sequelize-aware centralized error handling.
