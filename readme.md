# Readme
---
### Overview of the website
This pages works as my online CV, as an assignment from RevoU. This page have a purpose as follows:
1. **Showcase Skills and Projects:** Highlight your technical skills and the projects you’ve undertaken, providing context and insight into your capabilities and creative process.
2. **Build Your Professional Brand:** Create a digital footprint that conveys your personal brand by sharing your story, interests, and professional journey.
3. **Engage Users:** Design a user-friendly experience that allows visitors to navigate your site easily and find the information they seek without difficulty.

### Features Implemented
This site include the required 3 section, and also added some adjustment and additional sections so it could be more apealing as an Online CV.
1. **Home Section:**
  The Home Section contains the title of the page, and a navigation links.
2. **About Me Section:**
  This section contain a brief introduction of me. It tells you about my background, about my likes and hobbies, and also about what I am doing now.
3. **Projects Section:**
  I modified this section as I dont have any Project yet. Instead I put my work experience here.
4. **Contact Section**
  This section act as a way for visitor to contact me. There is quite a lot of technologies used here.

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
6. **Others**
  * I added my Name and Date at the end of the page.
  * I used *div* tag to put the *class* attribute for center-aligned the *body* section.
  * Repo:
  https://github.com/Revou-FSSE-Feb26/milestone-1-adam-fsse
  * Live url:
  https://revou-fsse-feb26.github.io/milestone-1-adam-fsse/



-end of file-