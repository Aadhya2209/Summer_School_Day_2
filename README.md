# Summer_School_Day_2

🎨 CSS Styling Summary – Personal Profile Card Project

This project demonstrates my understanding of HTML and the three types of CSS (inline, internal, and external), along with a variety of CSS selectors. Below is a breakdown of how and where each was applied in building my unique profile card.

────────────────────────────────────────
🔧 CSS Types Implemented:
────────────────────────────────────────

1️⃣ Inline CSS:
Used directly within the HTML element to instantly apply styling.  
→ Example: Added a soft background color to the <section> tag using the style attribute for quick customization.

2️⃣ Internal CSS:
Defined within a <style> block in the <head> of the HTML file.  
→ Purpose: Applied custom fonts and color styles to heading elements (h1, h2), and adjusted spacing in the contact section for better readability.

3️⃣ External CSS:
Stored in a separate `style.css` file and linked to the HTML.  
→ Purpose: Handled the majority of styling including layout, shadows, borders, and hover effects. This keeps the code clean, reusable, and organized.

────────────────────────────────────────
🎯 Selectors Used & Their Roles:
────────────────────────────────────────

✔ **ID Selector** – `#profile-pic`  
→ Targets the profile image to add a circular border and unique visual identity.

✔ **Class Selectors** – `.bio`, `.card`  
→ `.bio`: Styles the short description elegantly.  
→ `.card`: Styles the entire container with padding, rounded corners, and a subtle shadow for a polished card effect.

✔ **Element Selectors** – `h1`, `h2`, `p`, `ul`, `li`, `body`  
→ Applied to maintain consistency in fonts, spacing, and layout across basic HTML tags.

✔ **Group Selector** – `h1, h2`  
→ Groups headings together to apply shared typography styles efficiently.

✔ **Descendant Selector** – `.contact p`  
→ Ensures that only paragraph elements inside the contact section are affected — keeping styles scoped and intentional.

✔ **Attribute Selector** – `a[href]`  
→ Targets all anchor tags with an href attribute to apply link-specific styling like color and decoration.

────────────────────────────────────────
✨ Bonus Features:
────────────────────────────────────────

🌟 **Hover Effects** – Contact links subtly change color and underline on hover, enhancing interactivity.

🌟 **Shadow and Border Styling** – The profile card features a soft drop shadow and rounded corners, providing a clean and modern appearance.

────────────────────────────────────────
📁 File Structure:
────────────────────────────────────────
- index.html
- style.css
────────────────────────────────────────

