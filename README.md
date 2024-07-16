# Exercise 2 - HTML Page

## Objectives
Choose a simple website and code the HTML for its homepage. You will use semantic HTML5 structural elements to create different groups of content. The content will include a variety of HTML content elements. 

## Instructions
Remember to:
* Regularly save your files and check out what your web page looks like in a web browser.
* Make regular commits.
### Step 1: Read through the example
An example of this exercise is provided (see folder called "example-exercise"), the example is the homepage of https://upnitlodge.ca/. Check out the website's homepage in your browser and then read through the HTML in the index.html file in VS Code.
### Step 2: Choose a webpage
Browse the internet to find a simple brochure website. A brochure website is a website that includes approx 5 pages (For ex: Homepage, About, Services, Locations and Contact). It's like an online brochure. It explains what the business offers and provides a way to get in touch. A brochure website does not include e-commerce, membership log in, or any other type of advanced functionality. I recommend you find a website whose homepage is no more complex than the homepage of upnitlodge.ca. Don't choose something too complicated but make usre it contains a reasonable amount of text.
### Step 3: Create the webpage
* Use GitHub Desktop to clone your remote exercise repository onto your local machine.
* In VS Code, add a file called index.html to your local repository. 
* Open index.html and add the HTML skeleton code provided by VSCode.
* Change the page title in the head element to something appropriate for the webpage that you chose.
* Add a comment in the head element that includes the URL of the webpage that you chose. Example: `<!-- https://upnitlodge.ca -->`
### Step 4: Add the structural elements
Code the structural organization of the content. You don't need to include all the structural elements but you should use at least 6 of them.
1. Body 
2. Header
3. Nav
4. Main
5. Section
6. Article
7. Aside
8. Footer
### Step 5: Add the content
1. Copy and paste the content from your chosen website into your webpage.
2. Save the images in an images folder. Don't bother with background images and decorative images, only save editorial images. In the example, I didn't save the image behind the h1, nor the icons in the footer.
3. Use the elements we have learnt about so far to organize the content. Look them up in HTMLreference.io for details. Feel free to experiemnt using more HTMl elements if you like:
    - Headings (H1 to H6)
    - Paragraph
    - Strong
    - Bold
    - Italic
    - Emphasis
    - Special Characters
    - Hyperlinks (including email links and same-page links)
    - Unordered lists
    - Ordered lists
    - Description lists
    - Image
    - Div and span (you shouldn't need these elements as they carry no semantic meaning and are only used to define areas to which you want to apply styling)

### Step 6: Format and add comments 
* Make sure that you have the Prettier VS Code extension installed. On the index page, right-click > Format document to apply proper formatting. Repeat for the about page and the stylesheet.
* Optional: Add a few comments to explain your code, to point out any elements you have used that we haven't learnt about in class, to ask questions, or to highlight anything of interest. For ex: `<!-- I used the mark HTML element to highlight the word milk -->`

### Step 7: Learn to troubleshoot errors
1. Learn to use the HTMLHint extension:
    * Make sure that you have the HTMLHint VS Code extension installed. The extension will automatically underline coding errors with a squiggly line. If the extension has detected errors, a number will appear next to a warning icon in the status bar at the bottom of the VS Code window (see VS Code Reference Guide for details). Click on the warning icon in the status bar to open the Problems Panel. 
    * Try typing an error in your HTML file so that you can test the HTMLHint extension and see how it works.
2. A more robust way to validate your HTML is using the official W3C Markup Validator: 
    * Go to https://validator.w3.org/#validate_by_upload. Choose your *index.html* file in your local repository and click the Check button. If there are no errors then you should see a green message that says “Document checking completed. No errors or warnings to show.” If you get an error message then troubleshoot your work, save and re-check it until you get the green message.
    * **Take a screenshot of your HTML validation results, you will need to submit it in Brightspace.**

You have now completed your exercise but you still need to push your edits to GitHub and submit it in Brightspace. Make sure to follow the instructions in the How to Complete Your Exercises Guide. You will need to submit the screenshot of your HTML validation results.