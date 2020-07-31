# Code Refactor Starter Code
Steps taken to refactor the code: 

<!-- In index.html: -->
- moved the head title tag above the css link for easier browser readibility
- changed div class of "header" to the semantic element <header>
- changed the div in the header element for the navigation to <nav>
- changed the title from website to "Horiseon Search Engine Optimization"
- added a meta tag with name and description to help browsers know what the site is about
- changed the div class of "footer" to the semantic element <footer>



<!-- In style.css: -->
- updated the .header styles to reflect the change to the semantic <header> styles

- added the header nav declaration to the navigation anchor tags so if other tags are added later they can be styled differently if needed
- changed the header div css to header nav
- updated the .footer styles to reflect the change to the semantic <footer> styles

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
