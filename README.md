# SunFront Energy - Static Website

A static website for SunFront Energy Pvt. Ltd., a leading solar power producer company in India.

## Hosting on GitHub Pages

### Method 1: Using the `static` folder directly

1. Create a new GitHub repository
2. Copy the contents of the `static` folder to your repository
3. Go to **Settings** → **Pages**
4. Under "Source", select **Deploy from a branch**
5. Select the `main` branch and `/ (root)` folder
6. Click **Save**
7. Your site will be available at `https://yourusername.github.io/repository-name/`

### Method 2: Using the `static` folder as a subdirectory

1. Push your entire project to GitHub
2. Go to **Settings** → **Pages**
3. Under "Source", select **Deploy from a branch**
4. Select the `main` branch and `/static` folder (if available) or use GitHub Actions

## Contact Form Setup

The contact forms use Formspree for handling submissions on static sites. To set up:

1. Go to [Formspree.io](https://formspree.io/)
2. Create a free account
3. Create a new form and get your form ID
4. Replace `your-form-id` in the form action URLs in `index.html`:
   ```html
   action="https://formspree.io/f/YOUR-FORM-ID"
   ```

Alternatively, you can use other static form services like:
- [Netlify Forms](https://www.netlify.com/products/forms/)
- [Getform](https://getform.io/)
- [FormSubmit](https://formsubmit.co/)

## File Structure

```
static/
├── index.html          # Main homepage
├── favicon.ico         # Site favicon
├── css/
│   ├── style.css       # Main stylesheet
│   ├── bootstrap.css   # Bootstrap framework
│   ├── font.css        # Font definitions
│   └── ...
├── js/
│   ├── core.min.js     # Core JavaScript
│   ├── script.js       # Main scripts
│   └── ...
├── img/
│   ├── logo1.png       # Company logo
│   ├── uploads/        # Slider images
│   └── ...
└── font/
    └── ...             # Custom fonts
```

## Features

- Responsive design
- Hero slider with solar images
- About section
- Products & Services showcase
- FAQ carousel
- Contact form with quote request
- Social media links
- Mobile-friendly navigation

## Technologies Used

- HTML5
- CSS3
- JavaScript/jQuery
- Font Awesome icons
- Google Fonts
- Swiper.js for sliders
- WOW.js for animations

## License

Copyright © SunFront Energy Pvt. Ltd. All rights reserved.
