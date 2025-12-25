# Infibazar – One Product Landing Page

Infibazar is a lean D2C product-selling setup built to validate products using **Facebook Ads** and a **high-conversion one-page landing page**. This repository contains the frontend landing page hosted on **GitHub Pages**, with order data sent directly to **Google Sheets** using **Google Apps Script**—no traditional backend required.

---

## 🎯 Project Goal

- Sell **one product per landing page**  
- Drive traffic via **Facebook Ads**  
- Collect customer order details directly from the landing page  
- Confirm orders manually via phone call  
- Keep infrastructure **simple, fast, and cost-free**

This project is optimized for early-stage validation and can be scaled later with a custom domain, checkout system, or backend.

---

## 🧠 Core Strategy

- **Single-product focus** for maximum conversion  
- **No navigation menu** (no distractions)  
- **Embedded order form** inside the landing page  
- **Floating WhatsApp button** for customer inquiries  
- **Manual order confirmation** to reduce fake orders

---

## 🛠️ Tech Stack

- **HTML5** – page structure  
- **CSS3** – styling and responsive layout  
- **Vanilla JavaScript** – form submission logic  
- **GitHub Pages** – static hosting  
- **Google Apps Script** – form handler (acts as backend)  
- **Google Sheets** – order data storage

No frameworks. No servers. No databases.

---

## 📁 Project Structure

---

## 🧾 Order Form Workflow

1. User visits the landing page  
2. User fills in the embedded order form  
3. Form submits data using `fetch()` POST request  
4. Data is received by a **Google Apps Script Web App**  
5. Order details are saved into **Google Sheets**  
6. Infibazar team manually calls the customer to confirm the order

---

## 📝 Order Form Fields

**Required:**  
- Full Name  
- Phone Number  
- Full Delivery Address  
- City / Area  

**Optional:**  
- Order Note  

Email is intentionally excluded to reduce friction for Bangladesh-based users.

---

## 💬 WhatsApp Integration

A floating WhatsApp button is included for:  
- Product questions  
- Pre-purchase clarification  
- Building customer trust

WhatsApp is treated as a **support channel**, while the form is used for **confirmed purchase intent**.

---

## 🔐 Data & Privacy

Customer data is collected **only for order processing and confirmation**. No data is sold or shared with third parties.

---

## 🚀 Deployment

- Hosted using **GitHub Pages**  
- Can be accessed via:  
  `https://atikulislamx.github.io/InfiBazar`

---

## 🔄 Future Improvements

- Add reCAPTCHA for spam protection  
- Connect a custom domain  
- Add Facebook Pixel / Meta Conversion API  
- Introduce checkout & payment gateway  
- Multi-product landing pages

---

## 📌 Notes for Contributors / AI Tools

This repository is intentionally minimal. Any code generation (e.g., GitHub Copilot) should follow the principles outlined above:  
- One-page layout  
- Conversion-focused UX  
- No external frameworks  
- Google Apps Script for form handling

---

## 🏷️ Brand

**Infibazar** – Smart. Lean. Conversion-first.

---

If you are reviewing or extending this project, always prioritize **clarity, speed, and trust** over visual complexity.
