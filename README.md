# TechFuture Summit 2026 - Event Landing Page

A modern, responsive event landing page built with HTML, CSS, and JavaScript. Features a countdown timer, interactive schedule, speaker profiles, and registration form.

![Event Landing Page](https://img.shields.io/badge/Status-Ready%20to%20Deploy-success)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## ✨ Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Countdown Timer**: Real-time countdown to the event date
- **Interactive Schedule**: Tabbed interface for multi-day event schedule
- **Speaker Profiles**: Showcase of featured speakers with hover effects
- **Registration Form**: Full-featured form with validation
- **Smooth Animations**: Scroll-triggered animations and transitions
- **Modern UI**: Clean, professional design with gradient accents
- **Accessible**: Semantic HTML and keyboard navigation support

## 📂 Project Structure

```
event-landing-page/
├── index.html          # Main HTML file
├── styles.css          # CSS styling and responsive design
├── script.js           # JavaScript for interactivity
└── README.md           # Project documentation
```

## 🚀 Quick Start

### Local Development

1. Clone or download this repository
2. Open `index.html` in your web browser
3. No build process required - it's a static site!

### Live Preview

Simply open the `index.html` file in any modern web browser to see the site in action.

## 🌐 Deploying to GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the **+** icon in the top right and select **New repository**
3. Name your repository (e.g., `event-landing-page`)
4. Choose **Public** (required for free GitHub Pages)
5. Click **Create repository**

### Step 2: Upload Your Files

#### Option A: Using GitHub Web Interface

1. In your new repository, click **uploading an existing file**
2. Drag and drop all files:
   - `index.html`
   - `styles.css`
   - `script.js`
   - `README.md`
3. Scroll down and click **Commit changes**

#### Option B: Using Git Command Line

```bash
# Initialize git in your project folder
git init

# Add all files
git add .

# Commit the files
git commit -m "Initial commit: Event landing page"

# Add your GitHub repository as remote
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. In your repository, click **Settings**
2. Scroll down to **Pages** in the left sidebar
3. Under **Source**, select **main** branch
4. Select **/ (root)** folder
5. Click **Save**

### Step 4: Access Your Live Site

- Your site will be live at: `https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/`
- It may take 1-2 minutes for the site to deploy
- GitHub will show you the URL once it's ready

## 🎨 Customization Guide

### Changing Event Details

Edit `index.html` to update:
- Event name, date, and location
- Speaker information
- Schedule items
- Pricing tiers

### Updating Colors

In `styles.css`, modify the CSS variables at the top:

```css
:root {
    --primary-color: #6366f1;      /* Main brand color */
    --secondary-color: #ec4899;    /* Accent color */
    --dark-bg: #0f172a;            /* Dark backgrounds */
    --light-bg: #f8fafc;           /* Light backgrounds */
}
```

### Changing the Event Date

In `script.js`, find the countdown timer section:

```javascript
const eventDate = new Date('2026-03-15T09:00:00').getTime();
```

Change the date to your event date.

### Modifying Content Sections

Each section is clearly marked in `index.html`:
- Hero Section: Lines 29-73
- About Section: Lines 75-105
- Speakers Section: Lines 107-165
- Schedule Section: Lines 167-298
- Registration Section: Lines 300-413

## 📱 Responsive Breakpoints

- **Desktop**: > 768px
- **Tablet**: 480px - 768px
- **Mobile**: < 480px

## 🔧 Technical Details

### Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Flexbox, Grid, Custom Properties, Animations
- **JavaScript ES6+**: Modern syntax, DOM manipulation

### Key Features Implementation

#### Countdown Timer
- Real-time countdown using `setInterval`
- Automatically updates every second
- Shows days, hours, minutes, and seconds

#### Schedule Tabs
- Pure JavaScript tab switching
- Smooth transitions between days
- Responsive mobile layout

#### Form Validation
- Client-side validation
- Email format checking
- Required field validation
- Success message display

#### Scroll Animations
- Intersection Observer API
- Fade-in effects on scroll
- Parallax hero section

## 🐛 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📝 To-Do / Future Enhancements

- [ ] Add backend integration for form submission
- [ ] Implement email notifications
- [ ] Add Google Maps integration for venue
- [ ] Create admin dashboard for event management
- [ ] Add social media sharing buttons
- [ ] Implement ticket payment processing
- [ ] Add image gallery section
- [ ] Create sponsor showcase section

## 🤝 Contributing

Feel free to fork this project and customize it for your own events! If you make improvements, consider submitting a pull request.

## 📄 License

This project is open source and available under the MIT License.

## 👤 Author

Created as a modern event landing page template.

## 🙏 Acknowledgments

- Icons: Custom SVG icons
- Fonts: System fonts for optimal performance
- Color Palette: Modern gradient design inspired by contemporary UI trends

## 📞 Support

For questions or issues:
1. Check the browser console for errors
2. Ensure all files are in the same directory
3. Verify your GitHub Pages settings
4. Make sure the repository is public

---

**Happy coding! 🚀**

