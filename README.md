# Dream Esports Website

A modern, responsive esports organization website featuring rosters for Rainbow Six Siege, Rocket League, and Call of Duty teams.

## Features

- **Modern Design**: Built with Tailwind CSS for a sleek, professional appearance
- **Responsive Layout**: Fully responsive design that works on all devices
- **Multiple Pages**: Complete website with all essential pages
- **Interactive Elements**: Hover effects, animations, and smooth transitions
- **Team Rosters**: Detailed player profiles for all three games
- **Staff Directory**: Comprehensive staff and management team information
- **Contact Forms**: Functional contact form with validation
- **FAQ Section**: Expandable FAQ for common questions

## Pages

1. **Home** (`index.html`) - Landing page with hero section and game overview
2. **Rosters** (`rosters.html`) - Team rosters for all three competitive games
3. **About** (`about.html`) - Organization mission, values, and timeline
4. **Contact** (`contact.html`) - Contact form, social links, and FAQ
5. **Staff** (`staff.html`) - Management and staff team directory

## Game Rosters

### Rainbow Six Siege
- 5 Players + Coach
- Roles: IGL, Entry, Support, Flex, Lurker, Breacher

### Rocket League  
- 3 Players + Substitute
- Roles: Main Striker, Playmaker, Defense

### Call of Duty
- 5 Players + Coach  
- Roles: AR, Sniper, SMG, Flex, Objective

## Technologies Used

- **HTML5** - Semantic markup
- **Tailwind CSS** - Utility-first CSS framework
- **Font Awesome** - Icon library
- **Google Fonts** - Orbitron & Inter fonts
- **Vanilla JavaScript** - Interactive features

## Getting Started

1. Clone or download the project files
2. Add your logos to the appropriate directories (see Logo Setup below)
3. Open `index.html` in your web browser
4. Navigate through the site using the navigation menu

## Logo Setup

### Organization Logo
- Place your main organization logo at `assets/logo/logo.png`
- Recommended size: 200x200px or larger
- Use PNG format with transparent background for best results
- The logo will appear in navigation and footer areas

### Game Logos
Place game logos in their individual folders:
- `assets/games/rainbow-six-siege/logo.png` - Rainbow Six Siege logo
- `assets/games/rocket-league/logo.png` - Rocket League logo  
- `assets/games/call-of-duty/logo.png` - Call of Duty logo

Game logos should be:
- Size: 200x200px or larger
- PNG format with transparent background
- Official game logos or custom branded versions

### Logo Specifications
- **Format**: PNG with transparent background
- **Size**: Minimum 200x200px (larger is better)
- **Style**: Clean, modern design that works well with dark backgrounds
- **Colors**: Compatible with #2596be blue theme
- **Aspect Ratio**: Square (1:1) works best

### Folder Structure
```
assets/
├── logo/
│   └── logo.png
└── games/
    ├── rainbow-six-siege/
    │   └── logo.png
    ├── rocket-league/
    │   └── logo.png
    └── call-of-duty/
        └── logo.png
```

## Customization

### Colors
The site uses a blue color scheme (#2596be). You can customize colors by modifying the CSS variables in each HTML file:

```css
.hero-gradient {
    background: linear-gradient(135deg, #2596be 0%, #1a7ca8 100%);
}
```

### Team Information
Update player names, roles, and social media links in the `rosters.html` file:

```html
<h3 class="orbitron text-xl font-bold mb-1">PlayerName</h3>
<p class="text-orange-400 font-semibold mb-2">Role</p>
```

### Contact Information
Update contact details in `contact.html`:

```html
<a href="mailto:contact@dreamesports.com">contact@dreamesports.com</a>
<a href="https://discord.gg/dreamesports">Discord Server</a>
```

## Features Breakdown

### Navigation
- Fixed header with blur backdrop
- Mobile-responsive hamburger menu
- Active page highlighting

### Hero Section
- Gradient background with animated elements
- Call-to-action buttons
- Responsive typography

### Player Cards
- Hover animations and effects
- Social media links
- Role-based color coding

### Contact Form
- Form validation
- Success message feedback
- Multiple inquiry types

### FAQ Section
- Expandable/collapsible items
- Smooth animations
- Icon indicators

## Browser Support

- Chrome/Chromium 60+
- Firefox 60+
- Safari 12+
- Edge 79+

## License

This project is open source and available under the [MIT License](LICENSE).

## Contact

For questions or support regarding this website template, please contact us at:
- Email: contact@dreamesports.com
- Discord: https://discord.gg/dreamesports
- Twitter: https://twitter.com/dreamesports

---

**Dream Esports** - Competing at the Highest Level
