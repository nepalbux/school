# Reliance Public School Website

A modern, attractive, and fully functional website for Reliance Public School with full-page video, multiple sections, social media integration, and responsive design.

## Features

- Full-page video background on the homepage
- Modern and futuristic design with smooth animations
- Responsive layout for all screen sizes (mobile, tablet, desktop)
- Interactive navigation with smooth scrolling
- Sections for About Us, Activities, Gallery, Contact, and Enrollment
- Contact form with validation
- Google Maps integration
- Social media links
- Developer credit

## File Structure

- `index.html` - Main HTML file with the website structure
- `styles.css` - CSS file with all styling and responsive design
- `script.js` - JavaScript file with interactive functionality
- `README.md` - Documentation file

## Technologies Used

- HTML5
- CSS3 (with Flexbox and Grid)
- JavaScript (Vanilla JS)
- Font Awesome for icons
- Google Fonts (Poppins)
- YouTube embedded video

## Setup Instructions

1. Download all files to your local machine or server
2. No build process required - this is a static website
3. Open `index.html` in a web browser to view the website
4. To deploy, upload all files to your web hosting service

## Customization Guide

### Changing the Video

The current website uses a YouTube video as the background. To change it:

1. Open `index.html`
2. Find the `<iframe>` tag in the hero section (around line 60)
3. Replace the `src` attribute with your YouTube video URL
4. Make sure to keep the parameters for autoplay, mute, loop, etc.

### Updating Content

1. Text content can be modified directly in the `index.html` file
2. Images can be replaced by changing the `src` attributes in the image tags
3. Contact information can be updated in both the Contact section and Footer

### Styling Changes

1. Colors: The main color scheme uses gradients with `#4A90E2` and `#7B68EE`. You can modify these in the `styles.css` file
2. Fonts: The website uses 'Poppins' from Google Fonts. You can change this by updating the font import in the `<head>` section of `index.html` and the font-family in `styles.css`

### Adding New Sections

1. Follow the HTML structure pattern of existing sections
2. Add corresponding CSS styles in `styles.css`
3. Update the navigation menu in the `<nav>` section

## Browser Compatibility

The website is compatible with:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Android Chrome)

## Performance Optimization

- Images should be optimized for web (compressed)
- The JavaScript uses debouncing for scroll events to improve performance
- CSS animations are hardware-accelerated where possible

## Credits

- Developed by: [Ram Raja Bastakoti](https://ramrajabastakoti.com.np)
- Icons: [Font Awesome](https://fontawesome.com)
- Fonts: [Google Fonts](https://fonts.google.com)

## License

This website is created for Reliance Public School. All rights reserved.

---

For any questions or support, please contact the developer at the provided link.

