README file for Milestone Project 1 - The Xzitz

## UX / UI
### Project goal: 
      to create a website where the band can share information, content and upcoming gigs with fans, they also need a page where fans or potential promoters can submit queries and booking requests.  
### Use Cases
   1. Fans of the band: As a fan or follower of the band, I'd like to find out more about them, see photos and videos of previous gigs and find out where the next gigs are going to be and when. I would also like to be able to get in touch with them, to find out how much it would cost to book them for a private party. 
   2. Pub / Club promoters: As a pub landlord I'd like to find out more about the band, see photos and videos of previous gigs to assess if the quality and style of their music would fit in with my venue. I want to see when their upcoming gigs are and when, so I can attend and see what they are like live, before I consider booking them. I would also like to be able to get in touch with them to discuss potential bookings for the future. 
## Testing
   I used the link to the live page [https://ubi-feher.github.io/Milestone_Project_1/index.html] to carry out some functional testing, due to lack of time this section is not as well documented as I would have liked.
   1. First I made sure the page loads as expected and the navigation menu works and it highlights the page name when the user hovers over it:
      
      Desktop view
      ![Navigation menu-desktop](https://github.com/user-attachments/assets/84a0774e-a733-4759-8f70-70b910ebde53)
      Mobile view (I added a breakpoint to the Tagline to hide it on mobile devices)
      ![Navigation menu-mobile](https://github.com/user-attachments/assets/defb270d-a8de-4af8-9fb8-322a64e985b5)

    2. Then I made sure in the Band Members section the names are shown side-by-side on the desktop              version
    
    
    On the mobile version they are shown in individual lines to make it easier to read
    
    3. On the Gallery page the photos are shown in blocks of 3 for the desktop version, and the Videos are all in one row
    
    
    For the mobile version both the photos and videos appear in individual lines to make them easier to view
    
    
    4. On the Contact page, if the user tries to submit the form without completing all the required fields, they get a prompt and cannot submit until they fill in the missing info
   
    5. When the user completes the form correctly and submits it, they are taken to the Confirmation page
    
      
### Bugs discovered
   I wanted to add a toggle button for the navigation bar to follow good UX principles when the page is viewed on a mobile, I tried to use the Bootstrap navbar toggle function for this, however when I applied it to the pages the button was invisible. Unfortunately I ran out of time and wasn't able to fix this issue so I removed the toggle function and opted for a simpler nav bar where the items align vertically on mobiles, to make sure I have a working solution.
## Wireframes
Wireframes were created using Balsamiq [https://balsamiq.com/wireframes/] , I have attached screenshots here:
1. Home page
   ![Wireframe-Home page-desktop](https://github.com/user-attachments/assets/dd98c459-c669-4a98-b638-f7506576feba)
   ![Wireframe-Home page-mobile](https://github.com/user-attachments/assets/874a5ca6-2930-40c3-a1ed-db9a4981a198)
2. Gallery page   
   ![Wireframe-Gallery page-desktop](https://github.com/user-attachments/assets/66a0e961-0fef-4074-9aec-cbe2be178c18)
   ![Wireframe-Gallery page-mobile](https://github.com/user-attachments/assets/215a7277-f840-4b51-a993-50aa254baff6)
 3. Contact page  
   ![Wireframe-Contact page-desktop](https://github.com/user-attachments/assets/454493ff-89f3-4177-bfe8-7975117ad9db)
   ![Wireframe-Contact page-mobile](https://github.com/user-attachments/assets/9ade2bb0-330e-4403-b1d1-9b3089a1f776)
4. Confirmation page
   ![Wireframe-Confirmation page-desktop](https://github.com/user-attachments/assets/148eef2f-1b56-444c-94bd-dc0937342e21)
   ![Wireframe-Confirmation page-mobile](https://github.com/user-attachments/assets/963bd9c9-3b0d-4c52-8194-fa6f21725e21)

## Code
   1. I used Hover.css to apply a "sweeping" effect to the navigation Menu, to make it more visually appealing and interesting when a user hovers over one of the items, I took the code from:  [https://ianlunn.github.io/Hover/]
   2. I used free to use icons from Fontawesome for the Facebook, Contact and Website symbols in the footer section, I wanted to add a quick and easy way for users to check out the band's Facebook page [https://www.facebook.com/profile.php?id=61557937204854] and additional web page on Lemonrock [https://www.lemonrock.com/thexzitz] I took the code from:
  [https://fontawesome.com/search?q=facebook&o=r&m=free]
   3. I used Bootstrap v4.3 [https://getbootstrap.com/docs/4.3/getting-started/introduction/]for the grid containers and rows to create the page layout, the navigation bar, the form and Submit button on the Contact page, and then customised them to ensure each mandatory field is completed before the form is Submitted.
   4. I used Google fonts [https://fonts.google.com/] "Shadows Into Light" for the Header and Footer sections, and "Montserrat" for the body text
  
  
## Content
 with the band's permission I used the following content:
    1. Text for the Introduction section, Band Members and Upcoming gigs from the band's Wordpress page: [https://thexzitz.wordpress.com/]
    2. Photos and Band logo from: the band's Facebook page: [https://www.facebook.com/profile.php?id=61557937204854] , in order to keep their branding consistent I used their existing logo, I just applied a filter to the image to make the colours a bit more muted to fit in with the colouring of the page better. 
    3. Videos from: the band's Wordpress page: [https://thexzitz.wordpress.com/]

## Deployment
   The project was developed using the Code Institute CI Template [https://github.com/Code-Institute-Org/ci-full-template]
   To deploy this page to GitHub Pages from the GitHub repository  I completed the following steps:
   1. Log in to GitHub
   2. Search for "ubi-feher/Milestone_Project_1"
   3. From the project page click on Settings and scroll down until you find the GitHub Pages option on the right hand side
   4. From the Source menu select Master Branch, this will start deploying the page, which can take a little while
   5. Go back to the project page and on the right hand side under the Deployments section a link will appear to the page:
      ![GitHub page link](https://github.com/user-attachments/assets/c57749ad-251f-4703-b36d-426f3ad7a2a6)

   More details on how to create GitHub pages can be found here: [https://pages.github.com/]
## Lighthouse
   I ran the Lighthouse report on all 4 pages with the following results:
   1. Home page
      ![Lighthouse-Home page](https://github.com/user-attachments/assets/2ff67d9b-dd97-43e6-907d-e4017009bdd8)
   2. Gallery page
      ![Lighthouse-Gallery page](https://github.com/user-attachments/assets/888fc19b-5997-44d2-a3ff-f4d10997144c)
   3. Contact page
      ![Lighthouse-Contact page](https://github.com/user-attachments/assets/0fbc7056-8037-4c30-a15f-5bc09afa8ead)
   4. Confirmation page
      ![Lighthouse-Confirmation page](https://github.com/user-attachments/assets/8dec5fc3-d0fa-4602-ae88-5176f760bd60)

## W3C CSS Validation
   I uploaded my style.css file by direct input to [https://jigsaw.w3.org/css-validator/] and it validated as CSS level 3:
   ![jigsaw CSS validation](https://github.com/user-attachments/assets/90e931a5-2215-4a49-bb5e-6286e9629a86)
   ![jigsaw validation info](https://github.com/user-attachments/assets/3ff97d20-1b25-4b19-8ea0-975c4e095933)
## W3C HTML Validation
   I uploaded my index.html file by direct input to [https://validator.w3.org/detailed.html#validate-by-uri] and it passed:
   ![HTML validation](https://github.com/user-attachments/assets/85e66e00-6854-404c-a3f9-8deff45cbec4)
   ![HTML validation results](https://github.com/user-attachments/assets/ac586a45-2fff-4def-877d-366e6bcfd464)



