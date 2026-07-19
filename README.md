
# Apimor Digital Landing Page

A premium, high-performance single-page application designed for **Apimor Digital**. The interface bridges the aesthetic requirements of next-gen software systems with bare-metal industrial hardware engineering. Optimized for rapid delivery and zero-config deployment on **Cloudflare Pages**.

## 🚀 Tech Stack & Design Architecture

* **Structure:** Semantic HTML5
* **Styling:** Tailwind CSS (via edge CDN delivery)
* **Typography:** Google Fonts (Inter)
* **Graphics:** 100% Inline vector SVG layouts (No initial external image requests needed)
* **Theme:** Deep slate dark-mode matrix (`slate-900` to `slate-950`) accented with industrial amber (`amber-500`) and indigo (`indigo-600`) gradients.

---

## 📂 Project Directory Structure

```text
apimor-digital-landing/
├── assets/
│   ├── images/
│   │   ├── logo.png
│   │   ├── invitely.jpg
│   │   ├── water-vending.jpg
│   │   └── hivetrace.jpg
│   └── documents/
│       └── water-vending-specs.pdf
└── index.html

```

---

## 🛠️ Local Development Setup

To preview code changes instantly in your local workspace:

1. Open the project root folder inside **VS Code**.
2. Install the **Live Server** extension (by Ritwick Dey).
3. Right-click on `index.html` and select **"Open with Live Server"**.
4. The site will boot immediately on `[http://127.0.0.1:5500](http://127.0.0.1:5500)`. Any code modifications you save will automatically hot-reload in the browser.

---

## 📈 Scalability: Adding More Products

The code contains an isolated, hidden HTML boilerplate template to make expanding your product catalog direct and seamless.

To add a 4th or 5th product card:

1. Open `index.html` and navigate to the `#products` section grid container.
2. Locate the commented-out `🚀 FUTURE PRODUCTS TEMPLATE INSTRUCTIONS` block.
3. Copy the template block, paste it directly above the comment, and uncomment it.
4. Modify the values (`New Product Name`, description paragraph, action links, and icon SVGs). The layout uses Tailwind's responsive grid system (`grid-cols-1 md:grid-cols-2 lg:grid-cols-3`) and will automatically re-align the rows perfectly.

---

## ⚡ Cloudflare Pages Deployment Guide

Deploying directly to Cloudflare's global edge network takes less than two minutes:

### Method 1: Direct File Drop (Fastest)

1. Compress your workspace or simply grab your `index.html`.
2. Log in to your **Cloudflare Dashboard**.
3. Navigate to **Workers & Pages** > **Create application** > **Pages** > **Upload assets**.
4. Name your project (e.g., `apimor-digital`), drag and drop your files, and click **Deploy**.

### Method 2: Git-Backed CI/CD (Recommended for Continuous Updates)

1. Push your workspace repository to GitHub or GitLab.
2. In the Cloudflare Pages dashboard, select **Connect to Git**.
3. Choose your repository.
4. Leave **Build settings** completely blank (since this is a pure static HTML build, no build command or build directory is required).
5. Click **Save and Deploy**. Every future `git push` to your main branch will automatically trigger an instant deployment.

---

## 📞 Corporate Information & Routing

* **Headquarters:** Kibondo, Kigoma, Tanzania
* **Corporate Branch:** Ubungo, Dar Es Salaam, Tanzania
* **Primary Communications:** <contact@apimordigital.com>
* **Direct Operations Telephony:** +255 743 527 350
