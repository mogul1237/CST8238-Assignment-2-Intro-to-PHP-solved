# CST8238-Assignment-2-Intro-to-PHP-solved

Download Here: [CST8238 Assignment 2 – Intro to PHP solved](https://jarviscodinghub.com/assignment/assignment-2-intro-to-php-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

Purpose

• To be familiar with a real life web page and add functionality to this page using the PHP scripting language
Due Date/Course Weight

This assignment must be submitted before midnight on Nov 06, 2016.

• NOTE: Late assignments will not be accepted.

This assignment is worth: 10% of your total course mark
Assessment

Please follow the Assignment 2 Assessment document for more information.
Summary of Tasks

Listed below are the sections of the assignment which will need to be completed:

1. Download Travel.zip file from ‘Course Content -> Assignments -> Assignment 2- Travel’ folder on Blackboard which contains all files required for Assignment 2.
2. Modify travel.php and travel-image.php files to accomplish Task 1.
3. Modify travel-left-rail.php to accomplish Task 2.
4. Test your webpage on a local web browser using EasyPHP/XAMPP.
5. Submit source code of travel.php, travel-image.php, and travel-left-rail.php on Blackboard.
Task 1

You have been provided with Travel.zip file in which you have two files to modify: a page that will eventually contain thumbnails for a variety of travel images (travel.php) and a page that will eventually display the details of a single travel image (travel-image.php). Clicking a thumbnail in the first file will take you to the second page where you will be able to see details (relevant title, image, user name, country, and description) for that image, as shown in Figures below.

Sample Screenshot of travel.php is as follows:

Write a loop that displays these images and links using data within the $images array defined in travel-data.php

Notice that links for each thumbnail includes id as query string parameter.

Sample Screenshot of travel-image.php is as follows:

Display the appropriate data from $images array defined in travel-data.php

Task 2

Inside Travel.zip, there is another file travel-left-rail.php which contains the markup for the navigation rail on the left side of both pages. Replace the hard-coded continents and countries lists in the file with loops that output the equivalent markup but use the data defined in the arrays ($continents and $countries) in travel-data.php. After verifying that it works, use the appropriate sort functions to sort the continents and countries arrays alphabetically.

Screenshot of travel.php, specifying Task2, is as follows:

Write loops to display these menus using arrays defined in travel-data.php. Also use appropriate PHP sort function.

To accomplish Task 1 and Task2, please follow the Instructions below

1. Unzip Travel.zip into a folder named Travel. Both travel.php and travel-image.php pages will make use of arrays that are contained within the file travel-data.php.
Include this file in both pages.
2. Within travel.php in the

below the Favourites heading, replace the existing markup with a loop that displays the thumbnail image and link for each of the elements within the $images array (which is provided within travel-data.php). You must display the images as

in travel.php. Notice that the links are to travel-image.php and that they pass the id element as a query string parameter.
3. In travel-image.php, retrieve the passed id in the query string, and use it as an index into the $images array of travel-data.php. With that index, you can output the relevant title, image (in the images/travel/medium folder), user name, country, and description.4. Both pages (travel.php and travel-image.php ) make use of an include file called travel-left-rail.php. Replace the hard-coded continents and countries lists in the file travel-left-rail.php with loops that output the equivalent markup but use the data defined in the arrays ($continents and $countries) in travel-data.php. After verifying that it works, use the appropriate sort function to sort the continents and countries arrays alphabetically.
Task 3
Test your website on a local web browser using EasyPHP/XAMPP.
Task 4

Once you have confirmed that your webpage is available online, you are ready to hand in your lab.

To hand in your lab go to Blackboard and navigate to Course Content  Labs and click on ‘Assignment 2 – Intro to PHP’ link.

Under “Assignment Submission”, in the Submission text box write out the following Information:
• Student Number
• First Name
• Last Name

Under “Assignment Submission”, submit the following files as a single .zip file:
• travel.php
• travel-image.php
• travel-left-rail.php

Finally, once the Submission section is complete, click the ‘Submit’ button to send the Assignment to your Professor.

IMPORTANT NOTE:
You may only submit a Lab ONE TIME. Be sure the lab is complete before clicking on the ‘Submit’ button
