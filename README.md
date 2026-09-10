# Kimbo's Children's Book Author Website

Welcome to the official website for Kimbo's children's books including "The Bedtime Book of Impossible Questions" and "Shh! We Have a Plan"!

## 📚 Features

- **Beautiful Homepage** with hero section and featured books
- **Video Section** with embedded YouTube videos for trailers and readings
- **Teacher & Parent Guides** with downloadable PDF resources
- **Newsletter Signup** to keep readers updated
- **Contact Form** for inquiries and messages
- **Fully Responsive** design that works on all devices

## 🚀 Deployment (GitHub Pages)

This website is hosted on GitHub Pages for free! Here's how to enable it:

### Step 1: Enable GitHub Pages
1. Go to your repository: https://github.com/kimbo0017/bedtime-book-guides
2. Click **Settings** (top right)
3. Scroll down to **Pages** section (left sidebar)
4. Under "Source", select **Deploy from a branch**
5. Select branch: **main**
6. Select folder: **/ (root)**
7. Click **Save**

### Step 2: Your Site is Live! 🎉
Your website will be available at:
```
https://kimbo0017.github.io/bedtime-book-guides
```

It may take a few minutes to deploy. Refresh the page to see your live site!

## 📁 Project Structure

```
bedtime-book-guides/
├── index.html          # Main homepage
├── styles.css          # All styling
├── script.js           # Interactive features
├── books/              # Individual book pages
│   ├── bedtime-book.html
│   └── shh-plan.html
├── guides/             # PDF guides for download
│   ├── reading-guide.pdf
│   ├── activity-worksheets.pdf
│   ├── science-experiments.pdf
│   └── classroom-activities.pdf
└── README.md           # This file
```

## 🎥 How to Add Your YouTube Videos

Replace the YouTube embed links in `index.html`:

1. Find this line (appears 6 times):
   ```html
   <iframe src="https://www.youtube.com/embed/dQw4w9WgXcQ" ...>
   ```

2. Replace `dQw4w9WgXcQ` with your actual YouTube video ID:
   - Go to your YouTube video
   - The URL looks like: `https://www.youtube.com/watch?v=YOUR_VIDEO_ID`
   - Use `YOUR_VIDEO_ID` in the embed link

3. Example:
   ```html
   <iframe src="https://www.youtube.com/embed/YOUR_VIDEO_ID" ...>
   ```

## 📝 How to Create & Add PDF Guides

### Option 1: Using Google Docs (Free)
1. Create your guide in Google Docs
2. File → Download → PDF Document
3. Save to your computer
4. Upload to the `guides/` folder in the repository

### Option 2: Create PDFs Locally
1. Create your guide in Word/Google Docs
2. Export/Save as PDF
3. Upload to the `guides/` folder

### How to Upload Files:
1. Go to the `guides/` folder in your repository
2. Click **Add file** → **Upload files**
3. Select your PDF files
4. Commit the changes

## 🎨 How to Customize Your Site

### Change Author Name:
1. Open `index.html`
2. Find the logo section and change "✨ Kimbo's Books" to your preferred title
3. Update the About section with your bio

### Change Book Information:
1. Open `index.html`
2. Look for the book cards in the "Featured Books" section
3. Edit:
   - Book titles (h3 tags)
   - Descriptions
   - Age ranges
   - Page counts
   - Amazon links

### Change Colors:
1. Open `styles.css`
2. Look for color codes like `#667eea` (purple) and `#ff6b6b` (red)
3. Use a color picker to find new colors
4. Replace the hex codes throughout the file

### Add Your Email to Contact Form:
1. Open `index.html`
2. Find the `handleContactForm` function in the script section
3. Add your email handling logic (or use a service like Formspree)

## 📧 Contact Form Setup (Optional)

To make the contact form send emails, use **Formspree** (free service):

1. Go to https://formspree.io
2. Sign up with your email
3. Create a new form
4. Copy the form endpoint
5. In `index.html`, update the form:
   ```html
   <form class="contact-form" action="YOUR_FORMSPREE_URL" method="POST">
   ```

## 🔧 Editing Tips

### To Edit Files Online:
1. Go to your repository
2. Click on any file (e.g., `index.html`)
3. Click the pencil icon (✏️) to edit
4. Make your changes
5. Click "Commit changes" to save

### To Edit Locally:
1. Clone the repository:
   ```bash
   git clone https://github.com/kimbo0017/bedtime-book-guides.git
   cd bedtime-book-guides
   ```
2. Edit files in your favorite code editor
3. Upload changes to GitHub

## 📱 Mobile Responsive

The website automatically adjusts for:
- Desktop computers
- Tablets
- Mobile phones

No additional setup needed!

## 🎯 To-Do List

- [ ] Enable GitHub Pages deployment
- [ ] Replace YouTube video IDs with your actual videos
- [ ] Create and upload PDF guides
- [ ] Update author bio in About section
- [ ] Add book cover images (optional)
- [ ] Set up contact form with Formspree (optional)
- [ ] Customize colors to match your brand
- [ ] Add social media links in footer
- [ ] Test on mobile devices
- [ ] Share your website!

## 📞 Need Help?

Check out these resources:
- GitHub Pages Documentation: https://pages.github.com
- YouTube Embed Guide: https://www.youtube.com/embed/help
- Formspree: https://formspree.io
- Color Picker: https://htmlcolorcodes.com

## 📄 License

This website template is open for your personal use. Feel free to customize it for your book business!

---

**Happy Writing! 📚✨**
