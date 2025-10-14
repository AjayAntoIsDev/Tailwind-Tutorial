# Tailwind Tutorial

A minimal project demonstrating how to use Tailwind CSS in a simple static site.

This repository includes a basic HTML file and supporting CSS/JS used for examples and code highlighting.

## Project structure

- `index.html` - Example HTML page using Tailwind classes.
- `css/` - Stylesheets used by the project (e.g. `prism.css` for code highlighting).
- `js/` - JavaScript files used by the project (e.g. `prism.js` for syntax highlighting).

## Getting started

1. Open `index.html` in your browser to view the demo. For local development, you can serve the folder with a simple static server:

	 - Using Python 3:

		 python3 -m http.server 8000

	 - Using Node (http-server):

		 npx http-server -p 8000

2. Visit http://localhost:8000 in your browser.

## Notes

- This project is intentionally minimal and does not include a Tailwind build pipeline. If you want to use Tailwind's CLI or PostCSS to generate utility classes, add a `package.json` and Tailwind config, then install the Tailwind packages.

## License

This project is provided as-is for learning and demo purposes.