# bad-ash-bakes
This repository will be used for my Code Louisville Front End Project. I will create a website called Bad Ash Bakes.

<h2> What My Project Is For: </h2>

  I have created a single page website for the fake (for now!) business, Bad Ash Bakes. Bad Ash Bakes is a baked good subscription service. Viewers of the webpage should be able to view information about the owner of Bad Ash Bakes and the subscription service offerings. Users can also view a pricing guide as well as sign up for the subscription service online. 
  

<h2> Special Features Incorporated In This Project: </h2>

1.) At the top of the screen you will see a responsive nav bar. The links will jump the viewer to different areas on the webpage. The nav bar is also responsive. When the screen is resized, the navigation bar options collapse into a hamburger style menu.

2.) There is also an image carousel with three images. There are  dark grey arrow icons on the left and right side of the images. Click on the arrows to view all images. When hovering over the arrows, the arrow background will change to a pink color. 

3.) I used media queries for a responsive layout. You will see bootstraps media queries, as well as some custom made queries used for my navbar. I added the bootstrap queries as a reference because I used bootstrap to create a responsive layout in the body of my webpage. 

4.) For the body of my wepage, I imported Bootstrap from a CDN and used its column system to create a responsive design. You can see the CDN in the head of my html file. I used it to create a two column layout that collapses to a one column layout. I also used bootstrap styling classes for padding and some other styling features. I realized that sometime bootstrap would override some of my custom styling and it made more sense (and was more effective) to style some of the features of my page this way. There is also custom styling as well. I did not just use bootstrap styling. 

5.) I created a table to display size and pricing options. I used the :nth child styling to make every other row a different color.

6.) I created a form for users who would like to subscribe to the service. If you click submit and any fields are blank, you will recieve a prompt asking you to fill in the field. If you enter an email address and it does not contain the "@" symbol, you will also recieve a prompt. This would fulfill the requirement "Create a form that takes in at least two fields of information and validates input (for example, it checks to ensure email is the a@b.com format"

7.) When all fields in the form have been filled out correctly and the submit button has been clicked, a pop up window will appear at the top of the window, thanking the user for enrolling. This would fulfill the requirement "Create a JavaScript function whose return value is used in your site. The function must be triggered by user action (ex: clicking a button)."
