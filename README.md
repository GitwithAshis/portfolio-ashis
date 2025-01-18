
## Live Demo
Check out the live version of the website here: [portfolio-ashis](https://gitwithashis.github.io/portfolio-ashis/)

## HTML Structure
- The HTML document begins with the `<!DOCTYPE html>` declaration, which specifies that the document is an HTML5 document.
- The `<html>` tag is the root element of the HTML document, with the `lang` attribute set to "en" for English.
- The `<head>` section contains meta-information about the document, including character encoding, viewport settings for responsive design, and links to external stylesheets and icons.
- The `<body>` section contains the main content of the website, divided into various sections such as header, home, about, skills, work, and contact.

## Header Section:
- The `<header>` element contains a navigation bar (`<nav>`) with a logo and a menu with links to different sections of the page (`Home`, `About`, `Skills`, `Work`, `Contact`).
- The navigation menu is responsive, with a toggle button for mobile devices that shows or hides the menu when clicked.

**Home Section:**
- The home section (`<section id="home">`) includes a welcoming message, social media icons, and an SVG image with a mask and background image.

**About Section:**
- The about section (`<section id="about">`) provides information about yourself, including an image and a brief biography.

**Skills Section:**
- The skills section (`<section id="skills">`) lists your professional skills with progress bars to visually represent your proficiency in various technologies.

**Work Section:**
- The work section (`<section id="work">`) showcases your work with images of your projects.

**Contact Section:**
- The contact section (`<section id="contact">`) includes a form for visitors to fill out and contact you.

**Footer:**
- The footer contains social media links, an email address, and copyright information.

### CSS Explanation

**CSS Variables and Base Styles:**
- CSS variables (custom properties) are defined in the `:root` selector for consistency, including colors, font sizes, margins, and z-index values.
- Base styles are applied to all elements, including box-sizing, margin, font-family, font-size, and color.

**Layout Styles:**
- The header is styled to be fixed at the top of the page with a box shadow and background color.
- The navigation menu is styled to be responsive, with different styles for mobile and desktop views.
- Each section has padding and margins for proper spacing, and the section titles are styled with a specific font size and color.
- The home section includes styles for the welcoming message, social media icons, and the SVG image.
- The skills section includes styles for the progress bars, with different colors representing different skills.
- The work section includes styles for the project images, with hover effects for visual interest.
- The contact section includes styles for the form inputs and the send button.
- The footer is styled with a background color, text color, and social media icons.

 ## JavaScript Explanation

**Menu Show and Hide:**
- A function (`showMenu`) is defined to toggle the visibility of the navigation menu on mobile devices by adding or removing a CSS class.
- The function selects the toggle button and navigation menu by their IDs and adds a click event listener to the toggle button.

**Active Link Highlight on Scroll:**
- A function (`scrollActive`) is defined to update the active link in the navigation menu based on the scroll position.
- The function selects all sections with an ID and calculates their height and top position.
- When the user scrolls, the function checks if the current scroll position is within the boundaries of a section and updates the active link accordingly.

**Scroll Reveal Animation:**
- The ScrollReveal library is initialized with specific animation properties, including origin, distance, duration, and delay.
- The `sr.reveal` method is used to apply scroll reveal animations to various elements, such as the home data, about image, skills subtitle, skills text, and work images.
