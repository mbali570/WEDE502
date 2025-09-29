# WEDE502
in this submission I and done some edits and changes to my project to make it better and improve missing information 
📖 Part 2 – Designing the Visuals: CSS Styling & Responsive Design
🎯 Learning Outcomes

At the end of this part, I have:

Created and linked an external CSS stylesheet to all HTML pages.

Applied decorative, typographic, and layout styling for a desktop solution.

Used appropriate selectors to style page elements efficiently.

Leveraged the cascading nature of CSS for minimal selectors.

Used browser developer tools to test and debug styles.

Applied responsive styling with relative units, media queries, and breakpoints.

Implemented responsive images with srcset, sizes, and the <picture> element.

📝 Implementation Details
1. Feedback Corrections (Part 1)

Following lecturer feedback from Part 1, I implemented the following changes:

Improved HTML semantics (e.g., used <header>, <main>, <footer> instead of <div>s).

Added missing alt attributes to all images.

Corrected inconsistent indentation and formatting in HTML.

Linked a single external stylesheet (css/style.css) to all pages.

2. CSS Styling for Desktop

Created style.css and linked it to all pages.

Applied a CSS reset for browser consistency.

Established base typography using rem for scaling (font-family, size, weight, line-height, spacing).

Defined layout structure using CSS Grid and Flexbox (responsive header, sidebar, main content, and footer).

Styled interactive elements with pseudo-classes (:hover, :focus, :active).

Applied consistent color scheme, backgrounds, borders, and shadows.

3. Responsive Design

Used relative units (rem, em, %) for typography, spacing, and layout widths.

Identified breakpoints:

Mobile: ≤600px

Tablet: 601px – 1024px

Desktop: ≥1025px

Implemented media queries for typography scaling, navigation layout, and grid structure.

Used responsive images:

Applied srcset and sizes for different resolutions.

Used <picture> element for alternate image crops on mobile.

Ensured images are fluid using max-width: 100%; height: auto;.

4. Testing & Iteration

Used browser developer tools to test responsiveness on multiple devices.

Iteratively adjusted typography, spacing, and layouts.

Collected screenshot evidence of the design at desktop, tablet, and mobile breakpoints.

📷 Screenshots (Responsive Testing)

Desktop (1920px wide)


Tablet (768px wide)


Mobile (375px wide)


🔄 Changelog
## Changelog

- [2025-09-25] Corrected HTML structure to use semantic tags.
- [2025-09-25] Added missing alt attributes for accessibility.
- [2025-09-26] Created external stylesheet (css/style.css) and linked it to all pages.
- [2025-09-27] Applied base typography styles using rem units.
- [2025-09-27] Implemented Flexbox for navigation and Grid for page layout.
- [2025-09-28] Styled interactive elements (hover, focus, active states).
- [2025-09-28] Added media queries for mobile, tablet, and desktop breakpoints.
- [2025-09-28] Integrated responsive images with srcset and picture element.
- [2025-09-28] Tested across devices and included screenshots in README.

✅ Conclusion

Part 2 successfully applied CSS styling and responsive design principles. The website now:

Has a consistent design with a clear layout.

Uses scalable typography and relative units.

Adapts to multiple devices and screen sizes.

Optimises images for faster loading.

Provides a user-friendly and accessible experience.
