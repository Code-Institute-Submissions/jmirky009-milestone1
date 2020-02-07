# User Centric Frontend Development – Code Institute

This is a website showcasing the band known as “The Monkees”. On the site you will be able to find general information about the group, images, links to music and videos, upcoming tour dates as well as a form to submit messages to the band.

## UX

The website was designed with fans in mind who either want to access the bands media or get in touch with them. There is also scope with being able to stay up to date with tour dates with links that would take them to the ticket sellers. 
If you wanted to find images, media, tour dates or even contact the band; all of this can be achieved with the top navigation. There are also links to the bands social media accounts so fans can keep up to date with them in other ways. 


## User story:

### Fan
Can listen to new tracks as well as find the links to social media

### Journalist
Would be able to see upcoming tour dates or new release and report on them.

### Curious
Someone who hasn’t heard of the band before can easily come to the page and find information about them as well as listen or watch them for the first time.

## Wireframe

Please find the wireframe below
https://wireframepro.mockflow.com/view/monkeesprojectxyx


Features
In this section, you should go over the different parts of your project, and describe each in a sentence or so.

Features Left to Implement
•	Having an embedded video player as opposed to a media download

Technologies Used
•	HTML
•	CSS
•	Bootstrap 4.0.0-alpha.6

## Testing

To test the responsiveness of images and text sections on the site I used a varety of devices to see how it would display when using a smaller screen. These devices included iPhones, Android Mobiels, Mac laptops and also Windows laptops. On windwos laptops I have used Google Chrome, Firefox and Internet Explorer to test the consistency of the layout.

1.	Contact form:
i.	Go to the "Contact Us" page
ii.	Try to submit the empty form and verify that an error message about the required fields appears
iii.	Try to submit the form with an invalid email address and verify that a relevant error message appears
iv.	Try to submit the form with all inputs valid and verify that a success message appears.

2. Responsive design
i. The gallery responds to the various screen widths by reducing the number of photos appearing on one row:
    - 5 images per row on a large row
    - 4 images per row on a medium screen
    - 2 images per row on a small screen
    - 1 image per row on an extra small screen

ii. The blurb for the Monkees collapses into one column when the screen goes to an extra small state (e.g. mobile devices)

iii. The tour date section has responsive images that increase and decrease in size as the screen grows, and disappear altogether when ther screen goes to an extra small state. 

iv. The media sections change from inline to block when the screen reaches a small size (tablet and smaller).


## Deployment

The site is currently deployed on GitHub Pages. To do this I pushed all the content (index page, media assets and style sheets) to my Github repository and made it publically accessible. 

There were various branches of the index page created but I used these to test validation features on the Contact Us form. In the end I stayed with the master branch as the form is out of the box from bootstrap.

To start, the code was run on Cloud9 and due to availability, this was later sent Cloud9 on Amazon Web Services (AWS) instance of Cloud9. This caused minor complications as the original Cloud9 didn't require a root folder for the images and assets to appear. 



## Credits
Content
•	The text for the information section was provided by Wikipedia (https://en.wikipedia.org/wiki/The_Monkees)

## Media
Most of the images were provided by code institute but others were taken from google images when searching “Monkees HighQuality Images” including:
•	Morrisonhotelgallery.com
•	Kiss.png 
•	Commons.wikimedia.org
•	Media files for audio and video were provided by code institute

# Acknowledgements
https://stackoverflow.com/questions/11679567/using-css-for-fade-in-effect-on-page-load - provided insight with how to fade in images on loading 

https://www.codeply.com/go/4FdZGlPMNV - helped me created a custom coloured hamburger icon

https://fonts.googleapis.com/css?family=Dokdo|Gloria+Hallelujah - for the selected font used

https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js + https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css provided the relevant stylings for the site. Without this the grid layout would not have been achievable.

