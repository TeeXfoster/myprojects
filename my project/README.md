# Vision Sketches (Static Multi-page Website)

## Project overview
**Vision Sketches** is a static, multi-page website built with **HTML/CSS**.

It provides navigation across core pages:
- Home (`index.html`)
- About (`about-us.html`)
- Product (`product.html`)
- Features (`features.html`)
- Contact (`contact.html`)

The site uses a shared global stylesheet and assets stored in the `asset/` folder.

---

## File structure
```text
my project/
├─ index.html
├─ about-us.html
├─ features.html
├─ contact.html
├─ product.html
├─ README.md
├─ TODO.md
├─ css/
│  └─ styles.css
└─ asset/
   ├─ 101.mp4
   ├─ 
   ├─ art1.jpeg
   ├─ art2.jpeg
   ├─ art3.jpeg
   ├─ art4.jpeg
   ├─ art5.jpeg
   ├─ art6.jpeg
   ├─ art7.jpeg
   ├─ art8.jpeg
   ├─ art9.jpeg
   ├─ art10.jpeg
   ├─ art11.jpeg
   ├─ art12.jpeg
   ├─ art13.jpeg
   ├─ screenshot laptop-1024px.png
   ├─ screenshot tablet 768px.png
   └─ screenshotmobiles-320px.png
```

---

## Pages included

### `index.html` (Home)
- Top navigation (Home, About Us, Product, Features, Contact)
- Hero section with a video (`asset/101.mp4`)
- CTA buttons to Product and Features
- Footer with social links and “Back to Top”

### `about-us.html` (About)
- Navigation + About content
- Vision / Values / History sections
- Team section with images from `asset/`
- Footer with social links and “Back to Top”

### `features.html` (Features)
- Navigation + a features list
- Footer with social links and “Back to Top”

### `product.html` (Product)
- Navigation + product/pricing sections
- “Product images” grid showing thumbnails from `asset/art1.jpeg` … `asset/art13.jpeg`
- Footer with social links and “Back to Top”

### `contact.html` (Contact)
- Navigation + contact information
- Embedded Google Map iframe
- Contact form (with a modal placeholder for success)
- Footer with social links and “Back to Top”

---

## Assets
- Images/videos are stored in `asset/`.
- Background imagery is implemented via `css/styles.css` using the `asset/` files.

---

## Styling

### Global stylesheet: `css/styles.css`
Defines:
- Base/reset styles
- Shared layout for `header`, `nav`, `main`, `footer`
- Button styles (`.btn`, `.btn.primary`)
- Product page helpers
- Smooth scrolling (`html { scroll-behavior: smooth; }`)
- Background image helpers (e.g. `.page-bg`, `.about-bg`, `#features`)

---

## Screenshot files (Mobilisation)
The project includes responsive screenshots to demonstrate the UI across device sizes. Click a link to open the image:
- [Laptop (1024px)](asset/screenshot%20laptop-1024px.png)
- [Tablet (768px)](asset/screenshot%20tablet%20768px.png)
- [Mobile (320px)](asset/screenshotmobiles-320px.png)



