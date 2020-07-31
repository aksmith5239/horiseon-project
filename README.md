# Code Refactor Starter Code
Steps taken to refactor the code: 

<!-- In index.html: -->
- moved the head title tag above the css link for easier browser readibility
- changed div class of "header" to the semantic element <header>
= changed the div in the header element for the navigation to <nav>
- changed the divs in the main sections to semantic element <section>
- changed the div class of "footer" to the semantic element <footer>
- changed the title from website to "Horiseon Search Engine Optimization"
- added a meta tag with name and description to help browsers know what the site is about
- added alt tags with content to the important images on the page
- added empty alt tags to the unimportant icons on the page
- removed the individual div classes under the content section as these were unnecessary
- removed the individual div classes under the benefits section as these were unnecessary

<!-- In style.css: -->
- updated the .header styles to reflect the change to the semantic <header> styles
- updated the .footer styles to reflect the change to the semantic <footer> styles
- added the header nav declaration to the navigation anchor tags so if other tags are added later they can be styled differently if needed.
- changed the header div css to header nav
- moved .content to below .hero
- since all of the divs in the content section had the same styling with the exception of the image positions, consolidated all of the separate class styles for div, h2 and img under the .content declaration
- since all of the divs in the benefits section had the same styling, consolidated all of the separate class styles for div, h2 and img under the .benefits declaration
- reorganized the css to flow in the same order of the page included moving the <p> tag to a general styles section since all of the paragraph tags had the same styling. 

img for cost management div had a closing </img> tag that was unnecessary. Instead I used the self closing tag on the img.

<!-- customer asks and acceptance criteria -->
User Story: 
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines

Acceptance Criteria:
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title.
