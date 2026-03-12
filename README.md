TECH GROWTH JOURNEY

OVERVIEW

Two weeks ago, I shared a completed project that demonstrated a multi-page website structure and styling.
I have now decided to restart and document step-by-step to better showcase my learning progression and technical growth.
This repository will serve as a living project where I continuously improve and expand the website as I learn new concepts.

CURRENT VERSION (VERSION 1)

This version includes:
1. Basic multi-page HTML structure
2. Internal navigations between multiple pages
3. Eternal links to websites like Facebook, Instagram, TikTok, Amazon, and Twitter
4. Headings and content sections
5. Ordered and unordered lists
6. Description lists

GOAL

To progressively enhance this project by adding:
1. Tables
2. Forms
3. CSS styling
4. Responsive layout
5. JavaScript interactivity

Each update will reflect my learning journey and technical improvement.


VERSION 2

Added Table and Form

In this update, I added a table and a form to my project. I created them using HTML and connected them to other pages in the project. This helped improve my understanding of linking pages together.
For the table, I used rowspan to make the layout organized and readable. In the form, adding elements like buttons, checkboxes, and 0ther input types was challenging, but I practiced and learned how to implement them confidently.
Next is to add media before going on to CSS styling and more interactive feature with JavaScript to enhance the user experience and functionality of the project.


VERSION 3

Added Media

I added a few mwdia elements (image, audio, and video) to my project. 
Next, I will be working on CSS styling to enhance the design and layout.


VERSION 4

STYLED WITH CSS

While styling the form section of my HTML and CSS project, I ran into a small issue that taught me an important lesson about form structure.

At first, I wrote my checkboxes and radio buttons separately from their labels. My code looked something like this:

<input type="checkbox"><label>English</label>

And for gender:

<label>Male</label>
<input type="radio" name="gender">

But when I previewed the form in the browser, the checkboxes and radio buttons were not properly aligned with their text. At first I thought it was a CSS issue, but after reviewing my HTML structure, I realized the problem was how the labels and inputs were written.

I corrected it by placing the input inside the label so they act as one unit:

<label><input type="checkbox"> English</label>

<label><input type="radio" name="gender"> Male</label>

After restructuring the HTML this way, the inputs aligned perfectly with the text and usability improved because users can click on the text to select the option.

This experience reminded me that CSS cannot always fix layout problems if the HTML structure is not written properly. Sometimes the best solution is to go back and improve the HTML itself.

Each small challenge like this helps me understand web development better as I continue building projects and improving my skills.

LIVE DEMO

https://loveth-mary.github.io/tech-growth-journey/
