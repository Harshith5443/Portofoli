# Testing Plan for Portfolio Website Changes

## Changes Made
- Removed "View Projects" and "Email Me" buttons from the hero section heading.
- Separated embedded CSS from `index.html` into an external `style.css` file and linked it properly.

## Critical Areas to Test
- **Hero Section**
  - Verify the heading displays correctly without the removed buttons.
  - Ensure layout and spacing remain consistent.
- **Styling**
  - Confirm all styles are applied correctly from the external `style.css`.
  - Check fonts, colors, backgrounds, and responsive behavior.
- **Other Page Sections**
  - Scroll through all sections (About, Skills, Projects, Certification, Footer).
  - Verify no visual regressions or broken layouts.
- **Responsiveness**
  - Test on different screen sizes (desktop, tablet, mobile).
- **Links and Buttons**
  - Verify all remaining links and buttons function as expected.

## Testing Levels
- **Critical-path testing:** Focus on the hero section and overall styling.
- **Thorough testing:** Full page navigation, interaction, and responsiveness.

## Next Steps
Please specify which level of testing you prefer:
- Test only the hero section and styling (critical-path).
- Test the entire page thoroughly (thorough testing).
