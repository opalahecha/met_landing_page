# MET Landing Page

A responsive landing page for The Metropolitan Museum of Art. The page helps visitors plan a museum visit, browse current exhibitions, explore online resources, and find contact information for The Met Fifth Avenue and The Met Cloisters.

[Visit the Website](https://opalahecha.github.io/met_landing_page/) | [View Figma Design](https://www.figma.com/design/lSR1m42L9YwzQwzzxKwHpw/THE-MET?node-id=8590-29&p=f&t=0QxmL6vx6h1WX5ig-0)

## Project Description

This is a single-page responsive layout based on the provided Figma design. It includes a full-screen hero section, mobile menu, museum hours, exhibition cards, online exploration cards, contact details, and a contact form.

The project focuses on semantic HTML, BEM class naming, responsive CSS Grid/Flexbox layouts, optimized WebP images, and smooth hover/tap interactions across mobile, tablet, and desktop screens.

## Features

- Responsive layout for mobile, tablet, and desktop screens.
- Full-screen hero section with museum branding.
- Mobile menu opened through an anchor target.
- Phone contact tooltip available on hover and mobile tap/focus.
- Museum hours for The Met Fifth Avenue and The Met Cloisters.
- Now On View gallery with image hover zoom inside fixed image bounds.
- More to explore online section with responsive cards.
- Contact section with phone numbers, map links, and a simple form.
- Optimized WebP images for the main visual content.
- Smooth scrolling and BEM-based SCSS structure.

## Technologies Used

- HTML5
- Sass / SCSS
- BEM methodology
- CSS Grid
- Flexbox
- Parcel
- Node.js and NPM

## Requirements

- Node.js `22.18.0` or newer
- NPM `11.13.0` or newer
- Git

## Installation and Setup

1. Clone the repository:

```bash
git clone https://github.com/opalahecha/met_landing_page.git
```

2. Navigate to the project directory:

```bash
cd met_landing_page
```

3. Install dependencies:

```bash
npm install
```

4. Start the local development server:

```bash
npm start
```

5. For a production build:

```bash
npm run build
```

The local URL is usually shown in the terminal. By default, this project uses `http://localhost:8080`.

## Project Structure

```text
src/
  images/
  styles/
    blocks/
    utils/
  index.html
```

## License

This project is licensed under the GPL-3.0 License. See the [LICENSE](./LICENSE) file for details.
