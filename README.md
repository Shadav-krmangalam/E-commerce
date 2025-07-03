# E-commerce

Fashion E-Commerce Landing Page 

1. Page Setup
<!DOCTYPE html>: Declares HTML5 document type.


<html lang="en">: Specifies document language for accessibility and SEO.


<head> Section:


Meta tags: Set character encoding and responsive viewport.


Google Fonts: Imports the "Montserrat" font for modern typography.


<style> tag: All CSS is embedded directly within the document.



2. Sticky Navigation Bar
Purpose:
A fixed top bar to access search, icons (cart/login), and login button.
HTML Elements Used:
<nav class="navbar"> – Main nav wrapper.


Logo – Plain text styled with font-weight.


Search Bar – Input field styled with padding and custom icon using ::after.


Icon links – Emoji icons (🛒, 👤) with hover background.


Login Button – Styled with border-radius and hover transitions.


CSS Concepts:
position: sticky, z-index, box-shadow for fixed look.


Flexbox layout with justify-content: space-between and gap.



3. Hero Section
Purpose:
To grab attention with a banner image and call-to-action (CTA).
HTML Elements:
<section class="hero"> – Background image with overlay.


.hero-content – Text block with title, description, and CTA button.


CSS Concepts:
background: url(...) center/cover for full-size image.


.hero-overlay: semi-transparent layer using rgba().


Typography scaling with font-size, CTA hover effects.



 4. Flash Sale Strip
Purpose:
A promotional red bar with countdown-like appearance.
Features:
Text + Countdown: Uses spans styled with monospace and background.


Visual emphasis: Red background (#ff4d4f), large font.



5. Main Content Layout
Uses a Flexbox layout to organize:
Sidebar filters


Main product area



 6. Sidebar Filters
Purpose:
Allow users to filter products.
Structure:
Wrapped in <aside class="sidebar">


Uses headings and <label><input type="checkbox"> groups.


Sections: Category, Price, Color.


CSS Concepts:
box-shadow, border-radius, and spacing.


flex: 0 0 220px to fix width.



 7. Product Area
Sections:
Featured Categories:


Grid layout using grid-template-columns: repeat(auto-fit, minmax(...))


Cards with round category images.


Product Grid:


Multiple product cards each containing:


Image


Title


Price


"Add to Cart" button


Best Seller Section:


Same structure reused with separate heading.


Visual Elements:
hover effects for scaling cards and buttons.


Border-radius and shadows for smooth card styling.



 8. Testimonials
Purpose:
Adds social proof and user trust.
Structure:
Each testimonial includes:


Avatar image


Name


Feedback text


CSS:
Uses Flexbox to wrap cards


Soft background for cards


Border-radius and avatar styling



 9. Newsletter Signup
Purpose:
Collect emails for updates.
Elements:
Title + description


Email input and submit button


CSS:
Dark background with contrast buttons


Flex-wrap for responsiveness



 10. Footer
Structure:
Grid layout of 4 columns:


Account


Help


Policies


Social media links


Uses <ul> + <li> for links


Icons (emoji) for social media


Bottom copyright


CSS:
background: #181818, color contrasts, grid-template-columns for layout



 11. Responsive Design
Techniques:
Media Queries:


@media (max-width: 1100px), 800px, 600px


Adjusts:


Flex direction


Grid gaps


Font sizes


Padding/margins



