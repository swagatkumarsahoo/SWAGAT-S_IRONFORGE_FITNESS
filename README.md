# SWAGAT'S_IRONFORGE_FITNESS

A modern, responsive single-page website for SWAGAT FITNESS GYM, designed to showcase gym services, attract members, and handle email subscriptions.

Live Preview: https://peppy-truffle-573568.netlify.app/

## Description

This project is a fitness gym website built with HTML, CSS, JavaScript, and PHP. It features a clean, professional design with interactive elements like animations, carousels, and a subscription form. The site includes sections for services, testimonials, pricing, and contact information.

## Features

- **Responsive Design**: Optimized for desktop, tablet, and mobile devices using Bootstrap.
- **Interactive Elements**:
  - Sticky navigation bar that changes on scroll.
  - Smooth scrolling to sections.
  - Animated counters for statistics.
  - Owl Carousel for testimonials and client logos.
  - WOW.js animations on scroll.
- **Subscription Form**: AJAX-powered email subscription with PHP backend validation and email sending.
- **Preloader**: Loading animation on page load.
- **Scroll-to-Top Button**: Appears after scrolling down.

## Technologies Used

- **Frontend**:
  - HTML5
  - CSS3
  - Bootstrap (for responsive grid and components)
  - jQuery (for DOM manipulation and events)
  - JavaScript Plugins:
    - Animsition (page transitions)
    - SmoothScroll (smooth scrolling)
    - WOW.js (scroll animations)
    - Owl Carousel (image/text carousels)
    - Waypoints (scroll-triggered events)
    - CounterUp (animated counters)
- **Backend**:
  - PHP (for email subscription handling)

## Installation and Setup

1. **Clone or Download** the repository to your local machine.
2. **File Structure**:
   - Place all files in a web-accessible directory (e.g., `htdocs` for XAMPP or similar).
   - Ensure the `php/` directory is accessible for the subscription script.
3. **Dependencies**:
   - No additional installations required beyond a web server with PHP support (e.g., Apache with PHP).
   - The site uses CDN-hosted jQuery and Bootstrap in the HTML, but local files are included for offline use.
4. **Run the Website**:
   - Open `index.html` in a web browser for the frontend.
   - For the subscription form to work, serve the site via a local server (e.g., XAMPP, WAMP) to enable PHP processing.

## Usage

- Navigate through the sections using the menu or smooth scrolling.
- Fill out the subscription form to sign up for updates.
- Interact with carousels, animations, and counters as you scroll.

## Project Structure

```
SWAGAT_FITNESS_GYM/
├── index.html          # Main HTML file
├── css/
│   └── style.css       # Custom styles
├── js/
│   ├── custom.js       # Custom jQuery scripts
│   ├── jquery.subscribe.js  # Subscription form handler
│   ├── plugins.js      # Bundled plugins
│   ├── bootstrap.min.js     # Bootstrap JS
│   └── jquery-2.1.1.js      # jQuery library
├── php/
│   └── subscribe.php   # Email subscription backend
├── images/             # Image assets (logos, photos, etc.)
└── README.md           # This file
```

## Contributing

Feel free to fork the repository and submit pull requests for improvements or bug fixes.

## License

This project is open-source. Please check individual plugin licenses for third-party components (e.g., Bootstrap, jQuery plugins).

## Contact

For inquiries, visit the website's contact section or email the configured address.
