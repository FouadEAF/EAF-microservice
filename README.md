# EAF Microservice Portfolio

A modern, multi-language portfolio and agency website built with HTML, CSS (SCSS), JavaScript, and popular frontend libraries. This project is ideal for freelancers, agencies, or small businesses seeking a visually appealing, responsive, and easily customizable web presence.

## Features

- **Multi-language support:** Arabic, English, and French (see `assets/lang/`)
- **Responsive design:** Built with Bootstrap for mobile and desktop compatibility
- **Modern UI/UX:** Uses AOS, Swiper, GLightbox, Isotope, and more
- **Portfolio, Blog, and Service pages:** Modular structure for easy expansion
- **Contact and Newsletter forms:** PHP backend scripts for form handling
- **Well-organized assets:** Images, CSS, JS, and vendor libraries separated for clarity

## Project Structure

```
assets/
  css/         # Compiled CSS files
  js/          # Main JavaScript files
  scss/        # (If used) Source SCSS files
  img/         # All images (backgrounds, portfolio, blog, etc.)
  lang/        # Language JSON files (ar, en, fr)
  vendor/      # Third-party libraries (Bootstrap, AOS, Swiper, etc.)
forms/
  contact.php  # Handles contact form submissions
  newsletter.php # Handles newsletter form submissions
index.html     # Main landing page
pages/         # Additional HTML pages (blog, portfolio, 404, etc.)
```

## Getting Started

1. **Clone or download the repository.**
2. **Open `index.html` in your browser** to view the site locally.
3. **To use contact/newsletter forms:**
   - Ensure your server supports PHP.
   - Configure `forms/contact.php` and `forms/newsletter.php` as needed for your email setup.

## Customization

- **Languages:** Edit or add JSON files in `assets/lang/`.
- **Images:** Replace or add images in `assets/img/`.
- **Styles:** Modify SCSS/CSS in `assets/scss/` or `assets/css/`.
- **Content:** Edit HTML files in the root or `pages/` directory.

## Dependencies

- [Bootstrap](https://getbootstrap.com/)
- [AOS (Animate On Scroll)](https://michalsnik.github.io/aos/)
- [Swiper](https://swiperjs.com/)
- [GLightbox](https://biati-digital.github.io/glightbox/)
- [Isotope](https://isotope.metafizzy.co/)
- [Waypoints](http://imakewebthings.com/waypoints/)
- [ImagesLoaded](https://imagesloaded.desandro.com/)
- [Bootstrap Icons](https://icons.getbootstrap.com/)

All dependencies are included in `assets/vendor/` for offline use.

## Deployment

- Upload the project to any static web host (Netlify, Vercel, GitHub Pages, etc.).
- For form functionality, deploy to a PHP-enabled server.

## License

Specify your license here (e.g., MIT, GPL, etc.).

---

**Feel free to customize this README and the project to fit your needs!**
