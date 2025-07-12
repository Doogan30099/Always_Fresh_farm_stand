# Always Fresh Farm Stand Website

## Overview

Always Fresh Farm Stand is a rustic, community-focused website designed to showcase a local farm's offerings and encourage customers to shop online. The site includes rich storytelling about the farm's beginnings and values, a dynamic shopping experience, contact and checkout capabilities, and a consistent aesthetic that reflects its organic and welcoming nature.

## Features

* **Homepage**: A welcoming landing page with navigation links to the rest of the site.
* **Order Page**: Interactive shop interface with categorized items, quantity selection, real-time total calculation, and checkout button.
* **Checkout Page**: Displays order summary, including selected items and quantities. Contains form fields for customer information.
* **About Us Page**: Tells the story of the farm, its practices, values, and community involvement. Includes visual imagery of farm life.
* **Contact Page**: Customer support form with fields for name, email, phone number, and a comment section.

## Technologies Used

* **HTML5** and **Semantic Markup** for accessible structure
* **CSS3** for rustic and natural styling (including custom stylesheets)
* **Bootstrap 5** for responsive layout and UI components
* **JavaScript** for dynamic content rendering, interactivity, and data persistence via `localStorage`

## File Structure

```
Always_Fresh_Farm_Stand/
│
├── Always_Fresh_Farm_Stand_home.html # Homepage
├── Always_Fresh_Farm_Stand_Shop.html # Order page
├── Always_Fresh_Farm_Stand_Checkout.html # Checkout page
├── Always_Fresh_Farm_Stand_About_us.html # About Us page
├── Always_Fresh_Farm_Stand_Contact.html  # Contact Us page
│
├── Always_Fresh_Farm_Stand_shop_Styles.css   # Styling for order/checkout
├── Always_Fresh_Farm_Stand_about_Styles.css  # Styling for About Us
├── Always_Fresh_Farm_Stand_contact_Styles.css # Styling for Contact page
│
└── assets/
    └── images/ https://images.unsplash.com/photo-1621460249485-4e4f92c9de5d?w=600&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8M3x8ZmFybWluZ3xlbnwwfHwwfHx8MA%3D%3D      
               https://plus.unsplash.com/premium_photo-1687168616202-401d8ce57070?w=600&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8OXx8bG9jYWwlMjBmb29kfGVufDB8fDB8fHww
               https://images.unsplash.com/photo-1512621776951-a57141f2eefd?w=600&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MTB8fGZvb2R8ZW58MHx8MHx8fDA%3D
               https://images.unsplash.com/photo-1550989460-0adf9ea622e2?w=600&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8NHx8bG9jYWwlMjBmb29kfGVufDB8fDB8fHww
               https://images.unsplash.com/photo-1605000797499-95a51c5269ae?w=1000&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Mnx8ZmFybWluZ3xlbnwwfHwwfHx8MA%3D%3D
               https://images.unsplash.com/photo-1630802976932-f035b8742da6?w=1000&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8M3x8a2lkcyUyMG9uJTIwYSUyMGZhcm18ZW58MHx8MHx8fDA%3D
                # Images used throughout the site
```

## Data Persistence

* The order page uses JavaScript to store the selected items and total price in the browser's `localStorage`.
* The checkout page reads this data to generate an order summary.

## Setup Instructions

1. Clone the repository or copy the project files to your local machine.
2. Ensure all HTML and CSS files are in the correct structure as shown above.
3. Open `Always_Fresh_Farm_Stand_Shop.html` in a browser to start shopping.
4. The checkout page will reflect your order once you proceed via the Checkout button.

## Notes

* All pages include a consistent navigation bar for easy browsing.
* The aesthetic uses a muted, rustic palette with serif fonts to reflect organic farming values.
* You may replace placeholder image URLs with your own in the stylesheets or HTML.

## Future Enhancements

* Backend integration to process actual orders
* Email notifications upon order submission
* Inventory management and product filtering

---

This website provides a friendly, immersive experience that invites customers to learn, connect, and shop locally from Always Fresh Farm Stand.
