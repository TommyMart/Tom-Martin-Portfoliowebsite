# Portfoliowebsite
# Hi! 

And welcome to Tom Martin's portfolio website's readme page. 

You can visit my Portfolio Website **[here](https://tommartinportfolio.netlify.app/)** .

And access the code via the Github repo **[here](https://github.com/TommyMart/Tom-Martin-Portfoliowebsite)** .

## Purpose

The purpose of my portfolio website is to communicate and demonstarte my developer and IT professional abilities to prospective employers. Projects will be added to the website as I progress as an aspiring developer to reflect this. The website features a projects and a blog page to display my coding experience, abilities and interests, it also has a skills page and a link to my resume should be required. The end goal of the website is to aid in gaining full-stack employment or an internship at a company who shares similar values. 


## SITEMAP 

This sitemap was developed so that I would have an idea of the layout of the website before commencing the build. 

![picture of sitemap](<images/Screenshot 2024-03-26 at 10.35.46 am.png>)

The sitemap shows the 'root' Home page and the different paths that can be taken to access the website. The green LinkIn and GitHub paths are links to new external websites that are not hosted by Netlify with the other wesbite content. The navigation bar provides the user an easily accessible pathway to the six main pages no matter what page they are on - these page pathways are home, about, skills, projects, blog and contact. The resume pdf is a link to my resume pdf, that is stored as a pdf file on Netlify with the rest of the website, but is not responsive like the rest of the site because it is a pdf. The orange email pathway is to an automated email, that carries my email to their chosen email prodiver of choice. Finally, are the blog posts in yellow. These are only accessible from the blog page and have a pathway back to the blog page via a button at the end of the page. Alternatively, the user could just click 'blog' in the nav bar if they didn't want to scroll until the end of the page.

## Responsive Design

Responsive design was used to improve the viewer experience depending on what screensize they are viewing the website from. CSS flexbox layout was utlised to enhance the overall experience by wrapping sections of the page next to each other when the screen size allows. This can be seen in the screenshot example below,
where the skills are aligned next to each other in a row instead of a longer column that would need to scrolling to view. CSS media screens were also used to change styling, such as font-size, depending on the viewing screen size to assist in legibility. 

![picture of page sections in a row using flexbox](<images/Screenshot 2024-03-26 at 10.53.26 am.png>)

## Target Audience

My portfolio website is inteded to showcase my work, skills and personality to potential employers who have technical knowledge of information technology, development, programming languages and development stacks.

## Tech Stack
The technologies used to build my portfolio website are as followes:

- **HTML** - for the basic structure and content. 
- **CSS** - for styling, flexbox, media screens and annimations. 
- **Markdown** - for the writing the READAME.MD file. 
- **VS Code** - IDE for writing the code. 
- **GitHub** - for version control.
- **Netlify** - for the deployment platform. 

## Wesbite Aesthetics

I wanted the website to have a simple, modern, clean and sharp aesthetic. To achieve this, high constrasting black and white was chosen as the two main colours, along with a soft but bright lilac for larger text extra styling, used on the current selected navbar page and when hovering over buttons. The website was designed with a mobile first approach with accessibility by vision impaired and colourblind a key necessity. 

![colour palette](<images/Screenshot 2024-03-26 at 3.18.34 pm.png>)

A simple **Nunito sans serif** font was used to improve legibility and cohesively work with the modern aesthetic of the site. Simple annimations were used to make the wesbite more interesting, though these were purposefully not overdone to keep inline with the chosen aesthetic. 

![Nunito font example](<images/Screenshot 2024-03-26 at 1.23.40 pm.png>)
![Nunito font example](<images/Screenshot 2024-03-26 at 1.23.26 pm.png>)

## Wireframes 

Wireframes were designed to gain direction before embarking on the website build, this gave me a geographical reference point if ever I should need it.  

![wireframes of home, about and skills pages](<images/Screenshot 2024-03-26 at 9.49.52 am.png>)
![wireframes of projects, blog and contact pages](<images/Screenshot 2024-03-26 at 9.50.03 am.png>)

**Home Page** 

- Nav bar linking six HTML documents together via a component - 'Home' highlighted in lilac to let the viewer know what page they are on.
- An image of myself to build a personal connection.
- H1 'Tom Martin' heading. 
- A paragraph sentence in italics. 
- A button styled component 'Examples of my work!' that takes the viewer to the projects page.
- Links to professional LinkedIn and GitHub pages via a logo image anchor link.  
- Lastly a footer. 

**About**

- Nav bar linking six HTML documents together via a component - 'About' highlighted in lilac to let the viewer know what page they are on.
- H1 'About Me' heading.
- Two paragraphs about me. 
- H2 'Education' heading.
- List of education. 
- Lastly a footer. 

**Skills**

- Nav bar linking six HTML documents together via a component - 'Skills' highlighted in lilac to let the viewer know what page they are on.
- H1 'Skills' heading.
- Fours lists that use flex box to determine if they are aligned in a row, column, or both. 
- Button styled component that takes the viewer to a pdf of my resume when clicked.
- Lastly a footer.

Flexbox examples
Flex Row
![Flex row skills example](<images/Screenshot 2024-03-27 at 3.04.47 pm.png>)
Flex Column
![flex column skills example](<images/Screenshot 2024-03-27 at 3.06.02 pm.png>)

**Projects**

- Nav bar linking six HTML documents together via a component - 'Projects' highlighted in lilac to let the viewer know what page they are on.
- H1 'Projects' heading. 
- Six project styled components including a heading, short description paragraph and an image. 
- Each project component has a button styled component that links the viewer to the project if it is ready or says 'coming soon'. 
- Lastly a footer.

**Flexbox examples**

Flex Row
![flex row projects example](<Screenshot 2024-03-27 at 3.07.49 pm.png>)

Flex Column
![flex column projects example](<images/Screenshot 2024-03-27 at 3.06.52 pm.png>)

**Blog**

- Nav bar linking six HTML documents together via a component - with 'Blog' highlighted in lilac to let the viewer know what page they are on.
- H1 'Blog' heading. 
- Five blog styled components including a heading, date published and an image. 
- Each project component has a 'read more' button styled component that links the viewer to the blog post.
- Lastly a footer.

**Flexbox examples**

Flex Row
![flex row blog example](<Screenshot 2024-03-27 at 3.09.30 pm.png>)

Flex Column
![flex column blog example](<images/Screenshot 2024-03-27 at 3.10.22 pm.png>)

**Contact**

- Nav bar linking six HTML documents together via a component - 'Contact' highlighted in lilac to let the viewer know what page they are on.
- H1 'Contact' heading. 
- A button styled component that links the viewer to my mail email address via a 'mailto' link.
- An address section with name, location and email. 
- A paragraph section in italics acklowedging the traditional owners of the land in which the website was built. 
- Links to professional LinkedIn and GitHub pages via a logo image anchor link.  
- Lastly a footer. 

## Components

- **Navigation Bar** - the nav bar component of the website has been styled with the intenion of providing the viewer with a clear directory for navigation. The white text on the black background makes the words standout, when the mouse is hovered over the selections their size ratios are transformed which communicates to the viewers that they are clickable links that takes you to that page. The current nav bar page is also highlighted in blue, to remind the viewer incase they were unsure whicg page they were on. 

- **Buttons** - the buttons throughout the site are all styled the same way, the font size and family, the background colour, the corners and the hover change in colour. This consistent approach makes it easier for the viewer to know what component is what and limit guessing and website flow errors. 

- **Blog and Paragraph Tile Sections** - seperate projects and blog post sections have been purposefully seperated and styled the same way to achieve consistency. They each have a solid black border with the same rounded edges, that when hovered over become 90 degree angles. The images also each have a lilac drop down shadow and increase in ratio size when hovered over. This subconsciously communicates to the viewer that these sections are part of the same family of projects or blog posts. 

- **Paragraphs** - body copy was styled the same way, to achieve consistency and increase legibility. Paragraphs that stretch across the screen in desktop view are difficult to read because it can be hard to find the next line. The same font size and family have been used to communicate to the viewer that the content is a paragraph about the current page subject. 

## Thanks for looking! 