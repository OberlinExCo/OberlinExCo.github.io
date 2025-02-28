# OberlinExCo.github.io
A Website for Oberlin ExCo

# Author
Initialized by Lars Dreith, Oberlin College '20

Maintained and updated by Alex Jensen, Oberlin College '21
Maintained and put in plain language by Veronica Mahoney, Oberlin College '22

## Deprecated as of February 2025
A new website is available at https://exco.oberlincollege.net

A new template in the _layout folder has been created with a redirect page, and the index.md file in the root has been set up to use that template instead of "home"

Should any future committee member wish to reverse these changes. Updating the template reference in index.md to "home" and committing new changes should be sufficient.

# About this README
Hello! This document is designed to help you update the website. First of all, here are some small but important notes. Whenever we refer to a directory, it is the same as a folder. In GitHub, that appears as a blue folder to the left of the name. Additionally, remember that a lot of coding is copying things that already exist and changing them slightly to fit our needs. For example, if we want to add a new link to a page, take an existing link and change the URL. Remember that it takes a little bit of time for the website to update.

Finally, if you have any questions, feel free to reach out!

# Includes Directory
Contains elements that occur on every page, such as the header, footer, navigation, and social links, as well as some other elements that have been separated out for ease of use. This is the directory that you will access if you want to update the current and previous committee members, as well as add webpages to/remove webpages from the navigation bar. A note: if you remove a webpage from the navigation bar, it is still accessible unless you delete it completely from GitHub. Generally, we use the same webpages over and change them each time (such as the Course Catalog page), so this shouldn't be necessary.

# Layouts Directory
Allows us to specify formats for the different pages in the website. We use the home layout for the homepage, the announcement layout any time we want a header with the word "announcements," and the default otherwise. See some of the webpages to see how this is used.

# Site Directory
Outdated directory. Not necessary to touch this.

# Image Directory
If you want to add any images to the website, add them here and then access them using /img/yourimage.jpg. This allows us to keep all of our images in one place.

# Assets Directory
Contains all of the stylizing files for the entire website. If you want to change something specific, such as every link color, it will most likely be in assets/css/style.css. This should not be necessary unless you want to change the entire layout of the website.

# Resources and About Directories
This is how we group together webpages that will appear in the same tab in the navigation bar. For example, if you want to add a page that you can access via the Resources tab, you should put it in the resources directory and then link it in the navigation from the includes directory, mentioned above.

Add old Course Catalogs to the oldcourses page, and if you notice any new blogs about ExCo, feel free to link them in the readmore page. An idea for the future: a page with quotes from instructors about how ExCo has impacted them.

# Teach Directory
Similarly to the resources and about directories, this is a grouped set of webpages that will drop down from the tab at the top of the website. This must be updated regularly, both to tell potential instructors when they need to apply or if the application season is currently not open. There is also now a page for great syllabi so potential instructors can have an idea on what is expected.

# Index
Use this to keep up announcements on the homepage. 
Copy and paste the existing text in order to add a new announcement. In order to make the links work you need to check in our actual coding account to see where different tabs are listed. For example, the catalog is just listed under catalog, but the committee bios is under about/committee (I think that is correct but dont quote me). Go off of those tabs rather than what the website says. You can delete old announcements as well.

# Fair
We generally put this as a tab during the first week of the semester, but then take it down for the rest of the semester (you can change the text to say that the exco fair already happened and to check back next semester). We generally add a link to the Course Catalog here and also embed the Course Catalog directly in the page. The way to do this is as follows:

Click the File button at the top of the Google Doc and then click Publish to the Web. You will see the options of Link or Embed. Click Embed and then Publish. Some code will pop up. You can copy this code directly into the Fair file on GitHub. You might need to adjust the dimensions of the iframe object. Right after the part of the code where it says <iframe, write width="1000" height="1000". I don't know if these are the right dimensions, but you can play around with it to find good dimensions for the website.

# Catalog
This is where we put the Catalog for a given semester. It should be fairly easy to update this by just changing the URL each semester.

# ExCo Committee Members
You'll have to update the committee members anytime someone new is hired/when someone graduates. To do this, go to "includes" then "members" to change the current committee members. To delete an old committee member highlight their text and delete it. Make sure to then go to  "includes" and "past-members" to then add the deleted member there. Write them a bio/edit their previous bio here. Update their info in the same way you add a new committee member. To add a new committee member I like to copy existing code for an old committee member and then paste it below the bottom committee member and above the table stuff that seems important (i know very little about coding, I'm just now in charge of this somehow). Replace the names and descriptions of the text with the info about the new committee member. Make sure to upload an image of the committee member first in the image directory (explained above). 
