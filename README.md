Overview of SBA 307
Welcome to BudgetMe, a free and open-source budget management application. This app helps you manage your finances by tracking balances across multiple bank accounts and creating personalized savings plans to achieve your financial goals.

Objective
This SBA will test your skills in creating a simple website with a clean layout and styling. Your website should have a well-developed HTML structure and follow good visual design methodologies in order to produce a satisfying user experience.

Technical Specifications
The site consists of three main pages: Landing, Account, and About Me. Each page uses the Bootstrap grid system for centering content, with a combination of Flexbox applied to specific elements, such as the card container on the landing page (lines 192-204).

Landing Page
The Landing page displays an overview of the user’s financial status with a placeholder graph. Users can switch between different accounts using a dropdown menu.

Notable features and customizations include:

Text and Dropdown Styling: A combination of selectors, pseudo-selectors, attribute selectors, and combinators are used to style heading text (lines 28-30 and 145) and customize dropdown menu colors (lines 41-47).

Sidebar: A distinctive feature of the landing page, the sidebar will display the user’s recent transactions. It’s positioned within the top row alongside the account graph section and assigned a Bootstrap column size of 3, which aligns it to the right inside the container (line 144 & 157). To give it a more fluid position, CSS is used to make the sidebar position: fixed, and position it to the right of the view port. (line 50-55) 

The sidebar also includes a simple animation: when the cell blocks (e.g., those labeled "hello") are interacted with, their background color changes to a darker gray. ((line 67 - 75)

Account Page
The Account page serves as a template for future login and more complex information the user might need. It includes a login form and search bar, as well as a table for transaction information. While simpler than the Landing page, it includes a unique feature:

Loading Bar: A CSS keyframes-based loading bar provides smooth animation. Currently, it loops continuously, animating the element width from 0% to 100% and back over the animation duration (line 31-51).

