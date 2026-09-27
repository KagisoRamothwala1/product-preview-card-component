Overview
The Challenge

Users should be able to:

View the optimal layout for the component depending on their device's screen size
See hover and focus states for interactive elements

This project is a solution to the Product Preview Card Component challenge on Frontend Mentor. It displays a perfume product card featuring a product image, name, description, and pricing, along with an "Add to Cart" button.


Links
Solution URL: Add solution URL here
Live Site URL: Add live site URL here
My Process
Built With
Semantic HTML5 markup
CSS custom properties
Flexbox / CSS Grid
Mobile-first workflow
Google Fonts (Montserrat, Fraunces)
What I Learned

This challenge was a good exercise in structuring a small, self-contained component with clear content sections (image, header, description, pricing, and call-to-action). Example of the markup structure used for the pricing section:

html
<div class="pricingctn">
  <div class="price1">$149.99</div>
  <div class="price2">$169.99</div>
</div>
Continued Development

A few areas worth revisiting to strengthen this solution:

Add a responsive image (<picture> element) so a dedicated mobile image is served on smaller screens instead of the desktop image.
Add :hover and :focus states to the "Add to Cart" button for better accessibility, as required by the challenge.
Review heading semantics — consider using proper <h1>/<p> tags instead of generic <div> containers for the product name and description, to improve accessibility and SEO.
Add alt text that's more descriptive than the filename for the product image.
Author
GitHub - Kagiso Ramothwala
Frontend Mentor - Add your Frontend Mentor profile link here