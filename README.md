# El Nido, Palawan Tourism Web Platform
## Final Examination Project — Applied Business Tools and Technologies in Tourism

A fully functional, responsive, and aesthetically designed tourism web platform for **El Nido, Palawan**, built using semantic **HTML5**, **Vanilla CSS & Design System Tokens**, and **Bootstrap 5.3**. 

Designed specifically for **GitHub Pages hosting**, the website utilizes an **HTML5 LocalStorage Database Engine** for zero-SQL client-side data persistence (booking reservations, customer testimonials, and online inquiries).

---

## 🌴 Key Project Features & Requirements Compliance

### 1. Authentic Brochure Integration
Directly extracts all data from the official Municipal Tourism Office brochure:
* **Featured Package:** 4 Days & 3 Nights Island Escape at **₱8,500 per person**.
* **Attractions & Highlights:** Big Lagoon kayaking, Secret Lagoon natural pool, Shimizu Island coral reef & snorkeling, Seven Commandos beach relaxation, Nacpan-Calitang Twin Beaches, and Las Cabañas sunset viewing.
* **Service Amenities:** 3 Nights accommodation with daily breakfast, licensed boat captain and eco tour guides, basic snorkeling gear & life jacket, and authentic grilled island seafood feast.
* **Transparent Exclusions:** Airfare, ETDF Eco-Tourism Development Fee (₱200), Big Lagoon kayak rental (₱300), personal expenses, alcoholic beverages, and tips.
* **Official Municipal Desk:** NIPAP Building, Real Street, Brgy. Buena Suerte, El Nido, Palawan (Hotlines: `0919-002-1389` / `0906-449-0282`, Email: `elnidotourism@gmail.com`).

---

### 2. Website Architecture & Pages
* [index.html](file:///c:/MY%20PROJECTS/EL_NIDO_PALAWAN_WEBSITE/index.html): Hero section, official accreditation banner, live trip budget estimator, featured brochure package card, verified traveler reviews, and municipal FAQs.
* [about.html](file:///c:/MY%20PROJECTS/EL_NIDO_PALAWAN_WEBSITE/about.html): Destination background, history (from Bacuit to El Nido), mission, vision, core values, competitive advantages, and visitor target market analysis.
* [destinations.html](file:///c:/MY%20PROJECTS/EL_NIDO_PALAWAN_WEBSITE/destinations.html): Detailed product cards with category filters (Island-Hopping, Inland Beaches, Services & Amenities) with duration, price, and availability.
* [packages.html](file:///c:/MY%20PROJECTS/EL_NIDO_PALAWAN_WEBSITE/packages.html): 5 complete tour packages with full day-by-day itineraries, inclusions, exclusions, and target markets.
* [gallery.html](file:///c:/MY%20PROJECTS/EL_NIDO_PALAWAN_WEBSITE/gallery.html): 10 high-resolution photographs with category filters, detailed captions, source credits, and a responsive image lightbox modal.
* [travel-info.html](file:///c:/MY%20PROJECTS/EL_NIDO_PALAWAN_WEBSITE/travel-info.html): How to get there (AirSWIFT direct to Lio Airport vs PPS van transfer), interactive Google Maps embed, seasonal climate guide, packing checklist, eco code of conduct, and emergency municipal hotlines.
* [booking.html](file:///c:/MY%20PROJECTS/EL_NIDO_PALAWAN_WEBSITE/booking.html): Online booking and reservation engine with real-time fee calculation, printable E-Voucher modal, and client-side database management (`LocalDB`).
* [contact.html](file:///c:/MY%20PROJECTS/EL_NIDO_PALAWAN_WEBSITE/contact.html): Official contact details, physical address, business hours, and interactive digital inquiry form connected to LocalStorage.

---

### 3. Applied Business Tools & Technologies in Tourism (Rubric Compliance)
1. **Online Inquiry & Booking Engine:** Fast reservation workflow with automated booking reference generator (`EN-YYYY-XXXX`).
2. **Instant Trip Budget Estimator:** Real-time multi-currency calculator (PHP, USD, EUR, AUD) with dynamic add-ons (ETDF, Kayak, Van).
3. **Client-Side Database Storage (No SQL):** Uses HTML5 LocalStorage for bookings, inquiries, and reviews — zero database servers required, enabling static hosting on GitHub Pages.
4. **Interactive Embedded Mapping:** Responsive Google Maps embed with exact geographic coordinates of the NIPAP Municipal Office in Brgy. Buena Suerte.
5. **Customer Feedback & Review Module:** Real-time modal for submitting verified traveler testimonials directly saved into local storage.
6. **Mobile-First Responsive Framework:** Accessible on smartphones, tablets, and laptops.

---

## 🚀 How to Host on GitHub Pages

1. Initialize git in the project root:
   ```bash
   git init
   git add .
   git commit -m "Initial release of El Nido Tourism Platform"
   ```
2. Create a new repository on your GitHub account (e.g., `el-nido-tourism`).
3. Push your repository:
   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/el-nido-tourism.git
   git branch -M main
   git push -u origin main
   ```
4. Navigate to repository **Settings** &rarr; **Pages**.
5. Under **Branch**, select `main` and `/ (root)`, then click **Save**.
6. Your website will be live at `https://YOUR_USERNAME.github.io/el-nido-tourism/`.
