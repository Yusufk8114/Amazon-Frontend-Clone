# Amazon-Frontend-Clone (HTML & CSS)

A static front end page which mirrors that of the Amazon homepage and was made as my first HTML and CSS assignment. The components replicated include the navigation menu, categories box, hero image box, product category boxes, and footer.

> **Note:** This project is for learning purposes only. It is not affiliated with or endorsed by Amazon. All trademarks and logos belong to their respective owners.

## Features

- **Navigation bar** that contains logo, delivery location, search bar (category drop down menu, search box, search button), language selector (Indian flag), account and lists, return and orders, and cart - **Hover effect** on items in navigation bar (white border) and search bar (orange border) - **Secondary panel** that has "All" menu button, category links and deals highlight - **Hero section** that contains banner image and a message to change to amazon.in - **Shop section** that has 8 category cards (Clothes, Health & Personal Care, Furniture, Electronics, Beauty Picks, Pet Care, Toys, Fashion Trends) organized using Flexbox - **Footer** that has "Back to Top" bar, 4 columns of links, language and country button, legal links and copyright information

## Built With

- **HTML5**: semantic markup - **CSS3**: Flexbox, :hover pseudo-class, :before pseudo-element, background images - **[Font Awesome 7](https://fontawesome.com/)**: icons (location icon, search icon, cart icon, menu icon), using CDN

## Project Structure

```
amazon-clone/
├── index.html            # Page structure and content
├── style.css             # All styling
├── amazon_logo.png       # Logo used in header and footer
├── india-flag-icon.svg   # Flag icon in navbar and footer
├── hero_image.jpg        # Hero banner background
├── box1_image.jpg        # Category card images (box1 to box8)
├── ...
└── box8_image.jpg
```

## Getting Started

There are no need for any build tools.

1. 1. **Clone the repository** ```https://github.com/Yusufk8114/Amazon-Frontend-Clone ``` 2. **Navigate to your project directory** ```bash cd <Amazon-Frontend-Clone> ``` 3. **Load `index.html`** into your browser (open the file double-clicking on it, or use the Live Server extension on VS Code).

A connection to the internet is necessary for loading the Font Awesome icons.

## What I Learned

- Creating a web page using semantic HTML - Creating page layout using Flexbox (justify-content, align-items, flex-wrap) - Stylings using classes, hover effects, and background images - Structuring CSS into different segments like navigation bar, panel, hero, shop section, and footer - Including an icon library via a CDN

## Future Improvements

- Make the design responsive to tablets and mobiles (media queries) - Create an active search bar and drop-down for categories with JavaScript - Make a sign-in page and cart feature - Create a product listing page with product cards - Create a drop-down for the 'All' tab

## Author

**Your Name**
- GitHub: https://github.com/Yusufk8114

## License

The software is open-source and may be used for educational purposes.
