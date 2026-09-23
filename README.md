# 🌟 Brand Business Audit

> An AI-powered personal brand & positioning diagnostic web app built with Google Gemini & Google AI Studio, designed to analyze social media profile assets (Instagram & TikTok), diagnose messaging leaks, and generate high-converting revamps.

<p align="center">
 <img width="800" height="514" alt="BrandBusinessAuditEngine-ezgif com-optimize" src="https://github.com/user-attachments/assets/f72c6218-3476-4cd7-bc99-a1550474a2b0" />
</p>

---

## ✨ Features & Architecture

* **Multi-Modal Asset Analysis:** Accepts drag-and-drop avatar uploads and top 6–9 grid screenshots to critique visual hierarchy, authority, and aesthetic alignment.
* **Dual-Archetype Positioning Engine:** Allows users to select up to two target brand aesthetics (out of 10 curated archetypes, e.g., *Luxe / Editorial* + *Minimalist*) to calculate a **Target Vibe Match Score**.
* **5-Point Strategic Audit Generation:**
  1. *Brand Alignment & Messaging Leak Analysis* (identifying lost client conversions)
  2. *SEO-Optimized Bio Headlines*
  3. *High-Converting "I Help" Formula Breakdown*
  4. *Strategic Story Highlights Plan*
  5. *Direct-Response Link-in-Bio CTA*
* **Interactive Live Profile Simulation:** Real-time preview toggles between original and revamped bios across custom Instagram and TikTok UI layouts.
* **Resilient Multi-Model Fallback Pipeline:** Engineered backend retry logic across Google Gemini models (`gemini-3.1-flash-lite`, `gemini-3.8-flash`) with exponential backoff and localized fallback synthesis to ensure 99.9% application uptime under upstream load spikes.
* **Client-Side Exporting:** Integrated JS-PDF library to generate customizable, multi-page PDF executive audit reports.

---

## 🛠️ Tech Stack

* **Frontend:** React, TypeScript, Tailwind CSS, Lucide Icons, jsPDF
* **Backend / AI:** Node.js, Express, Google Gemini API (Multimodal Vision & Text)
* **Design System:** Ethereal Dreamscape (Custom CSS Glassmorphism, Pearl Gradients, Baroque Gold Accents)
