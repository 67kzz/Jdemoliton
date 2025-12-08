# J Demolition & Clearance Website

Professional waste clearance and demolition services website for London and surrounding areas.

## 🎨 Design Features

- **Clean, Modern Design** - Professional white and green color scheme
- **Fully Responsive** - Works perfectly on desktop, tablet, and mobile devices
- **Smooth Animations** - Elegant scroll effects and hover interactions
- **Project Galleries** - Dedicated sections to showcase clearance and demolition projects
- **Contact Form** - Easy-to-use quote request form

## 📂 File Structure

```
Jdemoliton/
├── index.html          # Main HTML file
├── styles.css          # All styling (white & green theme)
├── script.js           # Interactive functionality
└── README.md           # This file
```

## 🎯 Website Sections

### 1. **Navigation Bar**
- Fixed header with smooth scrolling
- Links to all major sections
- "Get Quote" call-to-action button

### 2. **Hero Section**
- Full-screen welcome banner
- Key features display (Licensed, 24/7 Service, London Coverage)
- Primary and secondary action buttons

### 3. **Services Overview**
- Four service cards:
  - House Clearance
  - Commercial Clearance
  - Garden Waste
  - Demolition Services

### 4. **Clearance Section**
- Detailed service description
- 6 key features with checkmarks
- Photo gallery with 6 project examples:
  - Full House Clearance
  - Office Clearance
  - Garden Clearance
  - Estate Clearance
  - Retail Unit Clearance
  - Warehouse Clearance

### 5. **Demolition Section**
- Comprehensive demolition services overview
- 6 key service features
- Photo gallery with 6 project examples:
  - Commercial Building Demolition
  - Interior Strip-Out
  - Residential Demolition
  - Industrial Demolition
  - Structural Demolition
  - Complete Site Clearance

### 6. **Contact Section**
- Contact information display
- Coverage areas (London boroughs and surrounding counties)
- Quote request form with fields:
  - Full Name
  - Email Address
  - Phone Number
  - Service Required (dropdown)
  - Project Details (textarea)

### 7. **Footer**
- Company information
- Service links
- Legal links
- Copyright information

## 🎨 Color Scheme

- **Primary Green**: #22c55e
- **Dark Green**: #16a34a
- **Light Green**: #4ade80
- **Accent Green**: #10b981
- **White**: #ffffff
- **Light Gray**: #f9fafb
- **Dark Gray**: #1f2937

## 🚀 How to Use

1. **Open the website**:
   - Simply open `index.html` in any modern web browser
   - Or host on any web server

2. **Customize content**:
   - Edit `index.html` to update text, images, and contact information
   - Replace phone number: Search for "020 XXXX XXXX"
   - Update email: Search for "info@jdemolition.co.uk"

3. **Update images**:
   - Current images are from Unsplash (free stock photos)
   - Replace URLs in `index.html` with your actual project photos
   - Format: `<img src="your-image-url.jpg" alt="description">`

4. **Modify colors**:
   - All colors are defined in `:root` variables in `styles.css`
   - Change `--primary-green` to update the main brand color

## 📝 Customization Guide

### Adding New Projects

Find the `.project-gallery` section and add:

```html
<div class="project-card">
    <div class="project-image">
        <img src="your-image-url.jpg" alt="Project Name">
        <div class="project-overlay">
            <h4>Project Title</h4>
            <p>Project description</p>
        </div>
    </div>
</div>
```

### Changing Contact Information

Edit the contact details in the contact section:

```html
<div class="contact-item">
    <svg>...</svg>
    <div>
        <h4>Phone</h4>
        <p>Your phone number</p>
    </div>
</div>
```

### Updating Service Areas

Modify the coverage area tags:

```html
<div class="area-tags">
    <span>Your Area 1</span>
    <span>Your Area 2</span>
    <!-- Add more areas -->
</div>
```

## 🔧 Form Integration

The contact form currently shows an alert on submission. To connect to a backend:

1. Open `script.js`
2. Find the form submission handler
3. Uncomment and configure the `fetch()` API call
4. Point it to your backend endpoint

Example:
```javascript
fetch('/api/contact', {
    method: 'POST',
    headers: { 'Content-Type': 'application/json' },
    body: JSON.stringify(data)
})
```

## 📱 Responsive Breakpoints

- **Desktop**: 1024px and above
- **Tablet**: 768px - 1023px
- **Mobile**: Below 768px

## ✨ Features

- ✅ Smooth scroll navigation
- ✅ Active section highlighting
- ✅ Hover animations on cards and buttons
- ✅ Image hover effects in galleries
- ✅ Form validation
- ✅ Intersection Observer animations
- ✅ SEO-friendly semantic HTML
- ✅ Accessibility features

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📞 Support

For questions or modifications, contact your web developer.

## 📄 License

© 2025 J Demolition & Clearance. All rights reserved.

---

**Built with modern web technologies for optimal performance and user experience.**
