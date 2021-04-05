Part A: Creating Home Page
Relevant files to work on: index.html, index.css, index.js, common.js, common.css.


Once you have downloaded the zipped folder, you will see a file named "index.html" at the root level of that folder. You must open that file and inside it, you will see some HTML code written. This "index.html" file will be the file for your homepage.

 

You can feel free to modify this HTML code. However, the entire page should look exactly the same as given in the screenshot below:

 



 

Following are some of the very important things to keep in mind:

 

1. You must strictly keep HTML, CSS and JavaScript portions of the code separate from each other in separate files.

 

2. You must refer to the "index.css" file inside the "styles" folder and define all your css inside that file, which corresponds to the styling done for the "index.html" file.

 

3. You must refer to the "index.js" file inside the "scripts" folder and define all your Javascript inside that file, which corresponds to the scripts written for the "index.html" file.

 

4. Unless explicitly mentioned otherwise (for example, at some places, it might be mentioned that a certain button MUST be red in color), you can customize your own CSS for any HTML element you want. However, please keep in mind that the overall appearance of any HTML page must be similar (if not identical) to the outcome of the screen mentioned prior to each part of the assignment. This means that if certain elements are placed towards the top-right part of the screen in the final outcome figure, then they MUST be placed at the top-right corner ONLY. Failing to do so will lead to deduction of marks. Note that there might be multiple ways in which a certain CSS effect can be achieved. So the exact syntax of the CSS code does not matter, but the overall appearance of any given page must be similar to the expected outcome.

 

Let us now begin the step-by-step process of creating the homepage.

 

The homepage will consist of 2 main segments:

 

a) The first part of the homepage consists of the header.

The header consists of the title of your website as "ScriBBler", the subheading "Explore, Imagine, Create", a "Sign Up" button and a "Sign In" button.

(Note that the header will be reused in all the other pages of your website.)

Eventually, the header should look like this:

 



 

You will need to create two modals for the header.

 

Dont forget to keep different div IDs for the different modals, so that they are kept distinct from one another!

 

b) The second part of the homepage consists of a segment which will consist of 2 buttons - "All Posts" and "Create Post".

 



 

 

Let us follow some steps to create the header. Note that all the CSS and JavaScript code corresponding to the header must be kept inside the common.css and common.js files respectively inside relevant folders.

 

1. Inside the header, you need to create:

 

a) The logo with the text "ScriBBler" towards the top-left corner of the screen

Recall how you learnt to use fonts obtained from Google Fonts in your HTML CSS module. You must use the “Montez” font for writing this text.

 

For getting this font, go to Google Fonts, and select the "Montez" font by clicking on the red-colored plus button having tooltip as 'Select this font'. Once selected, you will get a collapsed bar with the label '1 Family Selected'. When you expand the menu bar, you will get to see the external stylesheet reference as:

<link href="https://fonts.googleapis.com/css?family=Montez&display=swap" rel="stylesheet">
Copy the above code and paste it inside the head tags in your HTML page of your home page (index.html file).

 

Once done, add the CSS on your HTML element as:

font-family: 'Montez', cursive; 
 

b) A subheading with the text "Explore, Imagine, Create" just below the logo

Note that the size of this sub-heading should be less than the size of the logo "ScriBBler". Use the  font 'Ubuntu Mono' from Google Fonts for the sub-heading.

 

c) A blue-colored "Sign In" button on the top-right side of the screen

You can use any font of your choice for this. Don't forget to correctly position the text to center inside the button.

 

d) A blue-colored "Sign Up" button on the top-right side of the screen

You can use any font of your choice for this. Don't forget to correctly position the text to center inside the button.


2. On clicking the "Sign Up" button, a modal should appear on the screen. A modal is basically a simple pop-up dialog box which can be used to display some information when a button is clicked. So instead of opening a separate sign-up page, you can open a modal which will be contained inside the existing screen.

 

You must find on the Internet different ways to create a simple modal.  You can use this link to find a simple modal's code. However, the code will just give you an idea on how to create a modal and cannot be used as it is. You will need to modify the code in order for it to look like the one shown below. Thus, the modal corresponding to the "Sign Up" button must look like this:

 



 

a) The modal must be displayed in the center of the page. The title of the modal should be "Get Started" and you can use any font you wish. You should also display a tiny cross button in the top-right corner, which when clicked, will close this modal. You can use Font-Awesome icon named 'times' for this purpose.

 

b) The modal must consist of 4 input boxes - one each for "Name", "Username", "Password" and "Confirm Password". Note that the input type of each of these should be - text, text, password, and password respectively. You can use any font you like to display these texts. Just remember to have consistency in displaying all the texts with the same type and size.

 

Note that when nothing is typed into the input boxes, they should display a placeholder with the text "Enter your name", "Enter your username", "Enter your password" & "Re-enter your password" for the Name, Username, Password, and Confirm Password fields respectively. 

 

c) Below these input fields, you must create a green-colored "Sign Up" button. Note that you must make sure that the above 4 input fields are mandatorily filled in by the user, without which he/she cannot proceed with clicking the "Sign Up" button. For example, when a user tries to proceed without filling all the fields, a message must be displayed with the text 'Please fill out this field.', as shown in the screenshot given below:

 



 

 

 

Note that you do not need to define any specific action on clicking the Sign Up button.

 

3. On clicking the "Sign In" button, a modal should appear on screen. The modal corresponding to the "Sign In" button must look like this:

 



 

a) The title of the modal should be "Welcome Back!". You should also display a tiny cross button on the top-right corner, which when clicked, will close this modal. You can use Font-Awesome icon named 'times' for this purpose.

 

b) The modal must consist of 2 input boxes - one for "Username" and the other for "Password" having the input type as text and password respectively.

 

Note that when nothing is typed into the input boxes, they should display a placeholder with the text "Enter your username" and "Enter your password" for the Name and Password fields respectively. 

 

c) Below these input fields, you must create a green-colored "Sign In" button. Note that you must make sure that the above 2 input fields are mandatorily filled in by the user, without which he/she cannot proceed with clicking the "Sign In" button. For example, when a user tries to proceed without filling all the fields, a message must be displayed with the text 'Please fill out this field.', as shown in the screenshot given below:

 



 

 

d) Below the "Sign In" button, you must display the text "Not a member? Sign Up". The "Not a member?" portion of the text should be in black color, whereas the "Sign Up" portion of the text should be a hyperlink, which when clicked, should hide the sign in modal and display the sign-up modal which you have already created earlier. Thus, when you click on the hyperlink 'Sign up' in the sign in modal, you will get to see the sign up modal.

 

Now let us follow some steps to create the two buttons placed in center of the home page.

 



 

 

1. Creating two buttons in the centre of the page:

a) Create a yellow/orange colored button with the text "All Posts" in the centre (horizontally as well as vertically) of the page. The text inside this button should be in center.

 

b) Create another yellow/orange colored button with the text "Create Post" in the centre (horizontally as well as vertically) of the page. It should be placed towards the right side of  “All Posts” button. The text inside this button should be in center.

 

2. On clicking the "All Posts" button, the user should be taken to another page, which lists all the blog posts created. The code for this should be written inside a file named bloglist.html, which should be placed inside relevant folder. (For now, this can be an empty page, which you will create in the next part of your project.)

 

3. On clicking the "Create Post" button, it should display a modal like this:

 



 

a) The title of the modal should be "Pen Your Post".

b) There should be a label with the text 'Title' and below that there should be an input box. The placeholder should be 'Enter title of your post'.

c) Below Title, there should be a label with the text 'Contents' and below the label, there should be a large text box for writing the contents of the post. The placeholder should be displayed with text 'Enter the contents of your post'.

d) Below both the input fields, create a green-colored "Create" button at the centre which at the present moment, would not do anything when you click on it. (Later on, you can write an API request for posting a new blog article but for now, you don't need to worry about it.) 

 

e) Create a tiny cross button at the top-right corner of the modal, which when clicked, will close the modal. You can use Font-Awesome icon named 'times' for this purpose.