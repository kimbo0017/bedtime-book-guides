# 🚀 Kimbo's Author Website - Setup Guide

## ✅ Project Complete!

Your professional children's book author website is ready to launch!

---

## 📊 What's Included

### 🌐 Website Files
- ✅ **index.html** - Full homepage with all sections
- ✅ **styles.css** - Beautiful, responsive styling
- ✅ **script.js** - Interactive features & forms

### 📚 Downloadable Teacher & Parent Guides (4 PDF files)
- ✅ **reading-guide.pdf** - Discussion questions & activities
- ✅ **activity-worksheets.pdf** - Coloring pages & exercises
- ✅ **science-experiments.pdf** - Hands-on experiments
- ✅ **classroom-activities.pdf** - Group performance activities

### 📖 Complete Documentation
- ✅ **README.md** - Full customization guide
- ✅ This setup guide!

---

## 🎯 Quick Start (3 Steps)

### Step 1: Enable GitHub Pages (5 minutes)
```
1. Go to: https://github.com/kimbo0017/bedtime-book-guides/settings
2. Click "Pages" on the left sidebar
3. Select "Deploy from a branch"
4. Choose "main" branch
5. Click "Save"
```

**Your live site:** `https://kimbo0017.github.io/bedtime-book-guides`

---

### Step 2: Add Your YouTube Videos (10 minutes)
In `index.html`, find and replace YouTube video IDs:

**Current placeholder:** `dQw4w9WgXcQ`

**To get your video ID:**
1. Go to your YouTube video
2. URL looks like: `https://www.youtube.com/watch?v=YOUR_ID_HERE`
3. Copy the ID after `v=`
4. Replace all 6 instances in index.html

**Search for this line (appears 6 times):**
```html
<iframe src="https://www.youtube.com/embed/dQw4w9WgXcQ"
```

**Replace with your video ID:**
```html
<iframe src="https://www.youtube.com/embed/YOUR_VIDEO_ID"
```

---

### Step 3: Customize Your Content (15 minutes)

#### Change Author Name
- Open `index.html`
- Find: `<h1>✨ Kimbo's Books</h1>`
- Change to your name

#### Update Book Information
- Find the "Featured Books" section
- Edit book titles, descriptions, ages, pages
- Update Amazon links to your book pages

#### Change Colors (Optional)
- Open `styles.css`
- Find colors like `#667eea` (purple), `#ff6b6b` (red)
- Use https://htmlcolorcodes.com to pick new colors
- Replace throughout the file

---

## 📁 File Structure

```
bedtime-book-guides/
├── index.html                    # Main homepage
├── styles.css                    # All styling
├── script.js                     # Interactive features
├── README.md                     # Customization guide
├── SETUP.md                      # This file
└── guides/                       # Teacher & Parent Downloads
    ├── reading-guide.pdf
    ├── activity-worksheets.pdf
    ├── science-experiments.pdf
    └── classroom-activities.pdf
```

---

## 🎨 Website Sections

### 1. Navigation Bar
- Links to all sections
- Smooth scrolling
- Mobile responsive

### 2. Hero Section
- Welcome message
- Call-to-action button
- Eye-catching design

### 3. Featured Books
- Book 1: The Bedtime Book of Impossible Questions
- Book 2: Shh! We Have a Plan
- Coming soon teaser

### 4. Video Section ⭐ NEW!
- 6 embedded YouTube video slots:
  - Book trailer
  - Full story reading
  - Behind the scenes
  - Reading tips for parents
  - Animation process
  - Q&A with author

### 5. Teacher & Parent Guides
- 4 downloadable PDFs
- Free resources for educators

### 6. About Section
- Author bio
- Mission statement

### 7. Newsletter Signup
- Email capture form
- Welcome message

### 8. Contact Form
- Direct messaging
- Mobile friendly

### 9. Footer
- Social media links
- Copyright info

---

## 🔧 How to Edit Files

### Online (Easiest)
1. Go to https://github.com/kimbo0017/bedtime-book-guides
2. Click on any file
3. Click the pencil ✏️ icon
4. Make changes
5. Click "Commit changes"

### Locally (Advanced)
```bash
# Clone the repository
git clone https://github.com/kimbo0017/bedtime-book-guides.git
cd bedtime-book-guides

# Edit files in your code editor

# Upload changes
git add .
git commit -m "Your message here"
git push origin main
```

---

## 🎥 Video Setup Details

The video section includes 6 card layouts, each with:
- Responsive iframe for YouTube embeds
- Video title
- Description text
- Category tags (e.g., "Trailer", "Science", "Adventure")

**To replace videos:**
1. Each iframe has this format:
   ```html
   <iframe src="https://www.youtube.com/embed/VIDEO_ID"></iframe>
   ```

2. You can also change:
   - Video title (h3 tag)
   - Description
   - Tags

---

## 📧 Contact Form Options

### Option 1: Simple (Current Setup)
- Shows thank you message
- No email sending
- Good for testing

### Option 2: Formspree (Free Email Service)
1. Visit https://formspree.io
2. Sign up with your email
3. Create new form
4. Copy form endpoint
5. Update `index.html` form action with your endpoint

```html
<form class="contact-form" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

---

## 📱 Testing Your Site

### Desktop
- Open in Chrome, Firefox, Safari
- Check all links work
- Test forms

### Mobile
- View on phone/tablet
- Check responsiveness
- Tap all buttons

### Video Testing
- Replace one YouTube ID to test
- Make sure iframe loads properly

---

## 🚀 Launch Checklist

- [ ] GitHub Pages enabled
- [ ] Site is live at your GitHub Pages URL
- [ ] YouTube video IDs added (all 6)
- [ ] Author name customized
- [ ] Book information updated
- [ ] Amazon links added
- [ ] About section updated with your bio
- [ ] Newsletter form tested
- [ ] Contact form tested
- [ ] Colors customized (optional)
- [ ] Tested on mobile
- [ ] Shared on social media!

---

## 💡 Pro Tips

1. **Video SEO:** Use descriptive titles and descriptions for each video
2. **Mobile First:** Test on phone before desktop
3. **Regular Updates:** Add new videos and content regularly
4. **Newsletter:** Keep subscribers engaged with new releases
5. **Social Sharing:** Add buttons to share content on social media
6. **Analytics:** Consider adding Google Analytics (optional)

---

## 🆘 Troubleshooting

### Site Won't Load After GitHub Pages Enable
- Wait 5-10 minutes for deployment
- Check Settings → Pages confirms main branch selected
- Refresh browser cache (Ctrl+Shift+Del)

### Videos Not Showing
- Verify YouTube video ID is correct
- Check iframe syntax: `src="https://www.youtube.com/embed/VIDEO_ID"`
- Make sure YouTube video is public (not private/unlisted)

### Forms Not Working
- Check browser console for errors (F12)
- Verify form element IDs match JavaScript code
- Test in different browser

### Styling Looks Wrong
- Clear browser cache
- Check that styles.css file uploaded correctly
- Verify file paths in HTML

---

## 📞 Support Resources

- **GitHub Pages Help:** https://pages.github.com
- **YouTube Embed Guide:** https://www.youtube.com/embed/help
- **HTML/CSS Tutorial:** https://www.w3schools.com
- **Formspree Docs:** https://formspree.io/docs
- **GitHub Issues:** Ask in repository issues

---

## 🎉 Next Steps

1. ✅ Enable GitHub Pages
2. ✅ Add your YouTube videos
3. ✅ Customize content
4. ✅ Test thoroughly
5. ✅ Share your website!

---

## 📝 Notes

- All PDF guides are ready for download
- Website is fully responsive (mobile-friendly)
- Dark mode friendly color scheme
- Accessibility features included
- No coding required to customize!

---

**Your website is ready to inspire young readers! Happy launching! 🚀📚✨**

For more detailed customization, see `README.md`
