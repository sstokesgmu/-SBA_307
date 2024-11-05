Overview of SBA 307

Welcome to BudgetMe, a free and open source budget management application. Compare your finiances between your different bank accounts and set up plans to save you money.

Objective:
This SBA will test your skills in creating a simple website with a clean layout and styling. Your website should have a well-developed HTML structure and follow good visual design methodologies in order to produce a satisfying user experience.

Technical Specifications: 
The site is split into three different pages: landing, account, and about me. Each page uses Bootstrap grid system to help align content into the center. While Flexbox is applied to more specific nested elements such as the _card container_ (landing page line 192-204). 

**Landing Page**
The landing page will be the place where the user can see the status of their account with the graph, which is a place holder picture. They can change which account they see using the drop down. Using a a combination of selectors, pseudo selectors, attribute selectors, and combinators I was able to change the size of the text for the heading (landing line 28-30 and line 145) and the color of the drop down menu options (landing 41-47). The most unique part of the landing page is the side bar which will be used to for looking at the most recent transactions the user made. To make it is used a Bootstrap to contain it in the top row in the section with the account graph id. I gave it a column size of 3 which pushed it to the right side of the row. Then with CSS styles I applied a position property of fixed on the the full sidebar, then used I used the right property to affect the horizontal position of the object.
