# UVU Real Estate Hub

A clean, responsive hub page for the UVU Real Estate Program and Club. Routes visitors to four key destinations: industry professionals, curious students, club members, and the interest list.

## Features

- **Responsive Design**: Works seamlessly on mobile, tablet, and desktop
- **Dark Mode Support**: Automatically adapts to user's system preference
- **Accessible**: WCAG-compliant with proper semantic HTML and keyboard navigation
- **Fast Loading**: No JavaScript dependencies, pure CSS styling
- **Professional Typography**: Uses Google Fonts (Lora + Poppins)

## Project Structure

```
uvu-real-estate-hub/
├── index.html          # Main page (all-in-one file)
├── README.md          # This file
└── .gitignore         # Git ignore rules
```

## Quick Start

1. Clone the repository:
```bash
git clone https://github.com/yourusername/uvu-real-estate-hub.git
cd uvu-real-estate-hub
```

2. Open `index.html` in your browser, or serve it locally:
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (with http-server)
npx http-server
```

3. Visit `http://localhost:8000` in your browser

## Deployment

### GitHub Pages

1. Push to GitHub
2. Go to Settings > Pages
3. Set source to `main` branch
4. Your site will be live at `https://yourusername.github.io/uvu-real-estate-hub`

### Custom Domain

1. Update the `CNAME` file with your domain (optional)
2. Configure DNS records to point to GitHub Pages
3. Enable HTTPS in repository settings

### Other Hosting

This is a static HTML file, so it works on any web server:
- Netlify
- Vercel
- Cloudflare Pages
- Firebase Hosting
- Any traditional web host

## Customization

Edit `index.html` to modify:
- **Colors**: Update CSS variables in `:root` (lines 17-21)
- **Content**: Change heading, description, or card text
- **Links**: Update URLs in the card `href` attributes
- **Fonts**: Swap Google Fonts links at the top

### Color Customization

Light theme colors:
```css
--ground:      #f6f7f4;   /* Background */
--surface:     #ffffff;   /* Card background */
--ink:         #16211a;   /* Text */
--accent:      #275d38;   /* Accent color */
```

Dark theme colors are automatically generated. Customize them in the `@media (prefers-color-scheme: dark)` block.

## Browser Support

- Chrome/Edge 88+
- Firefox 87+
- Safari 14+
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

This project is open source. Feel free to use, modify, and distribute as needed.

## Contact

Questions? Email `realestatecoach@uvu.edu`
