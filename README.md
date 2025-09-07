🛍️ Multi-Vendor E-Commerce Marketplace

Welcome to Bazario..........


<img width="1750" height="961" alt="Screenshot (1054)" src="https://github.com/user-attachments/assets/9529e611-ad73-4058-8812-a44c1c945d29" />



Website Link: https://bazario.ltd/

📑 Table of Contents

📖 Introduction

🛠️ Technology Stack

✅ Requirements

🎨 Design

📌 Conclusion

🚀 Getting Started

🤝 Contribution

📜 License

📖 Introduction
1.1 Project Overview

The Multi-Vendor E-Commerce Marketplace is a full-featured online platform designed to bring together multiple vendors and buyers within a unified digital ecosystem.

Unlike traditional single-vendor systems, this marketplace empowers multiple sellers to register, showcase their products, and reach a global customer base.

🔑 Key Goals:

Build a robust, scalable, and user-friendly solution

Provide vendors with tools for product & order management

Enable buyers with seamless browsing and secure transactions

Empower admins with governance & compliance controls

🛠️ Technology Stack


🔹 Frontend

Next.js 15 – Fast, SEO-optimized framework

React 19.1.0 – UI library for interactive components

Tailwind CSS 4.1.11 – Utility-first CSS framework

Shadcn UI – Consistent, customizable UI components

DM Sans Font – Clean and modern typography

🔹 Backend

Bun Runtime – Ultra-fast JavaScript runtime

Node.js v23.7.0 – Scalable backend services

Payload CMS – Headless CMS with admin APIs

MongoDB – Efficient NoSQL database

Stripe Connect – Secure payment integration

🔹 Development Tools

TypeScript 5.8.3 – Strong typing for reliability

ESLint 9.31.0 – Code linting & consistency

Git & GitHub – Version control & collaboration

Shadcn CLI 2.9.2 – UI component setup

🔹 Design Frameworks

NeoBrutalism Theme – Bold, modern UI style

Mobile-First Responsive Layout – Device-friendly access

✅ Requirements
Functional Requirements (FRs)

🔑 Secure user authentication

🏪 Vendor store/product management

🔍 Product browsing, search & filters

💳 Payment options (Stripe & COD)

🛒 Shopping cart (add, update, remove)

📦 Order management (confirm/cancel)

🔐 Role-based access (customer/vendor/admin)

⭐ Product review & rating system

📊 Admin dashboard (monitoring & moderation)

📩 Contact & notification system

Non-Functional Requirements (NFRs)

🛡 Security → Protect user data

⚡ Performance → Fast & smooth experience

📈 Scalability → Handle user/product growth

🌐 Availability → 24/7 uptime

🎯 Usability → Intuitive design

📊 Data Integrity → Accuracy & consistency

📱 Accessibility → Multi-device support

Extra-Ordinary Features

Advanced product filtering (category, price, rating, availability)

Real-time order tracking & history

Wishlist & favorites system


🎨 Designs

Use Case Diagrams :

<img width="1662" height="1380" alt="Picture5" src="https://github.com/user-attachments/assets/0b98224b-6e8e-4a0f-8772-b4d4440dae6d" />
<img width="1950" height="1395" alt="Picture4" src="https://github.com/user-attachments/assets/f4f151d2-0abb-4c53-b8a5-38871024b1a7" />
<img width="1882" height="1256" alt="Picture3" src="https://github.com/user-attachments/assets/545a1de2-413e-42dc-8608-fc452a9f74c6" />
<img width="2246" height="1492" alt="Picture2" src="https://github.com/user-attachments/assets/942a195d-589c-49e5-91dd-4e91e57bfceb" />
<img width="2246" height="917" alt="Picture1" src="https://github.com/user-attachments/assets/daa18d4d-406a-47b5-a7a2-ff5e2aa0f660" />
<img width="1228" height="886" alt="Picture9" src="https://github.com/user-attachments/assets/559f864c-b71d-4a71-9d6c-ffe4ecd71531" />
<img width="1174" height="590" alt="Picture8" src="https://github.com/user-attachments/assets/b4bec1bd-6306-4cf9-9d0a-405287047f7e" />

Class Diagrams :

<img width="2356" height="2114" alt="class diagram" src="https://github.com/user-attachments/assets/815eee0f-854f-497e-8aab-0c7572b7cb14" />

Top level Component :

<img width="2211" height="1916" alt="top level componenert" src="https://github.com/user-attachments/assets/0ef10406-86d0-4c3c-8875-0efd3dea2fcf" />

Activity Diagram :

<img width="505" height="636" alt="activity" src="https://github.com/user-attachments/assets/b46bf626-511d-489e-9489-0b5eea161069" />

Navigation Flow :

<img width="1950" height="2466" alt="navigation flow" src="https://github.com/user-attachments/assets/af64f2b3-5232-40e9-94ff-d14dc6a3524c" />

DB Design :

<img width="2122" height="2459" alt="db diagram" src="https://github.com/user-attachments/assets/f7c0a6b3-4f4a-4258-b634-f1a1799ee825" />

White-Box Testing :

1) Login Module

<img width="1490" height="2212" alt="white box testing 1" src="https://github.com/user-attachments/assets/e636e732-0a9d-46ae-a1c4-fde51675f3e3" />


Black-Box Testing :

<img width="677" height="784" alt="image" src="https://github.com/user-attachments/assets/0d5c4ea7-5fbe-456f-9ad1-1e08b320bef1" />




📌 Conclusion
7.1 Learnings

Full-stack expertise (Next.js, React, Node.js, MongoDB, Payload CMS)

Cloud deployment (Vercel & Render with custom domains)

Secure transactions with Stripe Connect

Collaboration using Git & GitHub workflows

Testing & QA (SRS, white-box, black-box)

7.2 Limitations

No real-time chat (customer ↔ vendor)

No blog/content module for updates

7.3 Future Plans

🗨️ In-app messaging/chat support

✍️ Vendor & admin blogging system

📱 Cross-platform mobile app

🤖 ML-driven recommendations & analytics

🔒 Multi-factor authentication & fraud detection

⚙️ Microservices-based scalability

🚀 Getting Started
1️⃣ Clone the Repository
git clone https://github.com/your-username/multi-vendor-ecommerce.git
cd multi-vendor-ecommerce

2️⃣ Install Dependencies
npm install
# or
bun install

3️⃣ Setup Environment Variables

Create a .env.local file:

MONGODB_URI=your_mongo_connection_string
STRIPE_SECRET=your_stripe_secret_key
PAYLOAD_SECRET=your_payload_secret

4️⃣ Run Development Server
npm run dev
# or
bun dev

5️⃣ Build for Production
npm run build

🤝 Contribution

We welcome contributions!

Fork the repo

Create a feature branch → git checkout -b feature-name

Commit changes → git commit -m "Added feature"

Push to branch → git push origin feature-name

Open a Pull Request 🎉

📜 License

This project is licensed under the MIT License – free for use & modification.

✨ Multi-Vendor E-Commerce Marketplace → A next-generation platform designed for scalability, security, and user empowerment.
