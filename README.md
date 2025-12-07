Milestone 1 - Personal Portfolio Website (HTML Only)

Pages included
- index.html (Home)
- projects.html (Projects)
- contact.html (Contact)

Elements included
- List index.html (My Skills)
- Table projects.html (Project list)
- Image imagesprofile.jpg
- Special character &mdash; and &copy;

Milestone 2 - Personal Portfolio (CSS Styling)

Pages styled:
- Home_page.html
- projects.html
- contact.html

Color scheme and fonts:
- Colors: Blue (#004080), Light Blue (#0066cc), Light Gray (#f7f7f7)
- Font: Arial, Helvetica, sans-serif

Features:
- Styled navigation with hover effect
- Table with alternating row colors
- Consistent layout and spacing across all pages

Known issues:
- Some sections need more spacing adjustments


Project Milestone 3 - Portfolio Interactivity with JavaScript

I added JavaScript form validation to my Contact page.
The feature checks that all fields (name, email, and message) are filled before submitting.
If any field is empty, it shows an alert asking the user to complete the form.
If everything is filled, it displays a thank-you message.
I used variables, conditionals, a function, and an event listener for this feature.
I plan to improve it later by adding dark mode.



Personal Portfolio Website - Yasser



GitHub Repository:
https://github.com/Yassou911/Portfolio_Website


Overview
This project is a personal portfolio website created for my web development course. It showcases who I am, the projects I am working on, and ways to contact me. The site is built with HTML, CSS, and JavaScript and is designed to be responsive, accessible, and easy to navigate.


Pages Included
- Home_page.html: Introduces me and lists my basic skills.
- projects.html: Lists several projects with their descriptions, statuses, and links.
- contact.html: Provides contact information and a working contact form with validation.


JavaScript Features
1. Contact Form Validation
   - The contact form checks that the Name, Email, and Message fields are not empty before allowing submission.
   - If any field is empty, an alert message appears and the form is not submitted.
   - If all fields are filled, a thank-you message is displayed to the user.

2. Dark Mode with Saved Preferences (localStorage)
   - Each page has a "Toggle Dark Mode" button in the header.
   - When clicked, the site switches between light mode and dark mode by adding/removing a CSS class.
   - The selected theme (light or dark) is saved using localStorage so that the user’s preference is remembered on future visits.

3. Dynamic Project Filter (Advanced Feature)
   - On the Projects page, there is a search box above the projects table.
   - As the user types, JavaScript filters the table rows in real time.
   - Only the projects whose text (name, description, or status) match the search term remain visible.
   - This feature uses event listeners, DOM manipulation, and string methods.




Challenges and Notes
- One challenge was integrating all the JavaScript features across multiple pages without causing errors. I solved this by checking if elements exist before adding event listeners.
- Another challenge was keeping the design consistent while adding new sections. I used shared CSS styles for headings, tables, forms, and buttons to keep the site cohesive.
- Before deployment, I will double-check all links and file paths to make sure they work in the live environment.


