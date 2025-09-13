# Project Blueprint

## Overview

This document outlines the design, features, and styling of the personal portfolio website for Charles McCabe. The website showcases his robotics projects and provides information about his skills and experience.

##- V1 - Project Initialization

- **Project Setup:**
    - Main HTML file: `charlesMcCabe.html`
    - Styling: `styleSiteWeb.css`
    - Assets: Various images of the projects.

- **Styling:**
    - **Typography:**
        - Headings: "Century Gothic", "Courier New"
        - Body: "Century Gothic", "Courier New", sans-serif
    - **Color Palette:**
        - Primary: #009688 (teal)
        - Text: #333 (dark gray), white
        - Background: #f0f0f0 (light gray)

- **Features:**
    - Responsive navigation bar.
    - Project showcase with image overlays for details.
    - Contact information and social media links.

##- V2 - Professional Style Enhancement

- **Enhancements:**
    - **Typography:**
        - Headings: 'Montserrat', sans-serif (imported from Google Fonts)
        - Body: 'Lato', sans-serif (imported from Google Fonts)
    - **Color Palette:**
        - Primary: #00796B (darker teal)
        - Background: #f4f4f4 (softer gray)
    - **Visual Effects:**
        - Added a subtle drop shadow to project containers for a "lifted" look.
        - Applied a subtle noise texture to the background for a premium feel.

##- V3 - Content and Layout Refinements

- **Content:**
    - Corrected French grammar, spelling, and phrasing throughout the site (`charlesMcCabe.html` and `contact.html`) for a more professional tone.
- **Layout:**
    - **Contact Page:** Centered the contact information text and repositioned the "Download CV" button below the text for a clearer call to action.
    - **"About Me" Section:** Re-styled the section for a more visually appealing and balanced layout. The profile picture is now circular with a colored border and positioned to the left of the descriptive text. The image size has been adjusted to ensure it doesn't take up too much space, and the text alignment is preserved for a professional look.

##- V4 - Code Refactoring and Contact Enhancement

- **Code Quality:**
    - Refactored the HTML files (`charlesMcCabe.html` and `contact.html`) to remove inline styles. All custom styles have been moved to the `styleSiteWeb.css` stylesheet for better maintainability and consistency.
- **Layout & Style:**
    - **"About Me" Section:** Corrected the aspect ratio of the profile picture to prevent distortion.
    - **Footer:** Removed the GitHub social icon to simplify the design.
    - **Contact Page:** Added a prominent "Profil LinkedIn" button to provide a direct link to the professional profile.

##- V5 - "About Me" Section Enhancement

- **Layout & Style:**
    - **"About Me" Section:** Increased the size of the profile picture to 200px to give it more visual weight. The layout was adjusted to accommodate the larger image while maintaining a balanced and professional appearance.

##- V6 - "About Me" Image Refinement

- **Layout & Style:**
    - **"About Me" Section:** Further increased the size of the profile picture to 250px and applied a `border-radius` of 40% to create a distinct oval shape. The layout's `flex-basis` was adjusted to ensure the larger, styled image remains well-integrated with the surrounding text.

##- V7 - Final "About Me" Image Sizing

- **Layout & Style:**
    - **"About Me" Section:** Increased the profile picture to its largest size yet at 300px. The `flex-basis` for the image and text containers were balanced to 50% each to ensure the layout remains proportional and visually appealing, even with a dominant central image.

##- V8 - Emphasizing the Profile Image

- **Layout & Style:**
    - **"About Me" Section:** Maximized the impact of the profile picture by increasing its size to 350px. To support this, the `max-width` of the `.about-me-container` was expanded to `1000px`. The `flex-basis` properties of the image and text containers were fine-tuned to `45%` and `55%` respectively, ensuring a well-proportioned and visually engaging layout. The image size for mobile screens was also increased to `280px` for better visibility.

- **Current Plan:**
    - The current plan was to make the profile picture as large as possible while maintaining a good layout, which has been completed.
