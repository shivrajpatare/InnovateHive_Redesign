# InnovateHive Redesign Walkthrough

I have successfully redesigned the InnovateHive index page with a modern, premium aesthetic.

## Changes Made

-   **Backend**: Set up a lightweight Flask application (`app.py`).
-   **Frontend Architecture**: Created a modular template system using `base.html` and `index.html`.
-   **Styling**: Implemented a custom dark theme using CSS variables, gradients, and glassmorphism effects in `style.css`.
-   **Interactivity**: Added smooth scrolling and navbar scroll effects in `script.js`.

## Sections Implemented

1.  **Hero Section**: Dynamic headline with gradient text and call-to-action buttons.
2.  **About Us**: Team image with overlay effects and key statistics.
3.  **Services**: Grid layout with hover effects and custom gradient icons.
4.  **Projects**: Featured work showcase with image hover overlays.
5.  **Blogs**: Article cards with "premium" typography.
6.  **Testimonials**: Bootstrap carousel for client feedback.
7.  **Contact**: Modern form with floating labels and a clean layout.

## Verification

-   **Responsiveness**: The layout uses Bootstrap's grid system to ensure compatibility across Desktop, Tablet, and Mobile.
-   **Accessibility**: High contrast text colors and semantic HTML tags have been used.
-   **Functionality**: All links and hover states are functional.

## Next Steps

-   Run `python app.py` to view the site locally.
-   Deploy to a hosting platform like Render or Railway as per the assignment instructions.
