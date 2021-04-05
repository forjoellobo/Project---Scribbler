<div class="component-list fixed-main-container"><h1 class="segment-heading-text bold-font">Part A: Creating Home Page</h1><div class="component-list-items"><div class="text-component-item" id="component-c698"><div class="text-container"><p style="text-align: justify; margin-bottom: 0px;">Relevant files to work on: <strong><em>index.html</em>, <em>index.css</em>, <em>index.js</em>, <em>common.js</em>, <em>common.css</em></strong>.</p><p style="text-align: justify;"><br>Once you have downloaded the zipped folder, you will see a file named "<em>index.html</em>" at the root level of that folder. You must open that file and inside it, you will see some HTML code written. This "index.html" file will be the file for&nbsp;your homepage.</p><p style="text-align: justify;">&nbsp;</p><p style="text-align: justify;">You can feel free to modify this HTML code. However, the entire page should look exactly the same as given in the screenshot below:</p><p style="text-align: justify;">&nbsp;</p><p style="text-align: center;"><img class="image-editor" data-width="1364" data-height="654" height="287.683284457478" width="600" src="https://images.upgrad.com/fac4b9f3-ce90-41bd-97e4-bd7fd3a1f295-Home Page.png"></p><p style="text-align: justify;">&nbsp;</p><p style="text-align: justify;">Following are some of the very important things to keep in mind:</p><p style="text-align: justify;">&nbsp;</p><p style="text-align: justify;">1. You must strictly keep HTML, CSS and JavaScript portions of the code separate from each other in separate files.</p><p style="text-align: justify;">&nbsp;</p><p style="text-align: justify;">2. You must refer to the "<em>index.css</em>" file inside the "<em>styles</em>" folder and define all your css inside that file, which corresponds to the styling done for the "<em>index.html</em>" file.</p><p style="text-align: justify;">&nbsp;</p><p style="text-align: justify;">3. You must refer to the "<em>index.js</em>" file inside the "<i>scripts</i>" folder and define all your Javascript inside that file, which corresponds to the scripts written for the "<em>index.html</em>" file.</p><p style="text-align: justify;">&nbsp;</p><p style="text-align: justify;">4. Unless explicitly mentioned otherwise (for example, at some places, it might be mentioned that a certain button MUST be red in color), you can customize your own CSS for any HTML element you want. However, please keep in mind that the overall appearance of any HTML page must be similar (if not identical) to the outcome of the screen mentioned prior to&nbsp;each part of the assignment. This means that if certain elements are placed towards the top-right part&nbsp;of the screen in the final outcome figure, then they MUST be placed at the top-right corner ONLY.&nbsp;Failing to do so will lead to deduction of marks. Note that there might be multiple ways in which a certain CSS effect can be achieved. So the exact syntax of the CSS code does not matter, but the overall appearance of any given page must be similar to the expected outcome.</p><p style="text-align: justify;">&nbsp;</p><p style="text-align: justify;">Let us now begin the step-by-step process of creating the homepage.</p><p style="text-align: justify;">&nbsp;</p><p style="text-align: justify;">The homepage will consist of 2 main segments:</p><p style="text-align: justify;">&nbsp;</p><p style="text-align: justify; margin-bottom: 0px;">a) The first part of the homepage consists of the&nbsp;<strong>header</strong>.</p><p style="text-align: justify; margin-bottom: 0px;">The header consists of the title of your website as<strong>&nbsp;"ScriBBler"</strong>, the <strong>subheading "Explore, Imagine, Create"</strong>, a <strong>"Sign Up" </strong>button&nbsp;and a&nbsp;<strong>"Sign In"</strong> button.</p><p style="text-align: justify;">(Note that the header will be reused&nbsp;in all the other pages of your website.)</p><p style="text-align: justify;">Eventually, the header should look like this:</p><p>&nbsp;</p><p style="text-align: center;"><img class="image-editor" data-width="1363" data-height="82" height="36.09684519442406" width="600" src="https://images.upgrad.com/09c1f6fc-6d2b-417c-8184-c6b46460b8f4-Header.png"></p><p style="text-align: center;">&nbsp;</p><p style="text-align: justify; margin-bottom: 0px;">You will need to create two&nbsp;<strong>modals </strong>for the header.</p><p style="text-align: justify;">&nbsp;</p><p style="text-align: justify; margin-bottom: 0px;"><strong style="font-size: 1em;">Dont</strong><strong style="font-size: 1em;"> forget to keep different <em>div </em>IDs&nbsp;for the&nbsp;different </strong><strong style="font-size: 1em;">modals</strong><strong style="font-size: 1em;">,</strong><strong style="font-size: 1em;"> so that they are kept distinct from one another!</strong></p><p style="text-align: justify;">&nbsp;</p><p style="text-align: justify; margin-bottom: 0px;">b) The second part of the homepage consists of a segment which will consist of 2 buttons -&nbsp;<strong>"All Posts"</strong> and&nbsp;<strong>"Create Post"</strong>.</p><p>&nbsp;</p><p style="text-align: center;"><img class="image-editor" data-width="1359" data-height="175" height="77.2626931567329" width="600" src="https://images.upgrad.com/fa762482-68fa-4a62-a0db-5300c07fa4fd-Post Buttons.png"></p><p style="text-align: justify;">&nbsp;</p><p style="text-align: justify;">&nbsp;</p><p style="text-align: justify; margin-bottom: 0px;">Let us follow some steps to create the header. <strong>Note that all the CSS and JavaScript code corresponding to the header must be kept inside the <em>common.css </em>and <em>common.js </em>files respectively inside relevant folders.</strong></p><p style="text-align: justify;">&nbsp;</p><p style="text-align: justify; margin-bottom: 0px;"><strong>1.</strong> Inside the header,&nbsp;you need to create:</p><p style="text-align: justify;">&nbsp;</p><p style="text-align: justify; margin-bottom: 0px;"><strong>a) The logo with the text "ScriBBler" towards the top-left corner of the screen</strong></p><p style="text-align: justify;">Recall how you learnt to use fonts obtained from Google Fonts in your HTML CSS module. You must use the “Montez” font for writing this text.</p><p style="text-align: justify;">&nbsp;</p><p style="text-align: justify;">For getting this font, go to <a target="_blank" href="https://fonts.google.com/">Google Fonts</a>, and select the "Montez" font by clicking on the red-colored plus button having tooltip as 'Select this font'. Once selected, you will get a collapsed bar with the label '1 Family Selected'. When you expand the menu bar, you will get to see the external stylesheet reference as:</p><div id="code-snippet-cke_3292" data-lang="html" class="code-snippet-container"><div contenteditable="false" class="code"><pre style="margin: 0; line-height: 125%"><span></span>&lt;<span style="color: #007700">link</span> <span style="color: #0000CC">href</span><span style="color: #333333">=</span><span style="background-color: #fff0f0">"https://fonts.googleapis.com/css?family=Montez&amp;display=swap"</span> <span style="color: #0000CC">rel</span><span style="color: #333333">=</span><span style="background-color: #fff0f0">"stylesheet"</span>&gt;
</pre></div></div><p style="text-align: justify;">Copy the above code and paste it inside the <em>head</em> tags in your HTML page of your home page (<em>index.html</em> file).</p><p style="text-align: justify;">&nbsp;</p><p style="text-align: justify;">Once done, add the CSS on your HTML element as:</p><div id="code-snippet-cke_3290" data-lang="css" class="code-snippet-container"><div contenteditable="false" class="code"><pre style="margin: 0; line-height: 125%"><span></span><span style="color: #007700">font-family</span><span style="color: #333333">:</span> <span style="background-color: #fff0f0">'Montez'</span><span style="color: #333333">,</span> <span style="color: #007700">cursive</span><span style="color: #333333">;</span> 
</pre></div></div><p>&nbsp;</p><p style="text-align: justify; margin-bottom: 0px;"><strong>b) A subheading with the text "<em>Explore, Imagine, Create</em>" just below the logo</strong></p><p style="text-align: justify;">Note that the size of this sub-heading should be less than the size of the logo "ScriBBler".&nbsp;Use the&nbsp; font 'Ubuntu&nbsp;Mono' from Google Fonts for the sub-heading.</p><p style="text-align: justify;">&nbsp;</p><p style="text-align: justify; margin-bottom: 0px;"><strong>c) A blue-colored "Sign In" button on the top-right side of the screen</strong></p><p style="text-align: justify;">You can use any font of your choice for this. Don't forget to correctly position the text to center inside the button.</p><p style="text-align: justify;">&nbsp;</p><p style="text-align: justify; margin-bottom: 0px;"><strong>d) A blue-colored "Sign Up" button on the top-right side of the screen</strong></p><p style="text-align: justify;">You can use any font of your choice for this. Don't forget to correctly position the text to center inside the button.</p><p style="text-align: justify; margin-bottom: 0px;"><br><strong>2.</strong> On clicking the <strong>"Sign Up"</strong> button, a modal<strong> </strong>should appear on the screen.&nbsp;A modal is basically a simple pop-up dialog box which can be used to display some information when a button is clicked. So instead of opening a separate sign-up page, you can open a modal which will be contained inside the existing screen.</p><p style="text-align: justify;">&nbsp;</p><p style="text-align: justify;">You must find on the Internet different ways to create a simple modal.&nbsp; You can use <a target="_blank" href="https://www.w3schools.com/howto/howto_css_modals.asp">this</a> link to find a simple modal's code. However, the code will just give you an idea on how to create a modal and cannot be used as it is. You will need to modify the code in order for it to look like the one shown below. Thus, the modal corresponding to the "Sign Up" button must look like this:</p><p>&nbsp;</p><p style="text-align: center;"><img class="image-editor" data-width="1366" data-height="652" height="286.3836017569546" width="600" src="https://images.upgrad.com/97d2aa1e-c4dd-4b88-b326-c0523ba91237-Sign Up Modal.png"></p><p style="text-align: center;">&nbsp;</p><p style="text-align: justify;">a) The modal must be displayed in the center of the page. The title of the modal should be "Get Started" and you can use any font you wish. You should also display a tiny cross button in the top-right corner, which when clicked, will close this modal. You can use <a target="_blank" href="https://fontawesome.com/v4.7.0/icons/">Font-Awesome</a> icon named 'times' for this purpose.</p><p style="text-align: justify;">&nbsp;</p><p style="text-align: justify;">b) The&nbsp;modal must consist of 4 input boxes - one each for "Name", "Username", "Password" and "Confirm Password". Note that the input type of each of these should be - text, text, password, and password respectively. You can use any font you like to display these texts. Just remember to have consistency in displaying all the texts with the same type and size.</p><p style="text-align: justify;">&nbsp;</p><p style="text-align: justify;">Note that when nothing is typed into the input boxes, they should display a placeholder with the text "Enter your name", "Enter your username", "Enter your password" &amp; "Re-enter your password" for the Name, Username, Password, and Confirm Password fields respectively.&nbsp;</p><p style="text-align: justify;">&nbsp;</p><p style="text-align: justify;">c) Below these input fields, you must create a green-colored "Sign Up" button. Note that you must make sure that the above 4 input fields are mandatorily filled in by the user, without which he/she cannot proceed with clicking the "Sign Up" button. For example, when a user tries to proceed without filling all the fields, a message must be displayed with the text 'Please fill out this field.', as shown in the screenshot given below:</p><p>&nbsp;</p><p style="text-align: center;"><img class="image-editor" data-width="1357" data-height="649" height="286.95652173913044" width="600" src="https://images.upgrad.com/b5da8e70-28db-4cdc-8107-7bb9681fd442-Required Fields in Modals.png"></p><p style="text-align: center;">&nbsp;</p><p>&nbsp;</p><p>&nbsp;</p><p style="text-align: justify;"><meta charset="utf-8"></p><p dir="ltr" style="text-align: justify;">Note that you do not need to define any specific action on clicking the <em>Sign Up</em> button.</p><p style="text-align: justify;">&nbsp;</p><p style="text-align: justify; margin-bottom: 0px;"><strong>3.</strong> On clicking the "Sign In" button, a modal should appear on screen. The modal corresponding to the "Sign In" button must look like this:</p><p>&nbsp;</p><p style="text-align: center;"><img class="image-editor" data-width="1364" data-height="651" height="286.3636363636364" width="600" src="https://images.upgrad.com/519f26d1-d32f-4a82-a9a3-a3cfd99987a7-Sign In Modal.png"></p><p style="text-align: center;">&nbsp;</p><p style="text-align: justify;">a) The title of the modal should be "Welcome Back!". You should also display a tiny cross button on the top-right corner, which when clicked, will close this modal.&nbsp;You can use <a target="_blank" href="https://fontawesome.com/v4.7.0/icons/">Font-Awesome</a> icon named 'times' for this purpose.</p><p style="text-align: justify;">&nbsp;</p><p style="text-align: justify;">b) The&nbsp;modal must consist of 2 input boxes - one&nbsp;for "Username" and the other for "Password" having the input type as text and password respectively.</p><p style="text-align: justify;">&nbsp;</p><p style="text-align: justify;">Note that when nothing is typed into the input boxes, they should display a placeholder with the text "Enter your username" and "Enter your password" for the Name and Password fields respectively.&nbsp;</p><p style="text-align: justify;">&nbsp;</p><p style="text-align: justify;">c) Below these input fields, you must create a green-colored "Sign In" button. Note that you must make sure that the above 2&nbsp;input fields are mandatorily filled in by the user, without which he/she cannot proceed with clicking the "Sign In" button. For example, when a user tries to proceed without filling all the fields, a message must be displayed with the text 'Please fill out this field.', as shown in the screenshot given below:</p><p style="text-align: justify;">&nbsp;</p><p style="text-align: center;"><img class="image-editor" data-width="1358" data-height="651" height="287.62886597938143" width="600" src="https://images.upgrad.com/3b6b49f0-2774-4091-89d3-87a70403a8fa-Required Fields in Modals 2.png"></p><p style="text-align: center;">&nbsp;</p><p>&nbsp;</p><p style="text-align: justify;">d) Below the "Sign In" button, you must display the text "Not a member? Sign Up". The "Not a member?" portion of the text should be in black color, whereas the "Sign Up" portion of the text should be a hyperlink, which when clicked, <meta charset="utf-8">should hide the <em>sign in modal </em>and display the <em>sign-up modal </em>which you have already created earlier. Thus, when you click on the hyperlink 'Sign up' in the <em>sign in</em> modal, you will get to see the <em>sign up</em> modal.</p><p style="text-align: justify;">&nbsp;</p><p style="text-align: justify;">Now let us follow some steps to create the two buttons placed in center of the home page.</p><p>&nbsp;</p><p style="text-align: center;"><img class="image-editor" data-width="1359" data-height="175" height="77.2626931567329" width="600" src="https://images.upgrad.com/c8f33228-0365-47c0-a97c-37ab4967b5cb-Post Buttons.png"></p><p style="text-align: justify;">&nbsp;</p><p>&nbsp;</p><p style="text-align: justify;">1. Creating two buttons in the centre of the page:</p><p style="text-align: justify; margin-bottom: 0px;">a) Create a yellow/orange colored button with the text&nbsp;"<strong>All Posts</strong>" in the centre (horizontally as well as vertically) of the page. The text inside this&nbsp;button&nbsp;should be in center.</p><p style="text-align: justify;">&nbsp;</p><p style="text-align: justify; margin-bottom: 0px;">b) Create another yellow/orange colored button with the text&nbsp;<strong>"Create Post" </strong>in the centre (horizontally as well as vertically) of the page. It should be placed towards the right side of&nbsp; “All Posts” button. The text inside this button should&nbsp;be in center.</p><p style="text-align: justify;">&nbsp;</p><p style="text-align: justify; margin-bottom: 0px;">2. On clicking the <strong>"All Posts"</strong> button, the user should be taken to another page, which lists all the blog posts created.&nbsp;The code for this should be written inside a file named <em>bloglist.html</em>, which should be placed inside relevant folder. (For now, this can be an empty page, which you will&nbsp;create&nbsp;in the next part of your project.)</p><p style="text-align: justify;">&nbsp;</p><p style="text-align: justify; margin-bottom: 0px;">3. On clicking the "<strong>Create Post</strong>" button, it should display a modal like this:</p><p>&nbsp;</p><p style="text-align: center;"><img class="image-editor" data-width="1364" data-height="651" height="286.3636363636364" width="600" src="https://images.upgrad.com/cbe20198-30b7-41c1-bbb1-60d8f8cda4b4-Create Post Modal.png"></p><p style="text-align: center;">&nbsp;</p><p style="text-align: justify;">a) The title of the modal should be "Pen Your Post".</p><p style="text-align: justify;">b) There should be a label with the text 'Title' and below that there should be an input box. The placeholder should be 'Enter title of your post'.</p><p style="text-align: justify;">c) Below Title, there should be a label with the text 'Contents' and below the label, there should be a large text box for writing the contents of the post. The placeholder should be displayed with text 'Enter the contents of your post'.</p><p style="text-align: justify;">d) Below both the input fields, create a green-colored "Create" button at the centre which at the present moment, would not do anything when you click on it. (Later on, you can write an API request for posting a new blog article&nbsp;but for now, you don't need to worry about it.)&nbsp;</p><p>&nbsp;</p><p style="text-align: justify;">e) Create a tiny cross button at the top-right corner of the modal, which when clicked, will close the modal.&nbsp;You can use <a target="_blank" href="https://fontawesome.com/v4.7.0/icons/">Font-Awesome</a> icon named 'times' for this purpose.</p></div></div></div></div>

<div class="component-list fixed-main-container"><h1 class="segment-heading-text bold-font">Part B: Creating PostsList Page</h1><div class="component-list-items"><script class="fade" id="video-feedback-view" type="text/template"><div class="modal" id="video-feedback" tabindex="-1" role="dialog"><div class="modal-dialog"><div class="modal-content"><div class="modal-header"> <div class="header-content"><div class="sub-head"></div></div><button class="close" type="button" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button></div><div class="modal-body"><div class="video-placeholder"></div></div></div></div></div></script><script class="fade" id="text-feedback-view" type="text/template"><div class="modal" id="text-feedback" tabindex="-1" role="dialog"><div class="modal-dialog"><div class="modal-content"><div class="modal-header"><button class="close" type="button" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button></div><div class="modal-body"><div class="tab-holder"><div class="tab-switch"><div class="single-view-tab selected">Single view</div><div class="compare-view-tab">Compare view</div></div></div><div class="title-holder"><div class="title-sample-solution"><div class="title-text">Sample solution</div><div class="copy-solution" data-toggle="tooltip" data-placement="top" title="Copy solution to clipboard"><i class="material-icons copy-icon">file_copy</i><span class="copy-solution-text">Copy</span></div></div><div class="title-your-solution hide">Your submission</div></div><div class="text-placeholder"><div class="sample-solution-editor"></div><div class="your-solution-editor hide"></div></div></div></div></div></div></script><div class="text-component-item" id="component-c705"><div class="text-container"><p style="text-align: justify;">In this section, we would be creating a page called "postslist.html" which would display the list of all the&nbsp;posts.</p><p style="text-align: justify;"><meta charset="utf-8"></p><p style="text-align: justify;">&nbsp;</p><p dir="ltr" style="text-align: justify; margin-bottom: 0px;">Relevant files to work on: <strong>postslist.html, postslist.css, postslist.js</strong>.</p><p style="text-align: justify;">&nbsp;</p><p dir="ltr" style="text-align: justify;">Recall that in the previous section, you created an "All Posts" button on the centre of the screen which when clicked, would redirect to a "postslist.html" page. We would be designing this page (“postslist.html”) in this section. The final outcome of creating this page would look like this:</p><p>&nbsp;</p><p dir="ltr" style="text-align: center;"><img class="image-editor" data-width="1366" data-height="656" height="288.14055636896046" width="600" src="https://images.upgrad.com/19d17995-c2cd-48e9-8782-c2113b78551f-PostsList Page.png"></p><p dir="ltr" style="text-align: justify;">&nbsp;</p><p dir="ltr" style="text-align: justify; margin-bottom: 0px;"><strong><meta charset="utf-8"></strong>Some very important things to keep in mind:</p><p dir="ltr" style="text-align: justify;">1. You must strictly keep HTML, CSS and JavaScript portion of the code separate from each other in separate files.</p><p dir="ltr" style="text-align: justify;">&nbsp;</p><p dir="ltr" style="text-align: justify;">2. You must refer to the "postslist.css" file inside the "styles" folder and define all your css inside that file corresponding to the "postslist.html" file.</p><p dir="ltr" style="text-align: justify;">&nbsp;</p><p dir="ltr" style="text-align: justify;">3. You must refer to the "postslist.js" file inside the "scripts" folder and define all your JavaScript code inside that file corresponding to the "postslist.html" file.</p><p dir="ltr" style="text-align: justify;">&nbsp;</p><p dir="ltr" style="text-align: justify;">4. Unless explicitly mentioned otherwise (for example, at some places, it might be mentioned that a certain button MUST be red in color), you can customize your own CSS for any HTML element you want. However, please keep in mind that the overall appearance of any HTML page must be similar (if not identical) to the outcome of the screen mentioned prior to&nbsp;each part of the assignment. This means that if certain elements are placed towards the top-right part&nbsp;of the screen in the final outcome figure, then they MUST be placed at the top-right corner ONLY.&nbsp;Failing to do so will lead to deduction of marks. Note that there might be multiple ways in which a certain CSS effect can be achieved. So the exact syntax of the CSS code does not matter, but the overall appearance of any given page must be similar to the expected outcome.</p><p style="text-align: justify;">&nbsp;</p><p dir="ltr" style="text-align: justify;">Let us move step-by-step to create this page:</p><p dir="ltr" style="text-align: justify;">&nbsp;</p><p dir="ltr" style="text-align: justify;">1. First of all, color&nbsp;the background of the page with the color code <em>#ffeedd</em>.&nbsp;</p><p dir="ltr" style="text-align: justify;">&nbsp;</p><p dir="ltr" style="text-align: justify;">2. Include the code of the header from the 'index.html' page (home page created in the previous segment) inside the 'postslist.html' page.</p><p dir="ltr" style="text-align: justify;">Basically, the header part of the page should be exactly identical to the header portion which you created in the last segment.</p><p>&nbsp;</p><p style="text-align: center;"><img class="image-editor" data-width="1365" data-height="89" height="39.120879120879124" width="600" src="https://images.upgrad.com/725adda2-dd37-4996-bde0-ef0e339be964-Header - PostsList Page.png"></p><p style="text-align: justify;">&nbsp;</p><p dir="ltr" style="text-align: justify;">3. Below the header, you need to create a segment which consists of 5 identical posts and place them next to each other in pairs.</p><p dir="ltr" style="text-align: justify;">&nbsp;</p><p dir="ltr" style="text-align: justify;"><u style="margin-bottom: 0px;"><strong>IMPORTANT:</strong></u></p><p dir="ltr" style="text-align: justify; margin-bottom: 0px;"><strong>The HTML code for the list of posts in this page has been given to you. You can feel free to add or delete or modify this code. However, you do need to write the proper CSS and JavaScript code corresponding to these posts and all other HTML/CSS/JavaScript code needed to be written in order to produce the outcome which looks like the screenshots given in this page.&nbsp;</strong></p><p dir="ltr" style="text-align: justify;">&nbsp;</p><p dir="ltr" style="text-align: center;"><img class="image-editor" data-width="1363" data-height="541" height="238.15113719735876" width="600" src="https://images.upgrad.com/bd2adc39-62a9-4b84-9182-929bf23714ca-Main Body - PostsList Page.png"></p><p dir="ltr" style="text-align: center;">&nbsp;</p><p dir="ltr" style="text-align: justify;">a) Each post is displayed in the form of a card, as shown in the screenshot given below:</p><p dir="ltr" style="text-align: justify;">&nbsp;</p><p dir="ltr" style="text-align: center;"><b><img class="image-editor" data-width="576" data-height="169" height="169" width="576" src="https://images.upgrad.com/fd9b4818-450d-46de-b8e1-9a77e54212a4-Post.png"></b></p><p dir="ltr" style="text-align: justify;">&nbsp;</p><p dir="ltr" style="text-align: justify;">b) When a user hovers on the post (displayed in the form of card), box shadow appears, as shown in the screenshot given below where the first post is hovered upon:</p><p>&nbsp;</p><p dir="ltr" style="text-align: center;"><img class="image-editor" data-width="1231" data-height="540" height="263.20064987814783" width="600" src="https://images.upgrad.com/e253fdbe-e956-4247-85f3-869936d3cb1d-Hover on Post.png"></p><p dir="ltr" style="text-align: justify;">&nbsp;</p><p dir="ltr" style="text-align: justify;">c) Each&nbsp;post will display the username of the user towards the left.</p><p dir="ltr" style="text-align: justify;">&nbsp;</p><p dir="ltr" style="text-align: justify;">d) Towards the right of the username, you need to display the heading of the post. Below the heading of the post, you need to display the intial text of the post upto three lines only. Remember&nbsp;that you must not display the entire text of the post on this page itself.&nbsp;</p><p dir="ltr" style="text-align: justify;">&nbsp;</p><p dir="ltr" style="text-align: justify;">e) You need to add a "trash" icon towards the top-right of each post as shown in the screenshot given above. You can use the FontAwesome icon 'trash' for this purpose.&nbsp;</p><p dir="ltr" style="text-align: justify;">When a user hovers on the delete button, the pointer should change to cursor, as shown in the screenshot given below:</p><p>&nbsp;</p><p dir="ltr" style="text-align: center;"><img class="image-editor" data-width="581" data-height="172" height="172" width="581" src="https://images.upgrad.com/6890ed2c-b3d9-4c52-9254-a1834fe948ae-Delete Post Icon Click.png"></p><p dir="ltr" style="text-align: justify;">&nbsp;</p><p dir="ltr" style="text-align: justify;"><meta charset="utf-8"></p><p dir="ltr" style="text-align: justify;">On clicking the trash icon, a modal should be displayed&nbsp;like this:</p><p dir="ltr" style="text-align: justify;">&nbsp;</p><p dir="ltr" style="text-align: center;"><img class="image-editor" data-width="1361" data-height="653" height="287.8765613519471" width="600" src="https://images.upgrad.com/43990288-b76b-45ee-b5c5-c64b3549ddd1-Delete Post Modal.png"></p><p dir="ltr" style="text-align: center;">&nbsp;</p><p style="text-align: justify;">This modal would consist of a green-coloured "Yes" button and a red-coloured "No" button. On clicking the "No" button, the modal should disappear and the <em>postslist</em> page should appear again as it is without being refreshed. On clicking the "Yes" button, the post must be deleted from the page and other posts should be rearranged.For example, assume that the page consists of five posts, as shown in the screenshot given below:</p><p style="text-align: justify;">&nbsp;</p><p style="text-align: center;"><img class="image-editor" data-width="1366" data-height="656" height="288.14055636896046" width="600" src="https://images.upgrad.com/21642ec4-499d-4d96-a084-85f13ba3466a-PostsList Page.png"></p><p style="text-align: justify;">&nbsp;</p><p dir="ltr" style="text-align: justify;"><meta charset="utf-8"></p><p style="text-align: justify;">If the first post from the following list of posts is deleted from the list of posts as shown above, then there would remain only four posts on the page, as shown in the screenshot given below:</p><p style="text-align: justify;">&nbsp;</p><p style="text-align: center;"><img class="image-editor" data-width="1363" data-height="653" height="287.45414526779166" width="600" src="https://images.upgrad.com/99263b8f-eb95-44fb-9cd3-e651c744a3bb-Post Deleted From Page.png"></p><p style="text-align: justify;">&nbsp;</p><p dir="ltr" style="text-align: justify;">f) You should display only two of posts in a row. This means that whatever screen size we reduce our screen to, there should be exactly two posts in each row (see screenshot given below). They should adjust their height/width automatically when the screen is resized. In case, there is odd number of posts, then the post in the last row must be displayed in center, as shown in the screenshot given below:</p><p>&nbsp;</p><p style="text-align: center;"><img class="image-editor" data-width="1363" data-height="541" height="238.15113719735876" width="600" src="https://images.upgrad.com/26314ece-47cd-4abd-b12f-a9b5cdd1b6c1-Main Body - PostsList Page.png"></p><p style="text-align: justify;">&nbsp;</p><p dir="ltr" style="text-align: justify;">g) You need to add a small icon&nbsp;"..." next to each post. You can use the FontAwesome icon 'ellipsis-h' for this purpose. When someone hover on these three dots icon, the cursor changes to pointer, as shown in the screenshot given below:</p><p>&nbsp;</p><p dir="ltr" style="text-align: center;"><img class="image-editor" data-width="574" data-height="163" height="163" width="574" src="https://images.upgrad.com/0439952e-acca-4171-a6ce-93825874fe63-Hover on Three Dots.png"></p><p dir="ltr" style="text-align: center;">&nbsp;</p><p style="text-align: justify; margin-bottom: 0px;"><strong><meta charset="utf-8"></strong>On clicking this icon, a user must be redirected to the third page 'post.html' to display the details of a post.</p><p dir="ltr" style="text-align: justify;">(You can keep this page empty as of now, and we will fill it later in the next segment of your project.)</p></div></div></div></div>
