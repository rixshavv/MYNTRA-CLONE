MYNTRA-CLONE
A visually accurate and functionally robust front-end clone of the popular e-commerce platform, Myntra. This project was built to practice modern HTML structure, advanced CSS styling, and dynamic data handling with vanilla JavaScript.

🚀 Live Demo
Experience the clone live: LIVE DEMO LINK
(Replace with your actual deployed link, e.g., GitHub Pages URL.)

✨ Features
This clone focuses on replicating the core user experience and visual design of the original Myntra website.

Pages Cloned
Homepage: Replicates the main layout, header, footer, and promotional banners.
Product Listing Page (PLP): Displays product cards fetched from mock data.
Bag/Cart Page: Allows users to view, manage, and calculate their final order.
Functionality
Dynamic Product Rendering: Products are loaded dynamically from a JavaScript object/mock JSON data.
Filter & Sorting: Functional sidebar filters (e.g., by category, color, brand) and sorting options (e.g., Price: High to Low) to refine the product list.
Shopping Cart Logic:
Add to Bag / Remove from Bag functionality.
Quantity management on the Cart page.
Automatic calculation of Total Price, Discount, and Final Payable Amount.
Persistence: All Cart data is saved locally using localStorage, so it persists across page refreshes and sessions.
Responsive Design: Implemented with CSS Media Queries to ensure a smooth viewing experience on various screen sizes (Mobile, Tablet, Desktop).
🛠️ Tech Stack
This project is a purely front-end build and uses the following core technologies:

Technology

Role

HTML5

Project structure and semantic markup.

CSS3

Pixel-perfect styling, Flexbox, CSS Grid, and responsive design.

JavaScript (ES6+)

Dynamic content rendering, logic for cart, filters, and local storage management.

Local Storage

Data persistence for the Shopping Bag.

Font Awesome

Used for icons (e.g., Wishlist, Profile, Bag).

📁 Project Structure
The codebase is organized logically to separate structure, style, and script files.


Run
Copy code
MYNTRA-CLONE/
├── index.html              # Homepage
├── products.html           # Product Listing Page
├── bag.html                # Shopping Cart Page
├── css/
│   ├── style.css           # Global and general styles
│   └── responsive.css      # Media queries and responsive adjustments
├── js/
│   ├── index.js            # Homepage scripts (banners, sliders)
│   ├── products.js         # Product rendering, filtering, and sorting logic
│   └── bag.js              # Cart management and calculation logic
├── data/
│   └── products.js         # Mock product data (Array of Objects)
├── images/                 # All logos, banners, and product images
├── README.md
└── LICENSE
⚙️ Installation and Setup
To run this project locally on your machine, follow these simple steps:

Clone the repository:


Run
Copy code
git clone https://github.com/rixshavv/MYNTRA-CLONE.git
Navigate to the project directory:


Run
Copy code
cd MYNTRA-CLONE
Open in your browser:

Simply double-click the index.html file.
Or, if you're using a code editor like VS Code, right-click index.html and select "Open with Live Server".
🧑‍💻 Author
This project was developed by:

GitHub: rishavv
Developed By: [Rishav]
📝 License
This project is licensed under the MIT License - see the LICENSE file for details.

