# Amazon Clone

A beginner-friendly front-end project that recreates the look and feel of the Amazon homepage using only HTML and CSS.

This project was built as a learning exercise to practice:
- HTML page structure
- CSS layout and styling
- Flexbox
- responsive design basics
- image cards and hover effects
- building a real-world UI clone

The website is not functional as an ecommerce app. It is a static UI clone created for practice and educational purposes.

## Preview

This project includes:
- a top navigation bar similar to Amazon
- a secondary panel menu
- a hero banner section
- a product/category grid with 8 content boxes

## Tech Used

- `HTML5`
- `CSS3`
- `Font Awesome` for icons

## Project Structure

```text
amazon-clone/
├── index.html
├── style.css
├── amazon_logo.png
├── box1.jpg
├── box2.jpg
├── box3.jpg
├── box4.jpg
├── box5.jpg
├── box6.jpg
├── box7.jpg
├── box8.jpg
└── README.md
```

## What This Project Contains

### 1. Navbar

The top navbar is built to resemble the Amazon header and includes:
- Amazon logo
- delivery location section
- search bar with category dropdown
- sign in section
- returns and orders section
- cart icon

This part helped practice:
- horizontal layout using `flex`
- alignment and spacing
- icon integration
- hover borders

### 2. Panel Section

Below the navbar, there is a second horizontal panel containing:
- menu icon with `All`
- quick navigation links
- highlighted deals text

This section was useful for understanding:
- multi-row header structure
- secondary navigation styling
- spacing between grouped elements

### 3. Hero Section

The hero section uses a background image to create the large banner area at the top of the page.

It also includes a message box with a short project disclaimer and a link to the real Amazon website.

This section demonstrates:
- background images in CSS
- content positioning with flexbox
- overlay-style messaging

### 4. Shop Section

The shop section contains 8 category cards arranged in a grid-style layout.

Each box includes:
- a heading
- an image area
- a small call-to-action text like `see more`

This part helped practice:
- reusable card design
- consistent spacing and padding
- card hover effects
- using multiple local image assets
- wrapping boxes into multiple rows

## Styling Approach

The styling is written in a single `style.css` file.

Some of the main CSS concepts used in this project are:
- `box-sizing: border-box`
- `display: flex`
- `justify-content`
- `align-items`
- `background-image`
- `background-size: cover`
- `border-radius`
- `box-shadow`
- `hover effects`
- `media queries`

## Responsive Design

Basic responsiveness has been added so the layout behaves better on smaller screens.

Examples:
- navbar items can wrap when screen width becomes smaller
- panel content can break into multiple lines
- product boxes are designed to flow into additional rows

This project is responsive at a basic level, though it can still be improved further for mobile-first polish.

## Learning Goals Behind This Project

This project was mainly created to improve understanding of:
- how real websites are structured
- how layout problems happen and how to fix them
- how to use flexbox for row alignment
- how to organize repeated UI components
- how to make a page look more polished with spacing, colors, and images

## Key Improvements Made During Development

Some important improvements made while building this project:
- fixed incorrect CSS like `border: border-box` by replacing it with `box-sizing: border-box`
- corrected navbar structure so items stay in one row
- improved icon usage with proper Font Awesome classes
- added styling for the panel section
- improved the product card image area with better spacing and presentation
- expanded the product section from 4 cards to 8 cards
- added basic responsive behavior

## How to Run This Project

Since this is a static website, no installation is required.

1. Download or clone the repository.
2. Open the project folder.
3. Open `index.html` in your browser.

You can also use a live server extension in VS Code for a better development experience.

## Future Improvements

Some ideas to improve this project further:
- make the design even closer to the real Amazon homepage
- improve mobile responsiveness
- add footer sections
- add more product cards and sections
- use JavaScript for interactivity
- create separate pages
- add search functionality

## Disclaimer

This project is a personal educational clone inspired by Amazon's homepage design.
It is not affiliated with, endorsed by, or connected to Amazon.

## Author

Made as a web development practice project by Abhinav.
