# Blue Cross Support 

This project was designed to support the charity of Blue Cross. In simple and intuitive form it will present the information to the user. So that they could learn some general information about the charity, how does it help, where is it located along with that they could donate or contact the Blue Cross.
The visuals of the website must be clear, well arranged and appealing. Also, it must be kind of simple so the user won't have any complications while using it. 
In short - it must present the charity to a new public and attract them to their cause.

## User Experience:

This website is designed for the general public to inform them about Blue Cross charity. It must attempt to appeal to the user and encourage them to donate or use their services. 
In theory, those users will desire to see some general information about Blue Cross, how they help, where are they located and how to contact them. All of that is required to learn more about the charity and then make a fact-based decision on whether to support the charity or not.
Also, the user might desire to learn further about Blue Cross so the corresponding links to the original website should be provided.

Please follow the link to my wireframe: https://wireframe.cc/aAe6IX
## Features:

The easy-to-use user interface. It will change the button layout depending on the device used. On desktop devices and tablets all the links will be arranged in-line in single row. While on mobile there'll be one Menu button in the corner, which when clicked will collapse a list of links.
Carousel images which make the site more appealing while setting the correct mood for the rest of the page.
General information area with embedded FaceBook video, which just quickly shows some of the things Blue Cross does.
Four cards with pictures on the background. The text will be positioned inside the semi-transparent container. Like most of design choices, it contributes to the visual appeal of the page.
A donate section, where I attempt to encourage the user to donate. Right below the plea, there's a button which when clicked upon will transfer the user to official donate page of Blue Cross.
Interactive Google Maps iframe, which marks all the branches of Blue Cross on the map. A full list is available next to the map. And if the user finds the area they're interested in they can click on it to go to the page with extra details.
A contact form which permits user to send a message or suggestion to the Blue Cross charity.
Social media links located in the footer of the site. So that the user can follow them and see more recent news on those pages.

## Technologies Used:
WireFrame : https://wireframe.cc/aAe6IX: Used it for the initial design of the website.
Bootstrap: https://getbootstrap.com/: It were used for grid system, quick placing manipulations and the JavaScript it provides.
FontAwesome: https://fontawesome.com/: I used it to add icons to the links in the footer section.
Google Fonts : https://fonts.google.com/: It was necessary to use other than default fonts on the page.

## Testing: 
The project was thoroughly tested to pinpoint any design errors or code misuse. Through testing, I relied on two basic functions for all tests: a preview page and Google Developer Tools.

To save a bit of time further on, I'll expand on how I used mentioned functions. 
First of all the preview page, this is the barebones of test's I've done. Through the entirety of the project, I've been visiting the preview page to ensure everything displays as intended and properly functions. To achieve this, every time I've added a new element, container, button, image or a style rule - I entered the preview page to ensure it does exactly what I want it to do.
Then if some error occurs I use the Google Developer Tools by right-clicking on the element I desire to test and then select the Inspect option. This brings up the code, box model and other useful tools. For this project I heavily relied on box model, to show me all the padding and margin's so I can see what I need to adapt for it to display correctly. However whenever it's no padding or margin that I need to change or the problem persists - I use to code viewer. By selecting containers with problematic content, I inspect the code and try disabling/enabling some of the CSS rules. Then make conclusions and attempt to fix the code based on whatever idea comes in my head.


## Site Section Testing Scenarios:
### Navigation Menu (Desktop):
go to the website.

select each link one-by-one to ensure that they are functional.

Attempt to go to every section.

Results - All of the links are functioning / Success


### Navigation Menu (Mobile):
use a mobile device to ensure that the menu adapts.

If the Menu button is present click on it and verify that all links are present.

Click on each link to navigate other sections, test pass if all links are working.

Results - Button expands the link list, all links are functional / Succes


### Carousel Images:
Navigate to the top of the page.

Make sure that the carousel images are working and changing every 3 seconds.

There must be no empty gaps on the sides and images must fit the screen.

Results - Images replace each other every 3 seconds, no gaps present / Success


### About Us Section:
Get to the About Us section.

Make sure the text is aligned to left on the desktop and is centred on mobile devices.

The embedded Facebook video must be working and adapt to the screen size.

Results - Text aligns properly, FaceBook video is responsive and in working order.


### How We Help Cards:
Scroll down to How We Help section.

There must be 4 cards with pictures on background and text on a white foreground.

There must be 2 rows of 2 cards on desktop devices and 4 rows of one card each on smaller screen sizes.

Results - All 4 cards are present, background displays as intended and there's the subtle white background behind the text. Cards position changes depending on the screen size.


### Donate Section:
Find the Donate section.

Information presented in neat order while located in the container.

The donate button is working and redirecting the user to the official Blue Cross donate page.

Results - Text is positioned withing Bootstrap container and the button is functioning as intended.


### Google Maps:
Navigate to the Find Us section.

The Google maps are positioned on the left and are interactable. On mobile devices, it must take the entire row of space.

Two unordered lists must be either on the right or below the map. 

Lists present all branches in neat order and redirect user to the relevant page whenever the li element is clicked.

The result - Google Map displays as planned. Unordered lists are present and position themselves as required on different devices. All of the links are functioning. / Succes

### Form Section:
Find the form.

Try entering false details.

The form must reject if Email is incorrect (Name/Surname aren't required.)

Ensure that Submit and Reset buttons are working as expected.

Results - The form is rejected whenever email is of wrong format. Buttons are functioning and the form is pleasantly looking. 


### Footer Check:
Must show some TradeMark information (more on desktop devices)

The social media links must be working and redirect user to appropriate pages.

Icons must be displayed as links.

Results - TM information displays as I planned, icons display properly and act as links.


## Compatability:

To ensure that website works as expected on different plaforms I sent a link to some of my friends who used different devices. This way I managed to test the responsivness of site across different platforms.
Including the following:

-Laptop HP Pavilion 

-Samsung Galaxy S5/S6/S7

-Iphone 5

-Iphone 6

-My PC 

And across all of those devices the website worked as expected. 

## Deployment:
At the moment I didn't require any special deployment settings due to the simplicity of the project and lack of knowledge in that sphere. So all I've had to do to deploy this project:

-Navigate to GitHub

-Find and select my Blue-Cross-Support repository.

-Select the 'Settings' tab

-Scroll down until I find GitHub Pages section

-Select the source as "master branch'

-Verify the action and deploy the project!


## Credits:
Majority of the presented content was copied from the official Blue Cross webpage -https://www.bluecross.org.uk/ 
I express my gratitude to them for giving me permission to utilise their assets. Thanks, guys, it means a lot to me!

Carousel photo's and form background were pulled from those sites:

https://wallpaperscraft.com/download/dog_street_small_abandoned_26615/1920x1080

https://www.petsforpatriots.org/11-signs-of-animal-cruelty-and-how-you-can-help/abandoned-cat-cruelty-720x450/

https://www.peta.org/wp-content/uploads/2016/03/homeless-dirty-white-cat-PETA-owned-602x400.jpg

https://designwoop.com/free-subtle-textures

The inspiration and determination to make this project came from my lovable cat Ozzy. I must serve my fluffy overlord!
