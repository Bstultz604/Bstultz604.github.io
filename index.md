## Brandon's ePortfolio

You can use the [editor on GitHub](https://github.com/Bstultz604/Bstultz604.github.io/edit/main/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files. 

### Introduction
This ePortfolio showcases the computer science skills I have learned throughout my time as an undergraduate at Southern New Hampshrie University. Its contents include a narrated code review, design and justification narratives, a professional self-assesment, and enhancements to previous work focused on key competencies related to software design & engineering, algorithims & datastructures, and databases. These enchaments are improvments made to old work done ealier in my studies here at Southern New Hamsphire University. 

### Table Of Content
1. Professional Self-Assesment
2. Code Review
3. Software Design & Engineering 
4. Algorithims and Datastructures
5. Databases

### 1.) Professional Self-Assesment

   My journey in the field of computer science began in the spring of 2019. Throughout the last 4 years I have explored the many applications and practices of computer science. My study has revealed the importance of teamwork, professionalism, design, fundamentals, and security as the key pillars to success in this field. My work throughout the computer science program has sharpened my awareness of these crucial skills and has enabled me to hone their quality in relation to the works I produce as a software engineer. The obtainment of this foundational knowledge and skill is my first step into deeper and more fulfilling engagement with the professional field of computer science. 
  
	
  The cumulative skills and ability I have gained over the years have enabled me to produce a project to showcase my understanding of the core elements of computer science and my competencies in them. My project took a simple web application I had built earlier in my studies and redesigned/enhanced it. The enhancements I made to the project were made to highlight my competencies in the realms of software design and engineering, algorithms and data structures, and Databases. Software design and engineering are highlighted in my refactoring the design of the web app. My competency in data structures and algorithms are reveled in my use of algorithms to sort data inside the application. Database competency is seen in my design implementation of an external database for use in the app. These are all wrapped together into a single full stack application to highlight my skills and ability as a computer scientist.


### 3.) Software Design & Engineering

  The artifact I chose to make enhancements too is a simple express application. The program simply renders a static HTML web page. The goal of my enhancements is to refactor this web pages front end to utilize angular. These enchantments will showcase my ability to dissect the design elements of the web site while also being able to redesign these elements as modular components. These will add additional functionality to the front-end site and make the web site more modular, reusable, and dynamic. 
  
  The main sweep of enhancements required for this artifact was to decompose the original HTML to find what segments can be logically ordered as separate and individual components. Doing so revealed a few important component models. The first were the navbar and footer of the HTML. These portions of the HTML were designed to be clickable to the user to enable them to navigate to the different pages of the web page. These can be found at the top and bottom of every route page on the site, perfect candidates to be converted into angular components. 
  
  These were the first portions to be redesigned into modular components due to their ubiquitous use and important logical role in the web site. The logical code that dictates the behavior of the elements didn’t differ much between before and after the redesign. This is mostly due to the nature of the elements which was to route the user to different pages on the site. However, where they did differ was in the actual routing. In the original design the HTML elements, when clicked, would simply route the user to the designated static HTML page. After the redesign the routing instead led the user to a specially designed component that would serve up the component elements of the chosen page. This leads us to consider out next elements up for consideration to be refactored, the routing pages themselves. 
  
  The original artifact was comprised of static HTML pages that were switched between using the header and footer elements on every page. With the navbar and footer elements converted into angular components every page would now render with these at the top and bottom, showcasing their excellent modular design. However, the actual content of the page is still reliant on hard coded html. The pages themselves would need to be redesigned. I accomplished this by creating components for each page I wanted to route to. These include pages such as a home page, meal page, and news page. These components would serve two functions; a designator so the routing can be achieved and a container for the smaller components that make up each page.
  
  With the navbar, footer, and page container components created all that remained was the components that comprise the contents of each page. The main components that I utilized in the refactor of these content components was a simple listing component. These were the most dynamic modular elements I designed and added into the refactor process. They served as the main content of all the pages the user can see. The component is simply a container that is used to hold data that was to be retrieved from a data a base. I designed the component to be passed a ‘data’ variable that would inform the component which API call it should use to retrieve and display the correct data. This enabled the component to be highly reusable. Showcasing my ability to creatively solve design issues while also promoting design goals such as modularity and ease of use.
  
  The skills of this artifact enhancement demonstrate three important proficiencies. The first proficiency demonstrated is my ability to employ strategies for building collaborative environments. The second proficiency is the ability to design, develop, and deliver professional-quality oral, written, and visual communications that are coherent, technically sound, and appropriately adapted to specific audiences and contexts. The third proficiency is my ability to use well-founded and innovative techniques, skills, and tools in computing practices for the purpose of implementing computer solutions that deliver value and accomplish industry-specific goals.
  
  My proficiency in employing strategies for building collaborative environments were developed and implemented in this enhancement. The first of the collaborative design choices I made in this enhancement was to utilize version control systems to track and control the design of this enchantment and the future enhancements as well. The version control system git enabled me to better develop and test my work. These changes were then stored in a git repository on GitHub, accessible to any potential future collaborators. In addition to using version control I also ensured the use of explanatory code comments. This enables future developers, inducing myself, to follow the flow of logic of the application more easily. This promotes a higher quality collaborative environment.
  
  Proficiency in the design and delivery of professional communication can be seen in both the supporting narrative of this enhancement as well is the actual redesign itself. The narrative I provided clearly elaborated the decisions I made throughout the design process. In addition to the narrative, I had produced a design document that illustrates the key elements of my redesign process, showcasing my decomposition of the original artifact and redesigned it to use the angular. This document alone serves as a great professional communication device, when combined with the narrative a complete picture of my design process is revealed. Together they highlight my competency to produce professional communication.
  
  Competent proficiency in my ability to use well-founded and innovative techniques, skills, and tools in computing practices is best highlighted in the design document and the implementation of that design. The design document shows my attention placed on redesigning the system to be more modular and dynamic. My implementation of this design document also used the perspective of the user a key guide for constructing the key elements. All while ensuring my code was well commented to support future development. When paired together my competency can be seen in my attention to the best practices of creating modular and user-friendly code.

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Bstultz604/Bstultz604.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
