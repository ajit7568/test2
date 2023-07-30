# test2
<!-- hosted html link -->
 https://ajit7568.github.io/test2/
 <!-- index.html file -->
 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Test-2</title>
    
    </head>
    <body >
    
   <div class="container">
        <iframe width="20%" height="640vh" src="./index_sub1.html" ></iframe>
        <iframe width="79%" height="640vh" name="rightpanel" src="https://ajit7568.github.io/resume_ass/"></iframe>
    </div>
</body>
</html>
<!-- index_sub1.html file -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <p>Project 1 -  Resume</p>
    <hr>
    <div>
        <a href="https://ajit7568.github.io/resume_ass/" target="rightpanel">
            <img src="./Asset/Resume.png" width="100%" height="150px" alt="resume">
        </a>
    </div>
    <hr>
    <br>
    <p>Project 2 - Photo Cat app</p>
    <hr>
    <div>
        <a href="https://ajit7568.github.io/catphoto/" target="rightpanel">
            <img src="./Asset/Photo_Cat-app.png" width="100%" height="150px" alt="Photo cat app">
        </a>
    </div>
    <hr>
    <br>
    <p>Project 3 - Form</p>
    <hr>
    <div>
        <a href="https://ajit7568.github.io/form/" target="rightpanel" >
            <img src="./Asset/Form-task.png" width="100%" height="150px" alt="Form">
        </a>
    </div>
    <hr>
    <br>
    <p>Project 4 - Tribute Page</p>
    <hr>
    <div>
        <a href="https://ajit7568.github.io/tributepage/" target="rightpanel">
            <img src="./Asset/Tribute page.png" width="100%" height="150px" alt="resume">
        </a>
    </div>
    <hr>
</body>
</html>
<!-- Inside the <head> element, there are meta tags for character encoding and viewport settings, and the <title> element sets the title of the page to "Test-2."
The <body> element contains the visible content of the web page.
There is a <div> element with the class "container" that will hold two iframes side by side.
The first <iframe> displays the content from the index_sub1.html file. It has a width of 20% of the container's width and a height of 640vh, which means it will be 640 viewport heights tall (it's an uncommon way to set the height, usually vh is used for the viewport height, but here it's used as iframes' height).
The second <iframe> displays an external website located at "https://ajit7568.github.io/resume_ass/". It has a width of 79% of the container's width and a height of 640vh, similar to the first iframe. The name attribute is set to "rightpanel", which allows us to target this iframe from links with the target="rightpanel" attribute. -->
<!-- this is the index_sub1.html file that is loaded into the first <iframe> in the main index.html.
It is a simple HTML page with a list of projects.
The <body> element contains various project descriptions with images and links.
Each project is displayed as a <p> tag with the project's title and is separated by a horizontal line <hr>.
For each project, there is a <div> containing an anchor <a> tag with an image <img> as the link content.
The images are linked to different projects (e.g., resume, photo cat app, form, and tribute page), and they have a width of "100%" and a height of "150px".
The href attribute in the anchor tags points to the respective project URLs, and the target="rightpanel" attribute is used to open those URLs in the second iframe with the name="rightpanel" in the main index.html file.
Overall, this code sets up a webpage with two iframes side by side, where the left iframe displays the content from the index_sub1.html file, and the right iframe loads an external website related to the projects. The content in the right iframe changes based on the links clicked in the left iframe. -->

