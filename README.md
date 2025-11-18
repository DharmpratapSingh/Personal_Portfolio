# Personal Portfolio

 

A modern, responsive portfolio website inspired by [The Vault](https://www.osmo.supply/product/vault) design aesthetic.

 

## Features

 

- **Dark/Light Mode**: Toggle between themes with smooth transitions

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile

- **Smooth Animations**: Subtle scroll animations and hover effects

- **Modular Sections**: Hero, Projects, Skills, About, and Contact

- **Card-based Layout**: Clean, modern project showcases

- **Accessibility**: Semantic HTML and keyboard navigation support

 

## Design Inspiration

 

This portfolio is inspired by The Vault's clean, dashboard-like aesthetic:

- Generous whitespace and modern typography

- Card-based grid layouts

- Smooth transitions and interactions

- Professional color palette with dark mode support

- Geometric background elements

 

## Tech Stack

 

- **HTML5**: Semantic markup

- **CSS3**: Custom properties, Grid, Flexbox

- **Vanilla JavaScript**: No frameworks, pure performance

- **Design**: Mobile-first, responsive approach

 

## Getting Started

 

1. Clone the repository:

   ```bash

   git clone https://github.com/DharmpratapSingh/Personal_Portfolio.git

   ```

 

2. Open `index.html` in your browser or use a local server:

   ```bash

   # Using Python

   python -m http.server 8000

 

   # Using Node.js

   npx http-server

   ```

 

3. Customize:

   - Update personal information in `index.html`

   - Replace project cards with your own work

   - Modify colors in `css/style.css` (CSS custom properties at the top)

   - Add your resume to `assets/` folder

 

## Customization

 

### Colors

All colors are defined as CSS custom properties in `:root`:

```css

:root {

    --accent: #3b82f6;  /* Primary accent color */

    --bg-primary: #fafafa;  /* Main background */

    /* ... more variables */

}

```

 

### Projects

Edit the project cards in `index.html`:

```html

<div class="project-card">

    <!-- Update image, title, description, tags, and links -->

</div>

```

 

### Dark Mode

Theme preference is saved to `localStorage`. Users can toggle with:

- Click the moon/sun icon in the navigation

- Press `T` key on keyboard

 

## Performance

 

- No external dependencies

- Lazy loading for images

- Intersection Observer for scroll animations

- Optimized CSS with minimal reflows

 

## Browser Support

 

- Chrome (latest)

- Firefox (latest)

- Safari (latest)

- Edge (latest)

 

## License

 

MIT License - feel free to use this template for your own portfolio!

 

## Contact

 

Dharmpratap Singh Vaghela

- Email: your.email@example.com

- GitHub: [@DharmpratapSingh](https://github.com/DharmpratapSingh)

- LinkedIn: [Your LinkedIn]

 

---

 
