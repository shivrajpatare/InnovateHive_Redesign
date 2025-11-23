# InnovateHive Redesign

This is a redesign of the InnovateHive website index page, built with Flask and Bootstrap 5. The design focuses on a premium, modern aesthetic with dark mode, glassmorphism, and smooth animations.

## Features

-   **Modern UI/UX**: Dark theme with vibrant gradients and glassmorphism effects.
-   **Responsive Design**: Fully responsive layout using Bootstrap 5 grid system.
-   **Interactive Elements**: Hover effects, smooth scrolling, and entrance animations.
-   **Modular Code**: Clean separation of concerns with Flask templates and static assets.
-   **Accessibility**: Semantic HTML and readable contrast ratios.

## Technologies Used

-   **Backend**: Python, Flask
-   **Frontend**: HTML5, CSS3, JavaScript
-   **Framework**: Bootstrap 5
-   **Fonts**: Google Fonts (Outfit, Inter)
-   **Icons**: FontAwesome

## Setup Instructions

1.  **Clone the repository** (or navigate to the project directory):
    ```bash
    cd INNOVATEHIVE-REDESIGN
    ```

2.  **Create a virtual environment** (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3.  **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4.  **Run the application**:
    ```bash
    python app.py
    ```

5.  **Open in browser**:
    Navigate to `http://127.0.0.1:5000`

## Design Rationale

-   **Color Palette**: A deep dark blue/slate background (`#0f172a`) conveys professionalism and depth. Primary purple/indigo gradients (`#6366f1` to `#a855f7`) add a modern, tech-forward feel.
-   **Typography**: 'Outfit' for headings gives a geometric, modern look, while 'Inter' ensures excellent readability for body text.
-   **Layout**: Generous whitespace and card-based layouts improve content digestibility.
-   **Animations**: Subtle fade-in and slide-up animations guide the user's attention without being distracting.

## Project Structure

```
INNOVATEHIVE-REDESIGN/
├── static/
│   ├── css/
│   │   └── style.css      # Custom styles
│   └── js/
│       └── script.js      # Frontend logic
├── templates/
│   ├── base.html          # Base template with Navbar/Footer
│   └── index.html         # Main landing page content
├── app.py                 # Flask application
├── requirements.txt       # Python dependencies
└── README.md              # Project documentation
```
