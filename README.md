My assignment consists of 5 tasks, from 0 to 4. In this work I used HTML, CSS media queries and Bootstrap to make pages change for different screen sizes. Firstly I worked with simple text and boxes then moved to columns and navigation and a portfolio page.

I separated tasks into different folders to make it more convenient to see each part of assignment. The main document is 'index.html', where I placed links to the tasks.

<img width="214" height="503" alt="image" src="https://github.com/user-attachments/assets/6cdfa89d-79b0-4595-a7e2-a2351b95ef4c" />



Task 0. Responsive Typography
The HTML:
<img width="854" height="400" alt="Screenshot 2026-10-10 021851" src="https://github.com/user-attachments/assets/59b8eea8-1e02-49f1-ba65-bcbc2aeb5e47" />


The CSS:
<img width="508" height="523" alt="Screenshot 2026-10-10 021902" src="https://github.com/user-attachments/assets/4c01ff7b-c352-4c56-aa13-26df3d3c0f26" />


For this task I created a simple page with an "h1" and a "p". I connected "style.css" and added the viewport meta tag, so the page uses the device width on mobile.

<img width="776" height="128" alt="image" src="https://github.com/user-attachments/assets/b4d13438-6f82-4acf-915c-df4a54c814ee" />


The HTML:
<img width="836" height="546" alt="Screenshot 2026-10-10 021910" src="https://github.com/user-attachments/assets/236d39a8-2204-4b69-8e97-1f6209bb3c8c" />


The CSS:

<img width="754" height="696" alt="Screenshot 2026-10-10 021924" src="https://github.com/user-attachments/assets/d271ac03-a1db-4e6d-add4-c9c96733331b" />


I created one container and placed 3 boxes inside it. The text in them is Abish, Adil and Muratuly. All boxes use the same class, so their background, padding and text alignment are the same.

The normal box width is 300px. In my media queries it changes to 33% at 486px and below, and to 50% at 400px and below. These percentages control the box width, but padding and gaps also take space, so 33% does not automatically mean exactly three boxes in a row.

<img width="1859" height="451" alt="image" src="https://github.com/user-attachments/assets/cdf9fd06-1681-48bf-95ed-9ff16252fed3" />
<img width="931" height="784" alt="image" src="https://github.com/user-attachments/assets/c169bdda-ac81-464f-9eec-bf666daaf5ab" />





Task 2. Bootstrap Responsive Columns

The HTML:

<img width="971" height="918" alt="Screenshot 2026-10-10 021946" src="https://github.com/user-attachments/assets/81f2523d-65d5-4310-b5cb-50719338593a" />



In this task I connected Bootstrap and used the structure `container`, then `row`, then columns. I placed three blocks inside the row.

Each column has 'col-12 col-md-6 col-lg-4'. Bootstrap divides a row into 12 parts:

- 'col-12' takes the full row on small screens.
- 'col-md-6' takes half of the row from 768px, so two blocks can stay together and the third moves below.
- 'col-lg-4' takes one third from 992px, so all three blocks can stay in one row.

I also used 'mt-4' for space above the container and 'g-4' for space between columns. 
This part was easier because Bootstrap already has the responsive rules. I only needed to choose the classes.


Task 3. Bootstrap Navigation Bar

The HTML:

<img width="927" height="900" alt="Screenshot 2026-10-10 021953" src="https://github.com/user-attachments/assets/cb9e0333-f926-4131-bd05-5dac4c678f7f" />

The CSS:

<img width="619" height="216" alt="Screenshot 2026-10-10 022001" src="https://github.com/user-attachments/assets/6d21e9bc-88e9-4800-bbad-00b931fc4231" />

For the navigation I used 'navbar bg-dark' and a container inside it. For the logo I used a basic 'img' with 'logo.png' and a width of 70px. Then I added links inside the menu.

The links are placed in a div with the class 'hamburger'. In the media query 'max-width: 768px', I used 'display: flex' and 'flex-direction: column' for this class. It makes the links go vertically on a smaller screen.

In this version, the mobile layout is a vertical list of links. The class name 'hamburger' alone does not create a button that opens and closes the menu. A toggle button and collapse behavior would be the next step for a full hamburger menu.

<img width="1919" height="282" alt="image" src="https://github.com/user-attachments/assets/1c972928-5381-4b14-b85c-1d97d879e6d6" />
<img width="917" height="492" alt="image" src="https://github.com/user-attachments/assets/0dadae65-eb2b-4943-b376-ba97f841a1cb" />

## Task 4. Responsive Portfolio Page

For the last task I combined the previous ideas into a portfolio page. The page has a header with navigation, a main part with projects and personal information, and a footer at the bottom.

The main layout uses Bootstrap Grid. The projects section uses 'col-12 col-lg-8', and the sidebar uses 'col-12 col-lg-4'. On a large screen they stay next to each other. On smaller screens both take the full width, so the sidebar goes below the projects.

Inside the projects section, cards use 'col-12 col-md-6'. This gives one card per row on mobile and two from the medium screen size. The cards keep the project title, description and button together.

For the footer I used a simple section with centered text.



