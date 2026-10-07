# Projects

## ⏱️ Time Tracking Web Application

**GitHub:** https://github.com/Pbi-with-love/Time_Tracking

### Technologies

`React` · `TailwindCSS` · `JavaScript (ES6+)` · `Node.js` · `Express.js` · `MongoDB` · `Redis` · `RESTful API` · `JWT` · `Bcrypt`

### Highlights

* Designed and implemented **30+ RESTful APIs** to record and analyze user activity data for real-time tracking and reporting.
* Implemented **Redis caching** for frequently accessed data, OTPs, and temporary user information, reducing database load and improving response time.
* Used **JWT and bcrypt** to securely hash and verify passwords, managed token lifecycle with cookies, and integrated **Nodemailer** for OTP-based email verification.
* **Modularized and implemented 20+ React components** using Tailwind CSS and utilized React Context to manage tasks, tags, and timestamps, reducing redundant API calls and optimizing frontend-backend interaction.

---

## 🎫 Concert Ticket Booking Platform

**GitHub:** https://github.com/Pbi-with-love/Concert-Ticket-Booking-Platform

### Technologies

`Node.js` · `Express.js` · `PostgreSQL` · `Prisma ORM` · `Redis` · `Supabase` · `Postman`

### Highlights

* **Designed a relational database schema** and implemented booking, voucher, ticket inventory, payment, and attendee data models using Prisma ORM.
* Implemented customer-facing **booking APIs** for creating bookings, applying vouchers, checking booking status, and retrieving booking details.
* Built **concurrency-safe booking logic** using database transactions and atomic conditional updates to prevent ticket overselling.
* **Implemented idempotency handling** using a unique `idempotencyKey` together with Redis locks/cache to prevent duplicate bookings caused by request retries.
* Added **Redis caching** for booking lookup APIs to reduce database load on read-heavy endpoints.

---

## 🤖 n8n Automation Workflow

**GitHub:** https://github.com/Pbi-with-love/n8n_automation

### Technologies

`n8n` · `REST APIs` · `Facebook Meta Developer` · `Google Cloud Platform` · `Supabase` · `Apify` · `LLM` · `RAG` · `Vector Database`

### Highlights

* Built **two end-to-end automation workflows** using n8n, integrating multiple third-party APIs and services, including Facebook Meta Developer, Google Cloud Platform, Supabase, and Apify.
* Applied foundational knowledge of **LLMs, Retrieval-Augmented Generation (RAG), and vector databases** to build AI-assisted automation workflows.
* Applied system design concepts involving **database interactions, cloud infrastructure, and RESTful APIs** to connect multiple services into automated workflows.
