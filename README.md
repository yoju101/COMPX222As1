# COMPX222As1
COMPX222 Assignment 1
Marks:20%
Due: 4 August 2023, 5 PM.
For this assignment you will create a static website using HTML and CSS. The aim is to code
the HTML/CSS yourself so you understand how it works. Therefore, you are not permitted to
use any tools like Dreamweaver or similar that automatically generate HTML. You should
ensure all code that you do create is formatted tidily and is easily readable with comments
and appropriate indentation.
The aim of this assignment is to make a website demonstrating your knowledge of HTML,
CSS and HTTP. The content of the website will concern HTTP. The implementation of the
website will demonstrate the use of several HTML and CSS features, including responsive
design for images.
Content
Create a website for teaching high school kids about HTTP. We had a single lecture about it,
but you can go into much more detail by doing your own further reading. The website
should have pages with the following titles and descriptions:
• “What is HTTP and HTTPS?” – an overview of the protocol
• “How is a web page downloaded?” – use your browser’s network console to load a
webpage, and then analyse the sequence of HTTP requests made when loading the
page; make this page an annotated explanation of this trace; use a page with a
relatively small number of requests (e.g. 10-20) and make sure it has a mixture of
images and text files such as style files that are loaded
• “What is a request?” – describe the format of an HTTP request as well as you can, and
include a description of common error codes
• “When to use GET and POST?” – explain when and why you use one type of request
and not the other
Each page should have approximately 400 words of content on average. Additionally, there
should also be a way of navigating the site so that all pages are reachable from any one page.
Each page should display at least one image. The images can be drawn by you, or
downloaded provided they have a creative commons licence (see Images à Tools à Usage
Rights when using Google image search). The catch is that you must provide three versions
of each image: a narrow version for small phones, a medium version for narrow windows on
a monitor, and a large version for when the browser is stretched very wide. We will test
your website with a 1080p monitor (1920x1080). You will need to create the versions of the
images yourself.
Implementation
• Ensure that you meet the following technical requirements:
• The website is organised properly into appropriate folders.
• The default page for the website is index.html, which is located in the root of the
website.
• The style is completely separated from the content; this means there is a common
style.css file that is linked to from all the html pages, and when this link is commented
out, then the pages revert to a plain vanilla HTML style.
• Ensure that the following HTML elements are used and also styled suitably:
o Headings tags (at least two levels)
o Paragraph tags
o Divs (to divide each page into logical sections)
o Bulleted lists
o At least one table
o At least two span tags
In each case, it’s up to you to ensure that the use of this HTML element makes sense
and also to make it very clear where it is used so that we won’t miss it when
marking.
• Ensure that at least the following CSS elements are used in the style:
o A CSS grid
o A CSS selector of the form element1 element2
o A CSS selector of the form element1>element2
• For the images, we will use a responsive approach. Each image should have three
variants (narrow, medium, wide), and the browser should automatically select the
variant depending on how wide the page is.
Marking
Marks will be allocated as follows: 5 marks for HTTP content quality, 5 marks for the
HTML, 5 marks for the CSS, 5 marks for the responsive images. You may assume
we will test your website in the R block linux labs using Firefox. Make sure that your use of
each of the required HTML/CSS elements is obvious so we can ensure nothing is missed.
Submission
Please zip your website up into a single file and submit it via moodle before the due date.