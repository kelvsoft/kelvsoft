# Emmanuel Ebuka Williams

**Full-Stack Developer — Laravel · React · MySQL**
Lagos, Nigeria · Open to remote roles worldwide and to relocation with sponsorship

I build production web applications, mostly in the parts of a system that are unforgiving:
concurrent balance updates, geospatial search under time pressure, authentication, and data that
becomes dangerous when it goes stale.

🌐 **[emmanuel-williams.vercel.app](https://emmanuel-williams.vercel.app)** ·
✉️ emmanuelebukawilliams@gmail.com ·
💼 [LinkedIn](https://www.linkedin.com/in/emmanuel-ebuka-williams-3662b8355/)

---

## What I'm building

### 🚑 QuickCure NG — emergency healthcare platform
Helps a patient find the nearest verified hospital that *currently holds* the treatment they need,
rather than the nearest hospital in general. Built after a woman died of a snakebite having been
taken to two hospitals with no antivenom.

Term expansion so "snake bite" and "antivemon" both resolve; a bounding-box pre-filter on indexed
coordinates before any Haversine maths; a radius that expands automatically from 15km to 100km;
WhatsApp OTP with layered rate limiting; and a data-freshness dashboard that catches stale stock
before a patient drives to it.

`Laravel` `React` `Inertia.js` `MySQL` `WhatsApp API` — *in testing*

### 📈 [Limit-Order Exchange](https://github.com/kelvsoft/limit-order-exchange) — real-time matching engine
A cryptocurrency exchange with a live order book. Orders match inside a single transaction with row
locks on everything it writes, so two orders arriving at once can't consume the same liquidity.
Funds are committed at placement rather than checked at execution, partial fills keep the remainder
open, and trades execute at the maker's price so a taker is never filled worse than their limit.

`Laravel` `Vue 3` `Pusher` `MySQL` `Chart.js`

### 🛒 [SomiStore](https://somistore.com.ng) — e-commerce platform *(live)*
A complete storefront and admin platform built for a retail business. Catalogue with categories and
subcategories, cart with guest-cart merging on login, wishlist, delivery and shipping, order
tracking, reviews limited to verified purchasers, two-way customer↔admin messaging, and an
analytics dashboard.

`Laravel` `React` `Inertia.js` `MySQL` `OPay`

### 🛍️ [TrustShop](https://github.com/kelvsoft/laravel-react-cart-system) — cart & checkout system
A focused exercise in getting commerce correctness right: a database-backed cart that survives
logout and follows the user across devices, stock validated at every entry point and locked at
checkout, orders written in a transaction, prices recorded at purchase, and low-stock alerts as
queued background jobs.

`Laravel 11` `React` `Inertia.js` `MySQL` `Queues`

### 💬 [EchoStream](https://github.com/kelvsoft/EchoStream-Engine) — real-time chat
Messaging with image attachments, typing indicators and read receipts over WebSockets. New messages
broadcast to everyone including the sender, so both sides render from server-confirmed state rather
than optimistic local state that can drift.

`Laravel` `React` `Inertia.js` `Pusher`

---

## Tech

**Backend** — PHP, Laravel, MySQL (schema design, transactions, row locking), REST APIs, queues and
scheduled jobs. Currently deepening Python for backend work.

**Frontend** — JavaScript, React, Inertia.js, Vue 3, Tailwind CSS, Vite. TypeScript and Next.js from
contract work. React Native for mobile.

**Real-time & integrations** — Pusher, Laravel Echo, WebSockets, WhatsApp API, OPay, transactional mail.

**Tools** — Git, Postman, Linux, Chart.js, Pest.

---

## About

I started building for other people before I built for myself — e-commerce for a gadgets retailer,
then a full storefront for a family business, then contract frontend work on a school platform in
Next.js and TypeScript.

I read other people's code as much as I write my own, and I document what my projects get wrong as
well as what they get right — every README here has a limitations section. I'm looking for a team
where my work gets reviewed properly and I can learn faster than I can alone.

📄 **[CV](https://emmanuel-williams.vercel.app/resume.pdf)**
