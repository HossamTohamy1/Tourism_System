# 🌍 E-Tourism — Travel Booking Back-End

> The engine behind a tourism website: discover cities and tourist destinations, book trips, pay online, and leave reviews.

---

## 🧐 What is this, in plain words?

Planning a trip usually means jumping between many websites to find places to visit, compare prices and book.

This project is the **back-end (the "brain")** of a tourism platform that puts it all together:

- 🏙️ Browse **cities** and the **tourist destinations** in each one.
- 🛒 Add trips to a **cart**.
- 💳 Place an **order** and **pay online** (Stripe).
- ⭐ Read and write **reviews** about destinations.
- 👤 Create an **account**, log in, and manage your profile.

## 👥 Who uses it?

| Who | What they can do |
|---|---|
| **Traveler** | Browse cities & destinations, book, pay, review |
| **Admin** | Add/edit cities and destinations (with images), manage orders and users |

## 🔄 How it works (the simple story)

```
Traveler explores cities ➜ Picks destinations ➜ Adds to cart ➜ Pays online ➜ Leaves a review after the trip
```

---

## 🛠️ For developers

**Tech stack:** Node.js · Express · MongoDB (Mongoose) · JWT authentication · bcrypt · Joi validation · Stripe payments · Cloudinary (image uploads) · Nodemailer (emails) · Multer · QR codes · Deployed on Vercel

**Modules (`src/modules`):** `auth`, `user`, `city`, `touristdestination`, `cart`, `order`, `reviews`

**Run locally**

1. Install [Node.js](https://nodejs.org/) (LTS) and have a MongoDB database ready.
2. Create a `.env` file with:
   ```
   PORT=
   MOOD=
   DB_LOCAL=
   DB_CLOUD=
   APP_NAME=
   BEARER_KEY=
   TOKEN_SIGNATURE=
   ORDER_TOKEN_SIGNATURE=
   SALT_ROUND=
   STRIPE_KEY=
   SUCCESS_URL=
   CANCEL_URL=
   ```
3. Run:
   ```bash
   npm install
   npm run dev
   ```

---

## 🇪🇬 بالعربي

ده "العقل" اللي ورا موقع سياحة: بيعرض المدن والأماكن السياحية في كل مدينة، وبيخلّي المسافر يحجز رحلات ويدفع أونلاين، ويكتب رأيه في الأماكن اللي زارها.
