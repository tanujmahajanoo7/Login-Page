# Login & Signup Page

A modern, responsive login and registration page with a beautiful glass-morphism design and smooth animations.

## Features

- 🎨 **Modern UI Design**: Glass-morphism effect with backdrop blur
- 📱 **Responsive Layout**: Works on all screen sizes
- ✨ **Smooth Animations**: Elegant transitions between login and registration forms
- 🔒 **Form Validation**: Built-in HTML5 form validation
- 🎯 **User-Friendly**: Intuitive interface with clear navigation
- 🖼️ **Background Image**: Customizable background image support

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with glass-morphism effects
- **JavaScript**: Form switching and popup functionality
- **Ionicons**: Icon library for visual elements
- **Google Fonts**: Poppins font family

## Project Structure

```
Login-Page/
├── index.html          # Main HTML file
├── style.css          # Stylesheet with all CSS
├── script.js          # JavaScript for interactions
└── two.jpg           # Background image
```

## Getting Started

### Prerequisites

No special prerequisites needed! Just a modern web browser.

### Installation

1. Clone or download this repository
2. Navigate to the `Login-Page` folder
3. Open `index.html` in your web browser

That's it! The page should load with all features working.

## Usage

### Opening the Login/Registration Form

1. Click the **"Login"** button in the navigation bar
2. The form popup will appear with a smooth animation

### Switching Between Forms

- Click **"Register"** link in the login form to switch to registration
- Click **"Login"** link in the registration form to switch back to login
- Forms slide smoothly between each other

### Closing the Form

Click the **X icon** in the top-right corner of the form to close it.

## Customization

### Changing the Background Image

1. Replace `two.jpg` with your desired image
2. Ensure the image filename matches in `style.css` line 16:
   ```css
   background: url('two.jpg') no-repeat;
   ```

### Modifying Colors

The main color scheme uses `#162938` (dark blue). To change colors, search and replace in `style.css`:
- Primary color: `#162938`
- Text color: `#fff` (white)
- Accent colors can be adjusted throughout the file

### Adjusting Form Size

Modify the wrapper dimensions in `style.css`:
```css
.wrapper {
    width: 400px;
    height: 440px;
}
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Future Enhancements

Potential improvements you might want to add:
- Backend integration for actual authentication
- Password strength indicator
- Email validation with regex
- Remember me functionality (requires backend)
- Social media login options
- Forgot password functionality

## License

This project is open source and available for personal and commercial use.

## Author

Created with 💜 for modern web experiences.

---

**Note**: This is a frontend-only implementation. For a complete authentication system, you'll need to integrate with a backend service to handle user registration, login verification, and session management.

