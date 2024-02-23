# RefactorChallenge

## Introduction
This repository contains the solution to the HTML CSS Git Challenge focused on improving accessibility and search engine optimization (SEO) for a marketing agency's website. The challenge involves refactoring existing code to meet accessibility standards and ensure the website is optimized for search engines.

## Challenge Description
As a marketing agency, the goal is to have a codebase that adheres to accessibility standards to enhance the user experience for all visitors, including those with disabilities. Additionally, ensuring the website is optimized for search engines is crucial for visibility and discoverability online.

## Challenge Elements
### User Story
```markdown
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

### Acceptance Criteria
```markdown
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
THEN I find a concise, descriptive title
```
### Mockup
<details>
<summary>Click to Expand</summary>
![Mockup](https://static.bc-edx.com/coding/full-stack/01-HTML-Git-CSS/assets/01-html-css-git-homework-demo.png)
</details>

## Solution
This challenge involves understanding the following key concepts:
- Code Refactoring: Refactoring existing code to improve its structure, readability, and efficiency without changing its external behavior.
- Semantic HTML: Using HTML elements that convey meaning and structure to both the browser and developers, improving accessibility and SEO.
- Web Accessibility Standards: Ensuring that websites and web applications are designed and developed to be accessible to all users, including those with disabilities, by following established accessibility guidelines such as WCAG (Web Content Accessibility Guidelines).

To address the challenge requirements, the following steps were taken:

- Reviewed the existing codebase to identify areas for improvement and applied refactoring techniques to enhance the code's clarity and maintainability.
Semantic HTML: Updated HTML elements to use semantic tags appropriately, such as `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, and `<footer>`, to better define the structure and purpose of different sections of the webpage.
- Ensured that all HTML elements have appropriate attributes, such as alt attributes for images, and that the document structure follows a logical order to aid users of assistive technologies.
- Reviewed and updated the content and structure of the webpage to improve search engine visibility and ranking, including the use of descriptive and relevant `<title>` and `<meta>` tags.

By implementing these solutions, the Horiseon Marketing Agency website now meets accessibility standards, resulting in improved user experience and enhanced search engine optimization.


#### Specific Changes made to refactor the original HTML code:
<details>
<summary>Click to Expand</summary>
  
```markdown
1. **Document Title:**
   - Changed the title of the webpage to "Digital Marketing Strategies | Horiseon" to provide a more descriptive and SEO-friendly title.

2. **Header Section:**
   - Added a `<nav>` element to wrap the navigation links for better semantic structure.
   - Enclosed the navigation links within an unordered list `<ul>` and list items `<li>` for proper HTML hierarchy.

3. **Main Image:**
   - Renamed the class from meetingMainImage to mainImage for consistency and clarity.
   - Updated the alt attribute of the image to provide a descriptive text: "A group of people sat around a table discussing digital marketing strategies."

4. **Main Content Section:**
   - Renamed the class of each section (e.g., search-engine-optimization, online-reputation-management, social-media-marketing) to use lowercase and hyphens for better readability and consistency.
   - Updated the alt attributes of images within each section to provide descriptive alternative text.

5. **Aside (Benefits) Section:**
   - Enclosed each benefit within a `<div>` element with an appropriate ID for better organization and structure.
   - Updated the alt attributes of benefit images to provide descriptive alternative text.

6. **Footer Section:**
   - Updated the class name of the footer to footer for consistency.
   - Changed the `<h2>` tag to `<h4>` for proper semantic hierarchy.
   - Provided a more concise and descriptive text within the `<h4>` tag: "Made with ❤️️ by Horiseon".
```
These changes aim to improve the semantic structure, accessibility, and SEO optimization of the webpage while maintaining its functionality and visual appeal.
</details>

#### Specific Changes made to refactor the original CSS code:
<details>
<summary>Click to Expand</summary>
  
```markdown
1. Header Section:
   - Moved the background-color property below the color property for better readability and organization.
   - Added a comment for the navigation menu styling.
     
2. Navigation Menu Styling:
   - Renamed the `.header` div selector to `.header nav` to better reflect its purpose.
   - Changed the margin-top property to padding-top for consistency with other padding declarations.
   - Moved the float property from the `ul` element to the `nav` element for proper alignment.
   - Added comments for styling the list and list items within the navigation menu.
     
3. Main Image Styling:
   - Renamed the `.hero` class to `.meetingMainImage` for clarity and consistency with the HTML class attribute.
   - Updated the selector to target the img element within the `.meetingMainImage` class for specific image styling.
   - Removed the width property and added the max-width property to ensure responsive image sizing.

5. Main Content Styling:
   - Renamed the `.content` class to `.mainContent` for clarity and consistency with the HTML class attribute.
   - Removed the width property and added the max-width property to prevent content overflow on smaller screens.

7. Benefits Section Styling:
   - Added comments for styling the benefits section and individual benefits.
   - Updated the selector to target the benefits by ID (`#benefit-lead`, `#benefit-brand`, `#benefit-cost`) for more specific styling.
   - Changed the class selectors to ID selectors to ensure unique styling for each benefit section.
   - Removed the height property to allow the benefits section to adjust dynamically based on content.
   - Removed redundant font-family declarations and consolidated them into one declaration.

9. Footer Styling:
    - Updated the selector to target the footer by class (`.footer`) for consistency with HTML class attribute.
    - Changed the `<h2>` tag to `<h4>` for proper semantic hierarchy and updated the selector accordingly.
    - Removed the color property from the footer text to inherit the color from the parent element.
```
Overall, the changes aim to improve readability, organization, and consistency in the CSS code.
</details>

## Usage
<details>
<summary>Click to Expand</summary>

### Viewing the Source Code
1. Clone the repository
   - Open your terminal or command prompt.
   - Navigate to the directory where you want to clone the repository.
   - Run the following command:
     ```markdown
     git clone <repository_url>
     ```
   Replace <repository_url> with the URL of the repository.
2. Navigate to the Project Directory:
   - After cloning the repository, navigate to the project directory using the cd command:
     ```markdown
     cd <repository_name>
     ```
   Replace <repository_name> with the name of the cloned repository directory.
3. Explore the Source Code:
   - Once inside the project directory, you can explore the source code using any text editor or Integrated Development Environment (IDE) of your choice.
   - Open the files located in the project directory to view and analyze the source code.
4. Optional: View Remote Repository:
   - If you prefer not to clone the repository locally, you can also view the source code directly on the GitHub website.
   - Visit the repository page on GitHub at <repository_url>.
   - Navigate through the repository's file structure to view individual files.
   - GitHub provides syntax highlighting and a user-friendly interface for browsing the source code online.
</details>

## License
This project is licensed under the MIT License - see the `LICENSE` file for details.



