# Good Times Barbershop Website

A professional, responsive website for Good Times Barbershop with two locations in Victorville.

## Features

✨ **Responsive Design** - Works perfectly on desktop, tablet, and mobile devices

🎯 **Multiple Sections**
- Hero Section with location booking buttons
- Services Showcase
- Location Information with hours and contact details
- Contact Form
- Navigation Menu with smooth scrolling

🎨 **Modern Styling**
- Gold and dark color scheme
- Smooth transitions and hover effects
- Mobile-friendly hamburger menu
- Professional typography

📱 **Interactive Elements**
- Smooth navigation scrolling
- Mobile menu toggle
- Contact form with validation
- Booking buttons for each location

## File Structure

```
Good-times-Barber/
├── index.html      # Main HTML file
├── styles.css      # Styling
├── script.js       # JavaScript functionality
└── README.md       # This file
```

## Getting Started

1. Clone or download the repository
2. Open `index.html` in your web browser
3. No additional dependencies required - it's pure HTML, CSS, and JavaScript

## Customization

### Update Location Details
Edit the location cards in `index.html` to add:
- Actual addresses
- Real phone numbers
- Actual business hours

### Change Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #1a1a1a;      /* Dark color */
    --secondary-color: #d4af37;    /* Gold color */
    --accent-color: #ff6b35;       /* Orange accent */
}
```

### Add Booking System
Replace the `bookAppointment()` function in `script.js` with your actual booking system integration.

### Add Contact Form Backend
Update the form submission in `script.js` to send data to your backend server:
```javascript
fetch('/api/contact', {
    method: 'POST',
    headers: {
        'Content-Type': 'application/json',
    },
    body: JSON.stringify({ name, email, message })
});
```

## Responsive Breakpoints

- **Mobile**: 480px and below
- **Tablet**: 768px and below
- **Desktop**: 769px and above

## Browser Support

Works on all modern browsers:
- Chrome/Edge
- Firefox
- Safari
- Mobile browsers

## Future Enhancements

- [ ] Integration with booking system (e.g., Calendly, Acuity Scheduling)
- [ ] Photo gallery of haircuts
- [ ] Barber profiles and availability
- [ ] Online payments
- [ ] Customer testimonials/reviews section
- [ ] Social media integration
- [ ] Blog for hair tips

## License

Created for Good Times Barbershop © 2024

## Contact

For website questions or updates, contact the development team.
