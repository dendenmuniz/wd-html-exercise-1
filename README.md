# HTML Introduction
Your goal is to create an online curriculum vitae that you can share with prospective recruiters.
In addition, with will publish it to a web server using GitHub pages and use Tiny URL to personalize the URL.
Of course you will have to learn some basics, check the following links for documentation and guides:

#### Recommended elements:
- HTML5 at [W3Schools](https://www.w3schools.com/html/html5_intro.asp). An alternative guide that also works very well is [HTML Dog](https://htmldog.com/guides/html/).
- [CSS 3.0](https://www.w3schools.com/css/)
- [GitHub Pages hosting](https://pages.github.com)

#### Extra elements:
- [Google Fonts](https://fonts.google.com)
- [Font awesome icons](https://fontawesome.com)
- [Tiny URL](https://tiny.cc)

## Setup
Our front-development project is a single-page document that consists of three parts:
1. The markup file (The HTML file)
2. The column layout (CSS grid)
3. Personalizing style (The CSS file)

When it comes to the IDE, VS Code is recommended. (If you're using IntelliJ IDEA Community Edition it won't support
some web technologies.)

### Install VS Code
Visit the website [VS Code](https://code.visualstudio.com) and download the installer using the button with the label "Stable build". Then proceed with the installation.

## Main task
This task will consists of three parts:
1. The markup file (the HTML file `index.html`)
2. The column layout within the markup file (Bootstrap grid)
3. Personalizing style (a CSS file)

### Example result
Click here to download the example for [desktop](https://2020.school/uploads/wd-html-exercise-1-example-desktop.png) and [mobile](https://2020.school/uploads/wd-html-exercise-1-example-mobile.jpg).

![Eduardo Alvarez Curriculum Vitae](https://2020.school/uploads/wd-html-exercise-1-reference.png)
*Figure 1: CV Template*

Use it as a reference as for how your final page could look like.
Analyze the structure: introduction, work experience, education, and contact information.
Think about what sections you need and what additional content can you include to improve it.


#### Writing the markup information

1. Use the tag `<main>` to contain your whole project. The equivalent of an entire physical book.
2. Use the tag `<header>` for your introduction part. The equivalent of the cover of a book.
3. Use the tag `<section>` to specify a complete section that can stand on their own. This is the equivalent of an entire book chapter.
4. Use the tag `<article>` to specify a small part piece of text or content. The equivalent of a page on your book.
5. Use the tag `<footer>` to specify the last part of your page. The equivalent of the back cover of a book.

![HTML reference structure](https://2020.school/uploads/wd-html-exercise-1-html-structure.png)
*Figure 2: HTML reference structure*

Other than that you are free to use your own styling and feel free to use your own touch
to your CV document!

#### Adding the basic column grid
The modern version of CSS allows you to create column grids, withouth needing to use additional frameworks using the property CSS Grid. In this project we will use a 3 column layout.
1. Read about [CSS Grid](https://css-tricks.com/snippets/css/complete-guide-grid/).
2. Use the properties `grid-template-columns` and `grid-column-gap`
3. Double-check that works both on desktop and mobile (to quickly simulate a mobile device just narrow your browser window)

#### Personalizing
We can further personalize the project by applying some basic CSS properties to your HTML tags. To do so, follow these steps:
1. Create a new folder called `css`.
2. Create a file called `style.css` inside the previous folder.
3. Create a link tag on your project head that points to that style (check the css guide on how
to do this).

#### Publish on GitHub pages
To publish your CV follow these steps:
1. On your GitHub git repository, click on settings.
2. Scroll down until you find the section "GitHub Pages" and click on the source
3. Select your master branch.
4. Click on the green bar with the link that appeared just above this section.

![GitHub pages step 1](https://2020.school/uploads/wd-html-exercise-1-github-1.png)
*Figure 2: GitHub pages step 1*

---

![GitHub pages step 2-4](https://2020.school/uploads/wd-html-exercise-1-github-2.png)
*Figure 3: GitHub pages steps 2 to 4*

### Extra tasks
#### Adding fonts
Go to [Google Fonts](https://fonts.google.com), look for a typography that you like (this example uses Gothic A1) and then follow these steps:
1. Press the red circle with a "+" sign to add to the download list.
2. Press the black bar with the text "Family Selected".
3. Copy the HTML link tag that appears below the subtitle "Embed Font".
4. Paste the link tag at the end of your head tag inside your web file.
5. Copy the CSS code that appears below the subtitle "Specify in CSS".
6. Paste the code on the body tag in your CSS file.

#### Adding icons
Go to [Font awesome icons](https://fontawesome.com) to browse for icons that you want to add and then follow these steps:
1. Add this script to the head tag of your page: <script src="https://kit.fontawesome.com/86134dd369.js" crossorigin="anonymous"></script>
2. Copy the tag of the icon you want to use (check the image below for reference)
3. Paste the HTML tag inside your document.
4. Don't forget to add a margin-right or bottom to avoid having the icon to close to any other element.

![Font awesome tag](https://2020.school/uploads/wd-html-exercise-1-font-awesome.png)
*Figure 5: Where to find the icon tag on Font Awesome*

#### Using a URL shortener for better sharing
This guide will not cover how to purchase or configure a domain name like [eduardoalvarez.com](http://www.eduardoalvarez.com), but at least will teach a quick workaround to have a personalized link to share with friends and potential employers.

With your CV published on GitHub Pages, follow these steps:
1. Go to [Tiny URL](https://tinyurl.com). 
2. Pasted the link on *Enter a long URL to make tiny:* field.
3. Write your name and surname on the *Custom alias* field.
4. Press the *Make TinyURL!* button.

