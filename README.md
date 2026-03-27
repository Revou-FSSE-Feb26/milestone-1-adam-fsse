# Readme
---
### Overview of the website
This pages works as my online CV, as an assignment from RevoU. This page have a purpose as follows:
1. **Showcase Skills and Projects:** Highlight your technical skills and the projects you’ve undertaken, providing context and insight into your capabilities and creative process.
2. **Build Your Professional Brand:** Create a digital footprint that conveys your personal brand by sharing your story, interests, and professional journey.
3. **Engage Users:** Design a user-friendly experience that allows visitors to navigate your site easily and find the information they seek without difficulty.
4. **Apply CSS:** Apply CSS styles to create a welcoming atmosphere, ensuring the design captures visitors' attention and reflects your unique personality.

### Features Implemented
This site include the required 3 section, and also added some adjustment and additional sections so it could be more apealing as an Online CV.
1. **Home Section:**
    * The Home Section contains the title of the page, and a navigation links.
    * Apply CSS styles to create a welcoming atmosphere, ensuring the design captures visitors' attention and reflects your unique personality.
    * Use CSS to enhance typography, colors, and layout.
2. **About Me Section:**
    * This section contain a brief introduction of me. It tells you about my background, about my likes and hobbies, and also about what I am doing now.
    * Make the biography visually engaging through formatting (e.g., font styles, colors, spacing).
    * Add styles that differentiate sections of content for better readability.
3. **Projects Section:**
    * I modified this section as I dont have any Project yet. Instead I put my work experience here.
4. **Contact Section**
    * This section act as a way for visitor to contact me. There is quite a lot of technologies used here.
    * Design the contact form with user-friendly elements using CSS for better interaction (e.g., input field styling, button design).
    * Ensure the form is visually appealing and aligned with the overall website theme.

### Technologies Used
1. **Semantic, Indentation, and Comments**
  * I try to type the code as neat as possible. I used these tags as an initial structure and developed the page from there.
  * I also marking the codes with comments, and utilized the indentation, for an easily code troubleshooting.
  ```
  <html>
  <head>
  </head>
  <body>
    <header></header>
    <main></main>
    <footer></footer>
  </body>
  </html>
  ```
  
2. **Meta, Style, and CSS**
  * I started with the Title, trying to be stylist and ended up just adding equal mark on the sides .
  * With Style and CSS I try to make the page with more consistent looks so it will looked similar trough different browser. So I define the body width, and make it center aligned. Thought later on, I made the *Form* in *Contact Me* section Left Aligned just because it looks better that way.
  so I defined the class here, and later used the attribute *class* on some tags.
  * I made update on CSS. I add css tailwind script link, and add font link. But for now i used the internal CSS style to make it more easy, and planned it to change into Tailwind CSS later.
  
3. **Home Section, Page Title, and Navigation**
  * I used the *h1* tag for the title, as the home section works as the page's title, also it contain the navigation feature, I also added the navigation feature at the *footer* to make it easy to navigate from the end of the page.
  * Inside the *nav* tag, I used a *table* tag to make it more organized and easier to set the spacing later, but it turned out to be more complicated, and i decided to leave it for now.
  * And then I used the labels for ID-ing the *a href* tag for the navigation links.
  
4. **About Me and Portofolio Section**
  * Here I just used a simple *Paragraph* tag, and style the sub-title with *h2* and *h3*.
  * I also put the navigation link at the end of each section for convenience.
  * On the portofolio section i used the *class* attribute to make it left-align so to make it more pleasing in the eye.
  
5. **THE CONTACT ME SECTION**
  * This section is the most tiring section. I have to setup various Attribut for the *input* tag to work correctly.
  * First I used *label* tag to give labels for the input box. And give it the *for* attribute to link it with its corresponding *input* tag's *id*.
  * I differentiate the *id* name with 'x' from the *name* attribute.
  * I used the *required* attribute on the 'Name', 'E-Mail', 'Message' *input* tags.
  * I used the *type* attribute to define the input type.
  * I used the *placeholder* attribute to serve as a format guidance for the input text.
  * I made the 'Reason for Contact' with *select* tag, and using the *option* and *optgroup* tag to classified the selection. I also used the attribute *disabled selected hidden* so the user cannot select it by mistake.
  * I used the checkbox *type* on the *input* tag for the 'Prefered Contact Method'.
  * I used the file *type* on the *input* tag for the 'Upload File' part.
  * I used two *button* tags with the *submit* and *reset* *type* of attribute each for 'Submit' and 'Reset' button.
  * Also this section used the *fieldset* with the *class* attribute to coverage the whole form and make it left-aligned.
6. **More details on CSS style**
  * I used the *body* to center all the content using the options:
  ```
            display: flex;
            flex-direction: column;
            align-items: center;
  ```
* And then wrap it under *html* to center the whole *body*.
* I used *margin*, *width*, *text-align*, etc to make the layout looks good.
* i also defined the *background-color*, and using *background-repeat* to apply a background image. I used *background-blend-mode: overlay;* to blend the pattern with the background color.
* As i defined the CSS Tailwind I need to redefine the *h1,h2,h3* I used this to style and color the *h1,h2,h3* also.
* I fixed the table for *nav* that I used before, and changed it into *display: flex;*.
* I also use the *hover* to make the navigation more appealing.
* I restyle the *Ordered List* and customize the list marker.
* I make the *fieldset* more enggaging, and style it like a real sheet of form.
* I also styled the other component on *Contact* section like *input*, *label*, *button*, and *textarea*.
* I using the media query for mobile, tablet, and desktop view. The query is based on screen width, *max-width: 480px* is mobile, *max-width: 1024px* with *min-width: 481px* is for tablet, and *min-width: 1025px* for desktop. I changed the font size for each media queries.
7. **Profile Picture**
* I added my photo. I put it inside a *div* wrapper. And used the option *overflow: hidden;* and *transform: translateY(-15px);* to better croped the photo into a circle frame.

8. **Others**
  * I added my Name and Date at the end of the page.
  * I used *div* tag to put the *class* attribute for center-aligned the *body* section.
 

### How To Access
You can access the website from this Live URL:
  https://revou-fsse-feb26.github.io/milestone-1-adam-fsse/

You can access the repositories from here:
  https://github.com/Revou-FSSE-Feb26/milestone-1-adam-fsse
 


-end of file-