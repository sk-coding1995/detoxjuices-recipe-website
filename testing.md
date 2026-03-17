# Testing - DetoxJuices Recipes

## Testing overview
The website was tested manually during development and again before final deployment. The aim of testing was to check functionality, usability, responsiveness, accessibility, and consistency across all three pages of the website.

## Manual testing record

### Navigation 

clicked each navigation link on every page.
expected: Each link opens the correct page.
Result: All navigation links worked correctly (Pass)

### Home page buttons

Clicked "browse recipes" and "Read our story".
Expected: Each button links to the correct page.
Result: Both buttons worked with no issue (Pass)

### Skip link

Pressed the Tab key from the top of the website page to test keyboard navigation.
Expected: The skip link becomes visible and allows jumping straight to the main content.
Result: The skip link appeared and moved focus to the main content correctly (Pass)

### Images

Loaded each page and reviewed images.
Expected: Images display clearly and scale correctly.
Result: Images displayed correctly with no distortion (Pass)

### Recipe layout

Viewed recipe sections on desktop and mobile sizes.
Expected: Content remains readable and structured.
Result: Layout remained clear across screen sizes (Pass)

### Embedded video

Opened the juices page and tested the video.
Expected: Video loads and does not autoplay.
Result: Video loaded correctly and required user interaction (Pass)

### External link

Clicked on the YouTube link.
Expected: Link opens in a new tab.
Result: Link opened in a new browser tab (Pass)

### Mobile responsiveness

Tested the website on a smaller screen sizes by resizing the browser window.
Expected: Layout stacks and remains easy to read.
Result: Layout adjusted correctly and content remained clear (Pass)

### Desktop layout

Tested large screen sizes.
Expected: Layout stays consistent.
Result: No layout issues found (Pass)

### Accessibility

Checked headings, alt text, skip link, and keyboard navigation.
Expected: Site is accessible and easy to navigate.
Result: Accessibility features worked as intended (Pass)

### Deployment check

Opened live GitHub pages site.
Expected: Live site matches local version.
Result: No differences found (Pass)

## Validation testing

### HTML validation

Each HTML page was checked using the W3C Markup Validation Service.

- 'index.html' - passed after final corrections
- 'juices.html' - passed after final corrections
- 'about.html' - passed after final corrections

### CSS validation

The stylesheet 'styles.css' was checked using the W3C CSS Validation Service.

- 'styles.css' - passed after final corrections

## Bugs found and fixes applied

### Bug 1 - Incorrectly nested section elements causing validation errors

Issue: A '<section>' element in 'juices.html' was not properly closed, which caused incorrect nesting and validation errors.  
Fix: The section was correctly closed and the HTML structure was reorganised so the elements were nested properly.  
Result: The page structure is now valid and the HTML passes validation checks without errors.

### Bug 2 - Incorrect img tag syntax in the hero image

Issue: The hero image in 'index.html' included an unnecessary forward slash at the end of the '<img>' tag, which caused a validation issue.  
Fix: The extra forward slash was removed so the '<img>' tag followed correct HTML5 syntax.  
Result: The HTML now validates correctly with no errors in the W3C Markup Validator.

### Bug 3 - Incorrect image file names causing images not to display

Issue: Images on the juices and about pages were not displaying and only the alt text was shown. This was caused by incorrect file names in the image source paths.  
Fix: The file names in the 'src' attributes were corrected to match the actual image files stored in the 'assets/images' folder.  
Result: The images now display correctly on both pages.

### Bug 4 - Missing recipe image due to empty file

Issue: The 'green-juice.jpg' image in the assets folder appeared correctly named but was empty in the repository, causing it not to display on the juices page.  
Fix: The empty file was removed and replaced with the correct image file in the 'assets/images' directory.  
Result: The image now displays correctly on the page.

### Bug 5 - Incorrect wording and minor HTML issues in juices.html

Issue: Some wording in the ingredients list was inconsistent, such as “tea spoon” instead of “teaspoon”, and minor HTML issues were present on the page.  
Fix: The wording was corrected for clarity and consistency, and the HTML was reviewed and adjusted where needed.  
Result: The page content is now clearer and more consistent, and the HTML is cleaner and better structured.

### Bug 6 - External source attribution was unclear

Issue: Third-party content used in the project was not clearly credited.  
Fix: External content was credited in the README and the embedded YouTube video was identified in the HTML comments.  
Result: The difference between custom code and external content is now clear.

### Bug 7 - README screenshots not displaying

Issue: Screenshot images in the README appeared as text links instead of displaying correctly. This was caused by an incorrect file path to the image inside the assets folder.  
Fix: The image path in the README was corrected so it matched the actual screenshot location.  
Result: The screenshots now display correctly in the README preview and on GitHub.

### Bug 8 - README documentation was too limited

Issue: The original README did not fully explain the project purpose, value, deployment process, or user needs.  
Fix: The README was rewritten to include rationale, user stories, deployment steps, screenshots, credits, validation evidence, and lifecycle information.  
Result: The documentation now gives a fuller explanation of the project.

### Bug 9 - Testing evidence was too weak

Issue: Testing outcomes were not clearly documented and did not show enough manual checks.  
Fix: The testing file was rewritten to include clearer manual checks, validation notes, and recorded fixes.  
Result: Testing is now properly evidenced and easier to follow.

### Bug 10 - Code comments and organisation were inconsistent

Issue: The HTML and CSS were not clearly divided into labelled sections, which made the code harder to follow.  
Fix: Section comments were added across the HTML files and the CSS was reorganised into clearer sections.  
Result: The code is now easier to read and maintain.

### Bug 11 - Responsiveness needed clearer evidence

Issue: Responsive behaviour existed in the code, but the evidence for it was weak.  
Fix: Responsive testing results and screenshots were added to the documentation.  
Result: Responsiveness is now more clearly evidenced for assessment.

## Unfixed bugs

At the final testing stage, no known functional bugs remained in the project.

## Final testing summary

Overall, the final version od DetoxJuices Recipes was tested for functionality, usability, responsiveness, accessibility, deployment consistency, and validation. All checks confirmed the website is working as intended and the deployed version matches the local development version.