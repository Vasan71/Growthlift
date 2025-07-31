# GrowthLift - Digital Marketing Agency Website

A clean, fast-loading, and mobile-friendly website for a digital marketing agency named 'GrowthLift'. The website is designed to be conversion-focused, using the funnel technique to guide visitors from awareness to action.

## Features

- **Mobile-first responsive design** that looks great on all devices
- **Clean, professional UI** with rounded sections, attractive fonts, and a blue/white/green color scheme
- **Persuasive copywriting** focused on lead generation
- **Interactive elements** including smooth scroll, sticky header, and mobile menu
- **Working contact form** with validation
- **WhatsApp integration** for direct communication
- **Fast-loading optimized design**

## Pages

1. **Home** - Features a catchy headline, benefits of digital marketing, services section, testimonials, and strong call-to-action buttons
2. **Services** - Detailed information about SEO, Social Media Marketing, and Paid Advertising services
3. **About/Why Us** - Information about how GrowthLift helps businesses grow, trust-building points, and client logos
4. **Contact** - Simple form with Name, Email, Message fields, WhatsApp link, and contact information

## Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla)
- Tailwind CSS (via CDN)
- Font Awesome Icons

## Project Structure

```
├── index.html              # Home page
├── services.html           # Services page
├── about.html              # About/Why Us page
├── contact.html            # Contact page
├── css/
│   └── styles.css          # Custom CSS styles
├── js/
│   └── script.js           # JavaScript functionality
├── assets/                 # Images and other assets (to be added)
└── README.md               # Project documentation
```

## Setup and Deployment

### Local Development

1. Clone or download this repository
2. Open any of the HTML files in your browser to view the website
3. For the best experience, use a local server such as Live Server in VS Code

### Deployment

This website can be deployed to any web hosting service that supports static websites:

1. Upload all files and folders to your web hosting service
2. Ensure the file structure remains intact
3. The website should be immediately accessible

## Customization

### Images

Before deploying to production, replace the placeholder images in the `assets` folder with your own images. You can use royalty-free images from sources like Unsplash or Pexels.

### Contact Form

The contact form currently uses a simulated submission. To make it functional:

1. Create a server-side script to handle form submissions (PHP, Node.js, etc.)
2. Update the form action in `contact.html` to point to your script
3. Modify the JavaScript in `script.js` to handle the actual form submission

### WhatsApp Integration

Update the WhatsApp links with your actual WhatsApp business number:

```html
<a href="https://wa.me/YOUR_NUMBER_HERE" target="_blank">Chat on WhatsApp</a>
```

## Browser Compatibility

This website is compatible with all modern browsers including:

- Chrome
- Firefox
- Safari
- Edge

## License

This project is available for personal and commercial use.

---

Created with ❤️ for GrowthLift Digital Marketing Agency