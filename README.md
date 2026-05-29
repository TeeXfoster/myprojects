# Vision Sketches Website (Static HTML)

This folder contains a simple static website built with plain *HTML*.

---

## 1) Folder Structure (what’s inside this folder)

- project/README.md  
  This documentation file.

- pages/  
  All website pages (each page is a separate .html file):
  - pages/index.html (Landing page)
  - pages/home.html
  - pages/about-us.html
  - pages/integrations.html
  - pages/pricing.html
  - pages/features.html

- assets/  
  Static assets used by the pages:
  - assets/IMAGE.jpeg (used on the Home page)

- css/  
  A CSS directory exists in the project root. (In the current HTML pages you can see, no CSS file is explicitly linked.)

---

## 2) How Navigation Works

Every page uses the same navigation bar:

- Home
- About Us
- Integrations
- Pricing
- Features

The links switch between files inside pages/, for example:

- From pages/index.html to pages/home.html:
  - home link → home.html

Because these are separate HTML files, the site works by directly opening the corresponding file (no build step needed).

---

## 3) Step-by-Step: How to View the Website

### Option A (Simplest)
1. Go to: project/pages/
2. Open index.html in a web browser.
3. Use the navigation links in the header to move between pages.

### Option B (Check the Home image path)
1. Open project/pages/home.html in a browser.
2. Confirm the image loads.
3. The Home page references the image using a relative path:
   - ../assets/IMAGE.jpeg

If you open home.html from a different folder location (outside project/pages/), the image path may not resolve correctly.

---

## 4) Pages (what each file is for)

### pages/index.html
- Landing page.
- Shows a short introduction.
- Includes a list of page links (Home, About Us, Integrations, Pricing, Features).

### pages/home.html
- Home section.
- Includes a heading and a paragraph.
- Displays the image:
  - ../assets/IMAGE.jpeg

### pages/about-us.html
- About Us / mission-style content.
- Explains the purpose of Vision Sketches.

### pages/integrations.html
- Lists integrations/tools.
- Current content includes: figma, adobe xd, sketch, canva, procreate wireframes.

### pages/pricing.html
- Pricing section.
- Contains a simple pricing table layout using HTML divs.

### pages/features.html
- Features list.
- Uses an unordered list (<ul>) of feature items (drag-and-drop canvas, layers, export, vector tools, guides, undo/redo, etc.).

---

## 5) Notes (relative links and consistency)

- The pages consistently include:
  - header (title: VISION SKETCHES)
  - nav (page-to-page links)
  - footer (copyright line)
- The only asset currently referenced directly is the image on the Home page:
  - project/assets/IMAGE.jpeg

---

## Quick Checklist

- [ ] Open project/pages/index.html
- [ ] Click through nav links to confirm all pages load
- [ ] Open project/pages/home.html to confirm ../assets/IMAGE.jpeg loads correctly# project

