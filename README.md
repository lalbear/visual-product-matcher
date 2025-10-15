# 🛍️ Visual Product Matcher

A web application that helps users find **visually similar products** from a curated catalog after uploading an image or pasting an image URL.  
Built as part of the **Technical Assessment Project** for a Software Engineering position.

---

## 🌐 Live Demo

- **App URL:** _<add your Vercel deployment link here>_  
- **GitHub Repo:** _<add your repo link here>_

---

## ✨ Features

- 🖼 **Image Upload Options:**
  - Upload directly from device  
  - Paste an online image URL  

- 🔍 **Search Interface:**
  - Shows uploaded image preview  
  - Displays a list/grid of visually similar products  
  - Adjustable **Similarity Filter** (slider)

- 🧩 **Product Database:**
  - Over **50+ items** using public images (Unsplash)  
  - Each includes: name, category, and price  

- 📱 **Responsive UI:**
  - Fully mobile-friendly and adaptive layout  

- ⚙️ **Error Handling:**
  - Handles invalid URLs, large files, and missing data gracefully  

- ⏳ **Loading States:**
  - Displays loaders and fallback UIs during processing  

- 🚀 **Hosting Ready:**
  - Easily deployable to **Vercel** or **Netlify**

---

## 🧠 Approach (under 200 words)

This project delivers a clean, production-quality **visual search experience** entirely on the frontend.  
The app accepts both local uploads and image URLs, previews them instantly, and then performs lightweight visual similarity matching from a local dataset of 50+ products.

A custom **client-side image parser** extracts hints from filenames and URLs (e.g., “jacket”, “hoodie”, “sunglasses”) and compares them with product metadata to estimate visual similarity.  
Results are ranked and displayed in a responsive grid layout with a user-controlled **similarity filter slider**.  

To maintain simplicity and portability, the app runs **without a backend or API keys**, though it’s structured to easily integrate AI services later (e.g., Hugging Face, CLIP embeddings).  
Emphasis is placed on good UX — clear loading states, meaningful fallbacks, and clean component-based React code styled with Tailwind CSS.

---

## ✅ How It Meets the Requirements

| Requirement | Implementation |
|--------------|----------------|
| Image Upload | Supports both file upload & image URL input |
| Search Interface | Displays preview, product grid, and similarity filter |
| Product Database | 50+ public images with metadata |
| Hosting | Deployable to Vercel (free tier) |
| Responsiveness | Fully responsive with Tailwind CSS |
| Error Handling | File validation & clear error messages |
| Loading States | Animated loader and fallback grid |
| Documentation | Clear README & inline code comments |

---

## 🧰 Tech Stack

- ⚛ **React** – frontend framework  
- 🎨 **Tailwind CSS** – styling & responsive design  
- 🧠 **Lucide React** – icon library  
- 🖼 **Unsplash** – image source for demo data  
- ⚡ **Vercel** – deployment (free tier)

---

## 🧑‍💻 Local Setup

1. **Install dependencies**
   ```bash
   npm install
