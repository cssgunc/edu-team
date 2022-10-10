# Project 1: Personal Portfolio

Hello everyone, welcome to the first project of the CS+SG education team! In this first project, you will create your very own **Personal Portfolio website!** This project will help you get used to coding in HTML and CSS. 

In addition, setup for some of the tools you will use throughout the semester are provided here.

## Section 0: Getting Started with GitHub

### Step 0: Authenticate with GitHub

The Education Team uses GitHub to manage projects! GitHub is an internet hosting service for version control - Git. Version control is an extremely powerful tool that computer scientists use to save, organize, and share their code.

GitHub is used by millions around the world, and is the most popular version control system in use. Most of you are either in or beyond COMP 110 and most likely already have a GitHub account. 

CS+SG uses GitHub for all of their development projects, and the Education Team will also use GitHub. 

__To get started with GitHub, there are a few basic steps:__

1. **Sign Up:** If you have not already created an account with GitHub, [please do so](https://github.com/).
   
2. **Join the GitHub Classroom:** Join the GitHub classroom for the Education Team [here](https://classroom.github.com/classrooms/35878762-edu-team-f22).

### Step 1: Accept the Project

Now that you are connected to GitHub Classroom, you have to accept this project! This creates a **repository** that is entirely your own -- you can upload your files into this repository and I will be able to view all of your submissions through here.

## Section 1: Creating your Website!

The fun part begins now! In the first lesson video, you learned the basics of HTML and CSS for structuring and styling websites. Now, you will be able to make your very own website.

**In this project, you will create your very own personal portfolio site. Your website will include your name, picture, majors, coursework, and other cool things so that others can get to know you better!**

This project will be pretty simple to implement, and completing the basic steps should not take too long -- however, feel free to try and experiment with adding more content or style to the website if you wish! 

The best way to learn more about HTML and CSS, as well as programming in general, is to explore beyond the barebone requirements of assignments, textbooks, and exams. You learn from experience, and as part of the Education Team, you are free to explore all of the tools we go over!

Feel free to navigate to the `index.html` file in the directory.

Typically, the HTML file for the landing page of a website has the name `index.html` as convention. This is the file you will edit to create your website.

To see how your website renders in the browser, simply find it in your File Explorer and click! HTML files should automatically open in the browser.

Now that you are in the `index.html` file, you will see blocks of text that look like this:

```html
<!-- STEP n: Do something here -->
```

In HTML, these are **comments!** Comments allow you to add text into your code files without actually having the text run. Adding comments to your code greatly improves your code's readability and comprehensiveness. In this this, I added comments to specify each step you should complete! Instructions and details for each step are below.

There are 9 steps on the `index.html` file.

### Step 1: 

The first step (as well as steps 2 and 3) are within the `<head>` element! Recall from the lesson that the `<head>` tag provides extra information about our website for the brower to use.

The first step is to add a title for your website. This will not show up on the website itself, rather it will show up on the "tab" on your browser!

The specific HTML element used to create a title was mentioned in the lesson video.

Feel free to name the website whatever you like!

### Step 2:

> **THIS STEP WAS ALREADY COMPLETED FOR YOU!** However, please take a look at the text below to understand what is happening:

Next, the `<head>` element of your website also includes references to other files that your HTML file will use later. We want to connect our `styles.css` CSS stylesheet to our HTML file! To do this, we use the following element:

```html
<link rel="stylesheet" href="/styles/style.css">
```

The `<link>` element allows us to link external files to our HTML file. 

As you can see, `<link>` takes in two arguments: `rel` and `href`.

The `rel` argument stands for relationship, and this refers to the relationship between the linked file and the source file. In this case, the file we are linking is a `.css` file, so it is a `"stylesheet"` for our source `index.html` file that we are currently working in.

The `href` argument specifies URLs! You will see later that the `<a>` tag, specifically used to create *links*, also uses this argument. In this case, we want to refer to our `styles.css` file. The relative path to this file is `/styles/styles.css`, since our CSS file is inside a folder.

### Step 3:

We are now moving on to the `<body>` section! Now, elements you add will actually show up on your webpage.

This step is simple: simply add a header to your website that includes your name (first and last)! 

Recall the `<h1>`, `<h2>`, and `<h3>` tags from the lesson video to create a header.

### Step 4: 

The next step is fun -- adding an image! 

The `<img>` tag in HTML is used to denote an image element. The documentation can be found [here](https://www.w3schools.com/tags/tag_img.asp).

Try to add an image to your website by following the documentation! W3Schools is an EXCELLENT resource for learning HTML. Since HTML has such a large variety of element types, W3Schools is your best friend when exploring how to use these! 

Becoming familiar with using documentation as a source is extremely useful both in the Education Team and CS+SG in general, but in all of your UNC COMP classes as well.

### Step 5:

The next step is to add a headline! This is usually a single sentence that sumamarizes you.

This headline should be a header, but one decently smaller than the one you chose for Step 3. I recommend using `<h3>` or `<h4>` for this step.

### Step 6, 7, and 8:

The next three steps include adding sections for "About" "Education", and "Coursework". For each of these sections, feel free to use a header to denote each section. Then, add some text using the `<p>` paragraph tag in each of those sections:

**Challenge:** Try to use an *unordered list* to create bulletpoints for the coursework you have taken at UNC! Unordered lists look like:

* Item 1,
* Item 2, and
* Item 3!

To create an unordered list, use the `<ul>` tag to denote the list. Then, inside of this element, each individual bullet is represented using a *list item*, or `<li>`! For example:

```html
<ul>
    <li>Item 1,</li>
    <li>Item 2, and</li>
    <li>Item 3!</li>
</ul>
```

The code above should create the exact same list shown as an example earlier.

### Step 9:

The last step is to fill out a *table*! We can create entire tables using HTML, and that is pretty cool. The structure is broken into three parts:
- `<table>`: This is the outer container for the entire table.
- `<tr>`: These elements represent each row in a table.
- `<th>` / `<td>`: These elements represent each cell in a row! `<th>` are reserved for table headers (often only the first row), while `<td>` is reserved for data within the table.

The documentation for creating tables is [here](https://www.w3schools.com/html/html_tables.asp)! 

Try to add one more row to the existing table, and using `<td>` elements, fill out your answers to the "prompts"!

### Step 10-12:

You are now all done with the structure of your website! The last three steps are located on the `styles.css` file and mainly serves as a place for you to experiment styling your website. 

Feel free to explore all of the different styles! Again, [W3Schools](https://www.w3schools.com/css/default.asp) is a great resource for this.

There are no hard requirements for this section, however feel free to style your site to your heart's content and explore all of the different styling options.

Feel free to add `class` or `id` arguments to any of your elements in your `index.html` file if needed! Follow the same structure to style elements as shown in the lesson slides.

## Section 2: Submitting

After you create your website, push your code to the project GitHub repository that GitHub Classroom created for you! Feel free to message me if you have problems with submitting. I might create separate video showing you all how to do that.

## Final Thoughts

I hope this project was not too difficult to start off with! A lot covered here might be review for some of you, but it is definitely a great introduction to web development. 

If you have any questions, feel free to ask me on the #education channel of Slack!