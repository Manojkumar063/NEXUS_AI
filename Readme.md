<img width="1537" height="897" alt="image" src="https://github.com/user-attachments/assets/099c011b-21a8-4ce4-bb99-fa7ef0b6ad5a" />
Modern AI Search Interface
Overview
This project is a modern, responsive web interface for an AI-powered search application, designed with a sleek, dark-themed UI. It features a sidebar navigation, a dynamic search input area, and subtle animations to enhance user experience. The interface is built using HTML, CSS, and JavaScript, with no external dependencies, making it lightweight and easy to integrate.
Features

Responsive Design: Adapts to various screen sizes, including mobile, tablet, and desktop.
Modern Sidebar: Includes a brand logo, navigation items, and a new chat button with hover effects.
Dynamic Search Input: Auto-resizing textarea with placeholder and action buttons for attachments, voice, and camera inputs.
Animated Background: Subtle floating background elements for visual appeal.
Smooth Animations: Hover effects, transitions, and a pulsing PRO badge for interactivity.
Accessibility: Semantic HTML and ARIA-compatible elements for better usability.
Dark Theme: Gradient background with a glassmorphism-inspired sidebar and search container.

File Structure

index.html: The main HTML file containing the structure, styles, and JavaScript for the interface.

Getting Started
Prerequisites

A modern web browser (Chrome, Firefox, Safari, Edge, etc.).
No additional dependencies or build tools are required.

Installation

Clone or download the repository.
Open index.html in a web browser to view the interface.

Usage

Sidebar Navigation: Click on navigation items (Home, Discover, Library, Favorites, Settings, Upgrade, Account) to highlight the active item. The sidebar adapts to a horizontal layout on mobile devices.
New Chat Button: Click to initiate a new chat session (currently logs to console).
Search Input: Type a query in the textarea, which auto-resizes based on input. Press Enter or click the submit button to log the query to the console.
Action Buttons: Hover over the attachment, voice, or camera buttons for tooltips (functionality can be extended).
Responsive Behavior: On screens smaller than 640px, the sidebar becomes a horizontal scrollable bar, and the layout adjusts for better mobile usability.

Customization
To customize the interface, modify the following sections in index.html:

Colors: Adjust the CSS variables in the :root or specific class styles (e.g., background, color, linear-gradient).
Icons: Replace emoji icons in the sidebar and action buttons with SVGs or font icons (e.g., Font Awesome).
Logo and Branding: Update the brand-text and logo-text content, and modify the brand-icon or pro-badge styles.
Search Logic: Extend the JavaScript in the <script> section to integrate with an API or backend for actual search functionality.
Animations: Tweak the @keyframes (e.g., float, pulse) or transition properties for different effects.

Technical Details

HTML: Uses semantic elements like <nav>, <main>, and <button> for accessibility.
CSS:
Utilizes modern features like backdrop-filter, linear-gradient, and box-shadow for a premium look.
Responsive design with media queries for 768px and 640px breakpoints.
Animations use cubic-bezier for smooth transitions and keyframes for background effects.


JavaScript:
Auto-resizes the textarea based on input.
Handles search submission and Enter key press.
Applies animation delays to background elements for staggered effects.



Limitations

The current implementation logs search queries to the console. To make it functional, integrate with a search API or backend.
Action buttons (attach, voice, camera) are placeholders and require additional logic for functionality.
No hamburger menu is implemented for mobile sidebar toggling; this can be added for enhanced mobile UX.

Future Enhancements

Add a hamburger menu for mobile sidebar toggling.
Integrate with a real AI search API (e.g., xAI's API at https://x.ai/api).
Implement actual functionality for action buttons (file upload, voice input, camera).
Add light theme support with a theme toggle.
Enhance accessibility with ARIA labels and keyboard navigation.

License
This project is unlicensed and provided as-is for educational or personal use. For commercial use, please contact the author.
Contact
For questions or feedback, refer to the xAI community or support channels at https://x.ai.
