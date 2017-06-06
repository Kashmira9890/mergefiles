# mergefiles
Moodle Plugin for merging pdf files in a course<br>

The ‘Merge PDF Files’ plugin offers users a convenient way by which they can merge the PDF documents in a Moodle course. <br>
This plugin requires two external tools:<br>
 * PDFtk (short for PDF Toolkit) is a cross-platform tool for manipulating Portable Document Format (PDF) documents. It comes in three flavors: PDFtk Free, PDFtk Pro, and a command-line tool PDFtk Server.<br>
 * LaTeX – A document preparation system for high-quality typesetting. It is most often used for medium-to-large technical or scientific documents but it can be used for almost any form of publishing.<br>

The module is created and is currently being worked upon at IIT, Bombay (India). <br>

How to use?<br>
This folder is to be added under moodle/report directory.
Also, the folder contains a patch file which needs to be applied.

After adding this plugin to moodle:
 * Go to a particular course
 * Click on settings icon
 * A link saying "Merge PDF files" appears in the course settings (drop-down menu) list.
 * Then, you get a page listing all the pdf files in that particular course.
 * At the end of this page, you get a button labeled "Merge pdf files".
 * On clicking the button, the user will get a merged document of all the course files listed on that page.

Usage:<br>
Through this feature, now users will be able to merge pdf files in a particular course from within moodle itself.

Work in progress:<br>
The following functionality is currently being incorporated into this plugin wherein:
* user can shufffle the listed pdf files
* user can select only a few/all pdf files
* a list of previously merged pdf documents will be displayed to the user
