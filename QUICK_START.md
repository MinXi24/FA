# 🚀 Quick Start Guide - TravelMate

## Welcome to TravelMate! 

This guide will help you launch your website in under 2 minutes.

---

## ✅ Option 1: Using VS Code Live Server (Recommended)

### Step 1: Install Live Server Extension
1. Open VS Code
2. Click the **Extensions** icon (or press `Ctrl+Shift+X`)
3. Search for **"Live Server"** by Ritwick Dey
4. Click **Install**

### Step 2: Launch the Website
1. Open `index.html` in VS Code
2. **Right-click** on the file
3. Select **"Open with Live Server"**
4. Your browser opens automatically at `http://localhost:5500` 🎉

### That's it! The website is now live and will auto-reload when you make changes.

---

## ✅ Option 2: Direct Browser Opening

### Simple Method (Limited Features)
1. Navigate to: `c:\C240 (Tue afternoon)\FA\`
2. **Double-click** `index.html`
3. Opens in your default browser

**Note**: Some JavaScript features may work better with a local server (Option 1).

---

## ✅ Option 3: Using PowerShell (Python Simple Server)

### If you have Python installed:
```powershell
cd 'c:\C240 (Tue afternoon)\FA'
python -m http.server 8000
```

Then open: `http://localhost:8000` in your browser

---

## 📱 Features to Explore

### 1. **Navigation**
- Click the top menu to jump between sections
- Try the mobile hamburger menu (resize window)

### 2. **Attraction Cards**
- Click **"Learn More"** buttons for detailed info
- Hover over cards to see animations

### 3. **Interactive Modal**
- Read full attraction details
- Press `ESC` or click outside to close

### 4. **Smooth Scrolling**
- Notice the smooth transitions between sections
- Navbar changes when you scroll

### 5. **Responsive Design**
- Resize your browser window
- Try on mobile (open on your phone)

---

## 🎨 Making Changes

### Edit Colors
Open `css/styles.css` and modify the CSS variables at the top:
```css
:root {
    --primary-red: #8B4444;     /* Change this! */
    --primary-green: #5B7854;   /* Change this! */
}
```

### Edit Content
Open `index.html` and modify:
- Attraction names
- Descriptions
- Add new sections

### Edit Functionality
Open `js/app.js` to modify:
- Modal behavior
- Navigation logic
- Add new features

**Tip**: With Live Server running, changes appear instantly in your browser!

---

## 🐛 Troubleshooting

### Website Won't Load?
- ✅ Check if `index.html` is in the correct folder
- ✅ Ensure all folders (`css/`, `js/`) are present
- ✅ Try restarting Live Server

### Styles Not Showing?
- ✅ Check `css/styles.css` exists
- ✅ Verify the `<link>` tag in `index.html`
- ✅ Clear browser cache (`Ctrl+F5`)

### JavaScript Not Working?
- ✅ Open browser console (`F12`)
- ✅ Check for error messages
- ✅ Ensure `js/app.js` is linked correctly

---

## 📚 Documentation

- **README.md** - Complete project documentation
- **PROJECT_BRIEF.md** - Product brief and research
- **index.html** - Main HTML structure
- **css/styles.css** - All styling (800+ lines)
- **js/app.js** - Interactive features (500+ lines)

---

## 🎯 Next Steps

### Explore Singapore Attractions
1. **Iconic Landmarks** - Marina Bay Sands, Gardens by the Bay
2. **Cultural Sites** - Chinatown, Little India, Kampong Glam
3. **Museums** - National Museum, ArtScience Museum
4. **Hidden Gems** - Haji Lane, Pulau Ubin, MacRitchie

### Customize Your Site
1. Add more attractions
2. Change colors to your preference
3. Add your own photos
4. Implement new JavaScript features

### Share Your Work
1. Take screenshots
2. Share the live URL (if deployed)
3. Get feedback from friends
4. Iterate and improve!

---

## 🌟 Success Checklist

- [ ] Website loads successfully
- [ ] All sections are visible
- [ ] Navigation works smoothly
- [ ] Modal popups function correctly
- [ ] Mobile view looks good
- [ ] Colors are balanced and appetizing
- [ ] Content is readable and informative

---

## 💡 Tips for Presentation

1. **Demo the mobile menu** - Shows responsive design
2. **Click "Learn More"** - Demonstrates interactivity
3. **Explain color choices** - Red (excitement) + Green (nature)
4. **Highlight accessibility** - Keyboard navigation, contrast
5. **Show code quality** - Clean, documented, organized

---

## 🎉 Congratulations!

You've successfully created **TravelMate**, an AI-powered guide for exchange students exploring Singapore!

**Features Completed:**
✅ 16 detailed attractions with research  
✅ Balanced red/green/white design  
✅ Interactive JavaScript features  
✅ Responsive mobile design  
✅ Accessibility compliance  
✅ Performance optimizations  
✅ Git version control  
✅ Comprehensive documentation  

---

## 📞 Need Help?

- Check the **README.md** for detailed info
- Review **PROJECT_BRIEF.md** for design rationale
- Inspect browser console for errors (`F12`)
- Validate HTML at https://validator.w3.org/

---

**Enjoy exploring Singapore with TravelMate!** 🌏✨

*Built with ❤️ for Republic Polytechnic Exchange Students*
