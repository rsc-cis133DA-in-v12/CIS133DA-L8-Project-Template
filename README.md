# Lesson 8 Project
This week, the computer company client is asking you to remove the internal CSS and use external CSS so that the colors could be easily edited by the company in the future. They’ve provided a template as a jump start for making a page they'd like to have included in their website, an About page. You will be making the About page in this lesson according to the directions provided below.

Make sure you save and test your web page frequently this lesson, making sure that all elements within the web page are working and displaying correctly before you submit this project.

## Project Prep 
1. If you haven't done so already, clone the repo to your computer within your course folder.
2. Open the repo within VS Code. You can open this `readme.md` file within VS Code to view the project directions there. 

   > **TIP:** Right click on the file and choose the `Open Preview` option.
3. If there are files and folders present other than this `readme.md` file, take some time to familiarize yourself with the files within the repo so you know where they are located. This will help you when asked to use them within the project directions.

   > **TIP:** Before beginning any work on the project, read through all the steps to understand what you will be doing.

You will also need to move your internal styles so that they can be edited externally. To do this within the Explorer Pane in VS Studio Code, complete the following:

1. Create a subfolder within your Lesson 8 course folder called: **css**
    
    > **TIP:** Review the **How-To: Create a Subfolder in VS Code** from Lesson 6, Inserting Images as a reminder for creating a subfolder.
0. Create an external stylesheet in the CSS subfolder called: **default_style.css**
0. Open the **template.html** file and do the following:
    - Appropriately link the external style sheet you created in the previous step.
    - Copy the CSS from the internal stylesheet and paste it to the external stylesheet.

    > **TIP:** Go back to **Lesson 7, External Stylesheets** to review how-to add an external stylesheet.
    - Remove any remaining HTML for the internal stylesheet.
    - Save your changes.

## Create the About Page

1. Save a copy of the template file to your Lesson 8 folder as: **about.html**
2. In the HEAD section, update the **multi-line comment** to add your section number and the lesson number.
3. Within the HEAD section, update the **metadata** with the following:
    1. Change the title to: **About Us**
    2. Define the author using your first and last name.
    3. Add a minimum of **5 keywords** appropriate for the page content.
    4. Add an appropriate **description**.
4. Within the BODY section, create a content **division** element that starts right after the opening body tag and ends before the closing body tag. **TIP:** Essentially all content that currently exists in the body should be a child element of this new division element.
    1. Apply an id to the division element called: **wrapper**
    2. This will only be used once in your code, therefore use an appropriate unique identity.
5. Within the navigation bar, do the following:
    1. Apply a class to the "About" link element called: **active**.
    2. Apply a class to the list item containing the "Book an Appointment" link called: **right**
6. Within the main section, create an **aside** element.
7. Within the aside element, do the following:
    1. Display the image of the city of Phoenix provided to you in the repo.
    2. Create a caption for the image that displays: <code>Source: [Lisa Campbell](https://unsplash.com/photos/r6_My5ZpZXc)</code>
        - Include a working link to the source provided and apply an appropriate text-level semantic tag for the caption.
            > **Link to Source:** <code>https://unsplash.com/photos/r6_My5ZpZXc</code>
8. Within the main section, do the following:
    1. Create an **article** element to contain the second-level heading and paragraph of placeholder text.
    2. Change the second-level heading to display: **Welcome to Computer Systems Incorporated**
    3. Remove the placeholder text and replace it with paragraphs that provides the user with the following information: 

      ><code>We are a small but growing computer repair service company that opened our doors in Spring 2022. We are honored to service both home and business users within the greater Phoenix area and our technicians are experienced in servicing computers for both small and large companies<br><br>Whether its for home or business computer systems, our technicians are pros at cleaning physical hardware, removing malware and providing anti-virus software solutions, as well as providing computer repair or upgrades at your convenience.<br><br>Computer Systems Inc. are experts at selecting the best hardware for your business or home on time and within budget, we look forward to your service!</code>
9. Within the footer, add your MEID to the copyright and update the year, if necessary.

## Example Project
![Screenshot of example About page without CSS](https://raw.githubusercontent.com/rsc-cis133DA-in-v12/CourseResources/main/L8-example1.png)

## Style the About Page

1. If necessary, open the external stylesheet.
0. Add a multi-lined comment that displays:
    > <code>Author:<br>Course:<br>Lesson:</code>
    - Insert your MEID as the author, your course name (CIS133DA) and section number for the course, and add the current lesson number.
0. In the Header Styles, adjust the URL to the background image so that the image displays. **HINT:** The URL is relative to the location of the stylesheet - not the web page. Try reviewing relative URLs in **Lesson 6, Background Images**.
0. In the Navigation Bar styles, style the active class you created in this lesson to:
    - Add a background color using your desired color method.
    > **TIP:** This style should make it so that the page the user is actively on is highlighted.
0. In the Navigation Bar styles, style the right class you created in this lesson to:
    - Add a background color using your desired color method.
    - Float the element to the right.
0. Style the unordered list within the navigation bar to: 
    - Fix the navigation bar to the top of the page.
    - Change the width to 100%.
    > **TIP:** Notice how the navigation bar overlaps the content at the top of the page. Learn how to fix this in the next step.
0. Below the body styles, style the wrapper you created in this lesson to:
    - Add a light gray background color using your desired color method.
    - Add a top margin of 50px. 
    > **TIP:** Now you should notice that the navigation has less overlapping to the wrapper content. This is because of the margin you added, which moves your entire wrapper down 50px.
0. Within the main styles, style the main section to:
    - Define the width of the element to 900px.
    - Utilize an appropriate box-sizing value to automatically subtract any padding applied to the element.
    - Center the element on the page. **HINT:** The text alignment should not be affected, and remain at default (left).
0. Within the main styles, style the aside section to:
    - Apply a light gray background color using your desired color method.
    - Define the width of the element to 30% of the container.
    - Utilize an appropriate box-sizing value to automatically subtract any padding applied to the element.
    - Add 10px of padding to all sides.
    - Adjust the margin on all sides to 10px.
    - Float the element to the right.
0. Style the images within the aside section to:
    - Fill the full width of the container. **HINT:** Use a width value that will fill the parent element.
    - Define the height to 200px.
    - Adjust the size of the image so that the image will clip to fit to the size of the container.
     - Change the transparency of the image to 60% opacity.
0. Style the hover state of the images to:
    - Change the transparency of the image to 100% opacity.
0. Style the paragraphs within the aside section to:
    - Remove the margin on all sides.
    - Set the text color to gray using your desired color method.
0. Style the links within the aside section to:
    - Set the text color using your desired color method.
0. Save your changes. 
0. If necessary, open the Template and About page. Compare how the changes you made to the styles appear for both pages.

 ## Example Project
![Screenshot of example About page with CSS](https://raw.githubusercontent.com/rsc-cis133DA-in-v12/CourseResources/main/L8-example2.png)

## Submit the Project
Once you have completed your project, you need to let your instructor know that it is ready to be graded. This is done by submitting the Repo URL to the assignment in RioLearn.

   > **TIP:** If you need a refresher on how to submit your work, view: [Submitting Assignments & Viewing Feedback](https://riosalado.coursearc.com/content/cis-public/using-git-github-and-vs-code/submitting-assignments-and-viewing-feedback).
1. Save the file. You can either select **FILE>SAVE** or use the keyboard shortcut **CTRL+S**.
2. **Sync** the changes and apply a **Commit**.
3. Verify that all files appear on GitHub.

   > **TIP:** You can view any of your repos by going to the GitHub organization for the course - [RSC-CIS133DA-IN-V12 Organization](https://github.com/rsc-cis133DA-in-v12). Once you are viewing the class organization, you should see all of the Repos that you have accepted assignment invitations for. It is recommended that you bookmark this page for future reference. Push (i.e., sync) the files on your computer with GitHub to ensure all files are uploaded to GitHub for your instructor to view.
4. Right-click the link to your repository and select **Copy Link Address**.
5. Go to the Assessing Your Learning page in your RioLearn lesson, and click the link to submit the assignment. Paste the link to your repo in the assignment submission box.
