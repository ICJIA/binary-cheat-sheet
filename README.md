[![Netlify Status](https://api.netlify.com/api/v1/badges/08ec7661-79e2-4603-a5e6-411d1fa8e857/deploy-status)](https://app.netlify.com/sites/marvelous-centaur-46864c/deploys)

# Binary Cheat Sheet

A comprehensive, interactive guide to understanding binary numbers and their applications in computing. Built with modern web technologies and designed for both beginners and experienced developers.

## Demo

https://binary-cheat.netlify.app/

## Overview

This project provides a detailed exploration of binary numbers, from basic concepts to advanced applications. It includes:

- Interactive code examples in JavaScript and Python
- Visual explanations of binary operations
- Historical context and real-world applications
- Responsive design with dark/light mode support
- Accessible content structure

## Technical Details

### Built With

- HTML5
- Tailwind CSS (via CDN)
- PrismJS for code highlighting
- JavaScript (ES6+)

## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/yourusername/binary-cheat-sheet.git
```

2. Open `index.html` in your browser or serve it using a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve
```

3. Visit `http://localhost:8000` in your browser

## Project Structure

```
binary-cheat-sheet/
├── index.html          # Main HTML file
├── public/            # Static assets
│   └── altair8800.jpg # Historical image
└── README.md          # Project documentation
```

## Future Improvements

### Performance

- [ ] Implement Tailwind CSS purging to reduce bundle size
- [ ] Add lazy loading for images and code examples
- [ ] Implement service worker for offline support
- [ ] Add resource hints for CDN resources

### Accessibility

- [ ] Enhance keyboard navigation
- [ ] Add skip links for screen readers
- [ ] Improve color contrast ratios
- [ ] Add more ARIA roles and labels

### Features

- [ ] Add interactive binary calculators
- [ ] Implement binary visualization tools
- [ ] Add practice exercises
- [ ] Include more historical examples

### Technical

- [ ] Add error boundaries for JavaScript
- [ ] Implement proper image fallbacks
- [ ] Add meta tags for SEO
- [ ] Implement progressive enhancement
- [ ] Add unit tests for JavaScript functions

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
