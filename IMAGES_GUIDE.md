# How to Add Images to Your TravelMate Website

## ✅ I've Updated the Attraction Data!

All attraction information has been updated in `js/app.js` with:
- New ratings (out of 5 stars)
- Accurate pricing
- Opening hours
- Estimated time to spend
- Status (Free/Paid)
- Research notes

---

## 📸 How to Add Images

### Step 1: Get Your Images

**Recommended FREE image sources:**
1. **Unsplash** - https://unsplash.com/ (search "singapore marina bay")
2. **Pexels** - https://www.pexels.com/ (search "singapore attractions")
3. **Pixabay** - https://pixabay.com/ (search "singapore landmarks")

**What to download:**
- Gardens by the Bay
- Jewel Changi Rain Vortex
- Marina Bay Sands
- Merlion Park
- Buddha Tooth Relic Temple
- Kampong Glam / Haji Lane
- ArtScience Museum
- National Gallery
- Night Safari
- Singapore Zoo
- Haw Par Villa
- Henderson Waves
- Pulau Ubin
- Sentosa Beach
- Universal Studios Singapore

### Step 2: Save Images to the Folder

Save all downloaded images to the `images/` folder I just created with these names:
- `gardens-by-the-bay.jpg`
- `jewel-changi.jpg`
- `marina-bay-sands.jpg`
- `merlion.jpg`
- `buddha-tooth.jpg`
- `kampong-glam.jpg`
- `artscience-museum.jpg`
- `national-museum.jpg`
- `national-gallery.jpg`
- `sea-aquarium.jpg`
- `night-safari.jpg`
- `singapore-zoo.jpg`
- `haw-par-villa.jpg`
- `henderson-waves.jpg`
- `pulau-ubin.jpg`
- `sentosa-beaches.jpg`
- `universal-studios.jpg`

### Step 3: Update HTML to Use Images

Change this:
```html
<div class="card-image" style="background: linear-gradient(135deg, #8B4444, #A85858);"></div>
```

To this:
```html
<div class="card-image" style="background-image: url('images/gardens-by-the-bay.jpg');"></div>
```

### Example - Gardens by the Bay Card:

**BEFORE:**
```html
<article class="attraction-card" data-category="Iconic">
    <div class="card-image" style="background: linear-gradient(135deg, #4A7B5C, #5D9973);"></div>
    <div class="card-content">
        <h3>Gardens by the Bay</h3>
        ...
```

**AFTER:**
```html
<article class="attraction-card" data-category="Iconic">
    <div class="card-image" style="background-image: url('images/gardens-by-the-bay.jpg');"></div>
    <div class="card-content">
        <h3>Gardens by the Bay</h3>
        ...
```

---

## 🎨 Bonus: Add Overlay for Better Text Visibility

If you want to add a dark overlay so text shows better on images, update your CSS:

```css
.card-image {
    width: 100%;
    height: 200px;
    background-size: cover;
    background-position: center;
    border-radius: 12px 12px 0 0;
    position: relative;
}

/* Add overlay for better contrast */
.card-image::after {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background: linear-gradient(to bottom, transparent 0%, rgba(0,0,0,0.3) 100%);
    border-radius: 12px 12px 0 0;
}
```

---

## 🌟 Quick Checklist

- [x] Attraction data updated ✅
- [ ] Download images from Unsplash/Pexels
- [ ] Save images to `images/` folder with correct names
- [ ] Update HTML `<div class="card-image">` elements
- [ ] Test on your website

---

## 💡 Pro Tips

1. **Image size:** Keep images under 500KB each for fast loading
2. **Dimensions:** Use images around 800x600px or similar ratio
3. **Format:** JPG for photos, PNG for graphics
4. **Naming:** Use lowercase and hyphens (e.g., `marina-bay-sands.jpg`)

---

Need help? Let me know which images you need help finding or adding!
