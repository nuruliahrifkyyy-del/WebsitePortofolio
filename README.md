# Portfolio Website - Nuruliah Rifky

A modern, creative, and fully responsive portfolio website built with pure HTML, CSS, and JavaScript following Responsive Web Design (RWD) principles.

## 🎨 Features

- **3 Integrated Pages:**
  - Home/Landing Page (index.html)
  - Portfolio/Projects Page (portfolio.html)
  - Contact Page (contact.html)

- **Modern Design:**
  - Creative and colorful aesthetic with purple and pink gradients
  - Clean layout with excellent typography
  - Smooth animations and hover effects
  - Professional dark footer

- **Fully Responsive:**
  - Mobile-first design approach
  - Works seamlessly on desktop, tablet, and mobile devices
  - Responsive navigation with mobile hamburger menu
  - Responsive table that transforms into cards on mobile

- **Interactive Features:**
  - Smooth scrolling navigation
  - Project search and filter functionality
  - Interactive contact form with validation
  - Success modal on form submission
  - Animated skill progress bars
  - Scroll-triggered animations

## 📁 Project Structure

```
portfolio-site/
├── index.html           # Home page with hero, about, and skills sections
├── portfolio.html       # Portfolio page with projects table
├── contact.html         # Contact page with form
├── css/
│   └── style.css       # All styles and responsive design
└── js/
    └── script.js       # All JavaScript functionality
```

## 🚀 Getting Started

### Option 1: Open Locally
Simply open `index.html` in your web browser.

### Option 2: Using Python HTTP Server
```bash
cd portfolio-site
python3 -m http.server 8080
```
Then visit: http://localhost:8080

### Option 3: Using Node.js HTTP Server
```bash
cd portfolio-site
npx http-server -p 8080
```
Then visit: http://localhost:8080

## 📄 Page Details

### 1. Home Page (index.html)
- **Header:** Consistent navigation with logo and links
- **Hero Section:** Profile photo, tagline, and call-to-action buttons
- **About Me Section:** Background, education, interests, and highlights
- **Skills Section:** Technical skills with animated progress bars
- **Footer:** Links to social media and ITPLN website

### 2. Portfolio Page (portfolio.html)
- **Page Header:** Clear title and description
- **Search & Filter:** Real-time project search and status filtering
- **Projects Table:** 8 projects with:
  - Project name with colored icons
  - Year created
  - Technologies used (with tags)
  - Status (Completed/In Progress)
  - Demo link
- **Responsive Table:** Transforms into card layout on mobile

### 3. Contact Page (contact.html)
- **Page Header:** Welcoming message
- **Contact Information:** Email, phone, location with icons
- **Social Links:** GitHub, LinkedIn, Twitter, Instagram
- **Project Request Form:**
  - Text inputs (Name, Email)
  - Dropdown (Project Type, Budget Range)
  - Radio buttons (Timeline)
  - Textarea (Project Description)
  - Checkboxes (Newsletter, Terms)
  - Submit button with modal confirmation

## 🎨 Design Highlights

- **Color Scheme:**
  - Primary: Purple (#8B5CF6) to Pink (#EC4899) gradients
  - Background: White with subtle gradient overlays
  - Text: Dark (#0a0a0a) with gray variations
  - Accents: Colorful gradients for icons and badges

- **Typography:**
  - Headings: Poppins (Bold, Modern)
  - Body: Inter (Clean, Readable)

- **Animations:**
  - Fade-in on scroll
  - Hover effects on buttons and cards
  - Smooth transitions
  - Floating badges animation
  - Progress bar fill animation

## 🔧 Technical Details

- **HTML5:** Semantic markup with proper meta tags
- **CSS3:** 
  - Flexbox and CSS Grid for layouts
  - Custom properties for colors
  - Media queries for responsive design
  - Smooth animations and transitions
- **JavaScript:**
  - Vanilla JS (no frameworks)
  - Mobile menu toggle
  - Search and filter functionality
  - Form validation and submission
  - Scroll animations with Intersection Observer
  - Smooth scrolling

## 📱 Responsive Breakpoints

- Desktop: 1024px and above
- Tablet: 768px - 1024px
- Mobile: Below 768px

## ✅ Requirements Met

✓ 3 integrated pages with consistent navigation  
✓ Modern, attractive design with clean layout  
✓ Consistent color palette and typography  
✓ Hero section with profile photo and tagline  
✓ About Me section with background and education  
✓ Skills section with progress bars  
✓ Responsive table with 8 projects (exceeds minimum of 5)  
✓ Mobile-friendly table (no horizontal scrolling)  
✓ Contact form with all required elements  
✓ Form validation and user-friendly design  
✓ Flexbox and CSS Grid for layouts  
✓ Fully responsive for desktop and mobile  
✓ Hover effects and smooth animations  
✓ Favicon and semantic HTML  
✓ Footer with ITPLN link  

## 🌐 Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📝 Customization

To customize this portfolio for your own use:

1. **Update personal information:**
   - Change name, tagline, and bio in HTML files
   - Update profile photo URL in index.html
   - Modify contact information in contact.html

2. **Update projects:**
   - Edit the projects table in portfolio.html
   - Add your real projects with actual technologies

3. **Customize colors:**
   - Modify gradient colors in CSS
   - Update the color scheme to match your brand

4. **Add real functionality:**
   - Connect the contact form to a backend service
   - Add real project demo links
   - Integrate with analytics

## 📜 License

This project is open source and available for personal and educational use.

## 🙏 Credits

- Profile photo: [pravatar.cc](https://pravatar.cc)
- Fonts: Google Fonts (Inter & Poppins)
- Icons: CSS-based custom icons
- Powered by: [ITPLN](https://itpln.id)

---

**Note:** This is a demonstration portfolio with dummy data. Replace all placeholder content with your actual information before deploying.
