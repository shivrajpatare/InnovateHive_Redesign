# InnovateHive Redesign Implementation Plan

## Goal Description
Redesign the InnovateHive index page to be modern, responsive, and "premium" using Flask, HTML, CSS (Bootstrap + Custom), and JavaScript. The goal is to improve aesthetics, usability, and accessibility while retaining all existing content sections.

## User Review Required
> [!IMPORTANT]
> - **Design Direction**: The design will focus on a "premium" look with dark mode elements, gradients, and glassmorphism, as per the "Web Application Development" guidelines.
> - **Content**: Content will be replicated from the screenshots of the existing site.
> - **Images**: Placeholder images or generated images will be used where original assets are not easily extractable.

## Proposed Changes

### Backend
#### [NEW] [app.py](file:///C:/Users/shivr/.gemini/antigravity/scratch/INNOVATEHIVE-REDESIGN/app.py)
- Simple Flask application.
- Route `/` to render `index.html`.

#### [NEW] [requirements.txt](file:///C:/Users/shivr/.gemini/antigravity/scratch/INNOVATEHIVE-REDESIGN/requirements.txt)
- `flask`

### Frontend

#### [NEW] [templates/base.html](file:///C:/Users/shivr/.gemini/antigravity/scratch/INNOVATEHIVE-REDESIGN/templates/base.html)
- HTML5 boilerplate.
- Bootstrap 5 CDN links (CSS & JS).
- Google Fonts (Inter/Outfit).
- FontAwesome CDN for icons.
- Navigation Bar (Responsive).
- Footer.

#### [NEW] [templates/index.html](file:///C:/Users/shivr/.gemini/antigravity/scratch/INNOVATEHIVE-REDESIGN/templates/index.html)
- **Hero Section**: Dynamic headline, CTA, modern background.
- **About Section**: Company overview with visual hierarchy.
- **Services Section**: Cards with icons and hover effects.
- **Projects Section**: Grid or Carousel of projects.
- **Blogs Section**: Article cards.
- **Testimonials Section**: Carousel of client feedback.
- **Contact Section**: Functional-looking form and contact info.

#### [NEW] [static/css/style.css](file:///C:/Users/shivr/.gemini/antigravity/scratch/INNOVATEHIVE-REDESIGN/static/css/style.css)
- Custom variables for colors (Premium palette).
- Overrides for Bootstrap defaults.
- Animations (Fade-in, slide-up).
- Glassmorphism effects.

#### [NEW] [static/js/script.js](file:///C:/Users/shivr/.gemini/antigravity/scratch/INNOVATEHIVE-REDESIGN/static/js/script.js)
- Navbar scroll effect.
- Intersection Observer for scroll animations.
- Form submission handling (prevent default + alert).

## Verification Plan

### Automated Tests
- None (Visual design focus).

### Manual Verification
1.  **Setup**:
    -   `pip install -r requirements.txt`
    -   `python app.py`
2.  **Visual Check**:
    -   Open `http://127.0.0.1:5000` in Chrome.
    -   Verify all sections exist: Home, About, Services, Projects, Blogs, Testimonials, Contact.
    -   Check responsiveness on Mobile (DevTools).
    -   Verify hover states and animations.
3.  **Functionality**:
    -   Click Nav links -> Smooth scroll to section.
    -   Submit Contact form -> Success message (mock).
