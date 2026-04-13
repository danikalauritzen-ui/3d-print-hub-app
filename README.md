# 3D Print Hub App 🚀
*A mobile shopping experience for high-quality 3D printed collectibles.*

## 📌 Project Overview
This project is an e-commerce mobile application designed for my 3D printing shop. The goal is to bridge the gap between digital marketing efforts and a seamless purchasing experience, allowing customers to browse and buy 3D models directly through a dedicated platform.

---

## 🎯 Target Audience & User Acquisition
- **Primary Segments:** Tech enthusiasts, tabletop gamers, and collectors.
- **Acquisition Strategy:** - **SEO:** Organic traffic driven from web search.
    - **Social Media:** Direct engagement and lead generation via Instagram.

---

## ✨ Key Features (MVP)
- [ ] **Product Catalog:** A visual gallery of all 3D printed objects.
- [ ] **Product Details:** High-quality images, dimensions, and material specs.
- [ ] **Shopping Cart:** Easy management of selected items.
- [ ] **Checkout:** Integrated payment flow for final orders.

---

## 🛠️ Tech Stack
- **Design:** Figma (UI/UX) & Metaverse Design Principles.
- **Frontend:** Flutter (Dart) - Chosen for its high-performance UI capabilities.
- **Backend:** Firebase (Authentication, Firestore, and Storage).
- **Version Control:** Git & GitHub.

---

## 🎨 UI Components (Design System)
The interface will follow a clean, modern aesthetic to showcase 3D models.
- **Product Cards:** Featuring high-res images, title, and "Add to Cart" quick action.
- **Category Chips:** Horizontal scrolling filters (e.g., Figures, Home, Accessories).
- **Cart Badge:** Real-time counter for selected items in the navigation bar.
- **Custom Buttons:** Minimalist style for "Checkout" and "Buy Now."

---

## 🔍 Product Visualization Strategy
To leverage my background in Metaverse Design, the app will feature:
- **Interactive 3D Previews:** Integration with 3D viewers to rotate and inspect models.
- **Material Showcase:** High-detail close-ups for PLA and Resin textures.
- **Scale Reference:** Visual indicators to help users understand the physical size of 3D prints.

---

## 💾 Data Structure (Firestore Schema)
To manage the 3D shop inventory, each product will store the following attributes:
- **Product ID:** Unique identifier for the database.
- **Name:** Title of the 3D model (e.g., "Dragon Miniature").
- **Category:** Tag for filtering (e.g., "Tabletop RPG", "Decor").
- **Material:** Options for printing (PLA, Resin, PETG).
- **Price:** Based on material volume and print time.
- **Image Gallery:** Links to high-quality photos stored in Firebase.
- **3D File Link:** URL for the interactive previewer.

---

## 📝 User Stories
To guide the development process, I've defined the core user needs:
- **As a Collector:** I want to filter products by material (Resin vs PLA) so I can choose the best quality for my miniatures.
- **As a First-time Buyer:** I want an intuitive navigation so I can find and purchase a 3D model in less than 3 minutes.
- **As a Tech Enthusiast:** I want to rotate the 3D preview of the model to check for printing details before buying.
- **As a User:** I want to save items in a cart so I can manage my budget before finalizing the checkout.

---

## 📈 Development Journal (The "10-Minute" Challenge)
I am building this application in **10-minute daily increments** to demonstrate consistency and a focused learning path during my transition to Software Engineering.

- **Day 1:** Project scoping, repository setup, and README documentation.
- **Day 2: Mapping the User Journey**
  - Goal: Define how a customer interacts with the 3D print shop.
  - User Flow Steps:
    1. **Home Screen:** Browse featured 3D models (categories: Games, Home Decor, Tech).
    2. **Product Page:** View high-res photos and material details (PLA, Resin).
    3. **Cart:** Review items and quantity.
    4. **Checkout:** Simple login/guest checkout and payment confirmation.
- **Day 3: Tech Stack Selection**
  - Goal: Choose the tools to build the app.
  - Decision: Selected **Flutter** for the frontend to ensure a high-quality design-to-code transition and **Firebase** for a scalable backend.
- **Day 4: UI Architecture & Components**
  - Goal: Define the visual structure of the app.
  - Progress: Listed the key UI components to ensure a consistent design-to-code transition using Flutter.
- **Day 5: Product Visualization Planning**
  - Goal: Define how 3D models will be presented to the user.
  - Progress: Integrated 3D viewing concepts into the UX, bridging the gap between Metaverse Design and Mobile E-commerce.
- **Day 6: Data Schema Design**
  - Goal: Map the information needed for the product database.
  - Progress: Defined the Firestore attributes to ensure seamless integration between the shop's inventory and the app's interface.
- **Day 7: User Stories & Requirements**
  - Goal: Define functional requirements from a user perspective.
  - Progress: Drafted the primary user stories to ensure the app solves real customer needs in the 3D printing niche.
- **Day 8: Backend Infrastructure Setup**
  - Goal: Initialize the project's cloud environment.
  - Progress: Created the official project on Firebase Console, preparing the ground for Authentication and Firestore Database integration.
