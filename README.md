# The Hoggy Hospital
The Hoggy Hospital is a website for a fictional wildlife organisation that rescues and rehabilitates hedgehogs. The site targets people are interested in learning about the organisaton or who may wish to support it in some way.

On the website, users can find information about the Hoggy Hospital, its purpose and why its work is important, the ways that they can support the organisation, and information on how to contact it.

## User Experience
### User Story
Why a user may visit the website:

* To learn about the work the organisation does
* To contact the organisation in the event they find a sick or injured animal
* To find out if they can donate or contribute to the organisation in some way

What goals the organisation may have for the website:

* To reach a wide audience
* To encourage support from the public
* To provide information to users about the work they do
* To provide contact information to members of the public

## Features
### Navigation
- The header element features a navbar that is used across all pages. It remains at the top of the screen as the user scrolls down the site so they can easily navigate to different pages on narrower devices without having to scroll back to the top to find navigation.
- On the right of the navbar are links to the three main pages of the website. On hover, the links transition to green to ackowledge the users interaction. The "active" page has a bottom-border in green to reflect which page the user is currently on.
- The navbar features a logo to the left side which navigates to the main page. On larger screens the logo features a hedgehog with text of the name of the organisation. On smaller devices, the logo is replaced with a simple hedgehog to maintain branding but provide space for the links. On very small screens, the logo is removed to allow the links to be easily accessed and prevent misclicking on small devices.
- The background colour is a dark brown and the text is in white to provide good contrast. The transition and bottom-border are in green as it an appropriate colour for the theme of the site and contrasts well with the brown.

### Footer
- The footer element features social media links for the organisation. It features across all pages.
- The links feature a similar transition to green as the navbar.

### Index Page

The first page comprises four sections that introduce the user to the organisation, provide information about work of the organisation, and features a video accompanied by a call to action and an invitation to explore the website further.

#### Hero Image - index.html
- The hero section contains a large hero image of a hedgehog overlaid by the title of the website and organisation.
- The title features an ease-in transition when the page loads to draw the users eye.
- The section contains a call-to-action contact button below the title. Although the contact page is easily visible on the navigation bar, the button being immediately displayed in the header means the user can find contact information quickly. The button is styled in a dark red colour taken from the hero image itself with text in white. On hover, the button's colour scheme is inverted.

#### About Section
- The about section features three short paragraphs of text giving the user an introduction to the organisation. These paragraphs are intentionally short so as not to overload the user with information immediately on arrival and to encourage the user to keep reading. 
- The section is styled such that on large screens the paragraphs display as a row, but wrap to fit beneath each other on smaller devices.
- The text contains inline links to the How To Help page and Contact Us page, where appropriate. These are styled in the sam dark red colour as the CTA button in the Hero section.

#### Why Help Hedgehogs Section
- This section provides information to the user about the reasons animals come into the care of the organisation. This serves to provide motivation for the user to become emotionally invested in the work the organisation undertakes.
- The section is styled with a background image which appears as the user scrolls down so that as the text information comes into focus, so too does the hedgehog's face. This also is aimed at appealing to the user to become emotionally invested while rewarding them with a cute image as they scroll down the page. The background image also serves to break up the page into sections.

#### Who You're Helping Section
- The video element with accompanying text serves as a call to action. 
- The video provides controls to allow the user to initiate playback and is muted on load so the user won't be surprised by any unexpected noise. It is a simple video aimed at appealing to the users desire to see cute animals and could easily be substituted in a real wildlife organisation with a real video of a rescued animal.
- The text accompanying the video includes inline links to the How To Help page and Contact page to encourage the user to engage further with the website now that they have reached the bottom of the first page.

### Help A Hog Page

The second page of the site is similarly comprised of four sections. It focuses entirely on encouraging the user to support the organisation and features interactivity to engage the user.

#### Hero Image - help.html
- To match the first page, the first section contains a hero image as well. This provides an opportunity to reward the user with an appealing image of a hedgehog for visiting further into the page.

#### Help Introduction Section
- Comprised of text and an accompanying image, the introductory section of this page encourages the user to support the organisation by giving a summary of the ways available to help.

#### Ways To Help Section
- This presents the three main means of help that the organisation accepts.
- It is styled on a light background that highlights the images as important features and separates them from the sections above and below. The three images are styled to wrap on smaller devices while remaining centered on the page. Using the hover pseudoclass, the user can interact with the images so that the image transitions to text specific to the option they are interacting with. 

#### CTA Section
- At the bottom of the page is a simple call-to-action section. At this point, the user has presumably explored all the previous sections of the site and been presented with information about the organisation's work and the ways the user can help. They are invited by a question in the title and a large button element to contact the organisation.
- The button element is styled similarly to the CTA on the index.html hero section, though slightly larger as it is the focus for the user here. When hovered over, the button style changes to give feedback to the user.

### Contact Page
The third page of the website contains all the relevant information that the user may need to contact or locate the organisation. It is presented as three simple, similarly styled boxes or cards over a large background image of a hedgehog. The emergency contact always remains on top and centered horizontally. On large screens the form and location elements are displayed in a row below, with the location element wrapping below the form on small screens.

#### Emergency Contact
- Horizontally aligned centrally with a large heading, the first element presented to the user is the phone number to contact in case of an emergency. One of the main reasons a user may visit a wildlife rescue organisation's website is to find contact information in the case that they have found an injured animal, so this information is provided first and clearly labelled.

#### Contact Form
- The second element is the form element for a user to use to contact the organisation. The only required inputs are the name and email address. There is an option to include their phone number for contact purposes, but it is not required in the case the user is not comfortable providing that information. The user has the option to select checkboxes to identify if and how they would like to support the organisation. The user also has the option to include a message in the textarea element.
- Currently, the form opens a new tab to confirm receipt of the submitted form.

#### Location
- The third element contains the location information for the organisation. This includes a iframe element with the organisation's location pinned on the map so users can easily find it.

### Received.html
This page serves to provide feedback to the user when they click submit on the form element. They are directed to a page containing simple text and the navigation and footer elements to allow them to navigate to the main site. This page is not accessible through the navigation element as it is not intended for the user to see it unless they have completed the form. 

### Future Expansion
As a wildlife rescue website, there are a variety of features that could be implemented in the future.
1. A direct donation link. This could be connected to the organisation's PayPal account or similar, allowing the user to donate directly on the page, quickly and easily.
2. A blog. It provides further user engagement and encourages users to return. Users of these types of sites enjoy learning more about individual rescue cases. It can also be used to direct views from social media to the site, for example, through short synopses on Facebook or Instagram with links encouraging the user to read the blog for the full story. Similarly, it can direct views to the organisations social media sites, e.g. by linking to their videos on YouTube.
3. A gallery. This could comprise solely of pictures of the animals rescued or include the facilities or staff of the organisation, creating a more personal connection with the user.
4. An online shop. An online shop with options to purchase limited branded merchandise (e.g. mugs, stickers, etc.) or sponsorship of an animal could be implemented as a means of fundraising, branding or to encourage user engagement.

## Design
### Imagery
On an animal related website, users expect visual content of animals so the site was designed around including a large amount of images of hedgehogs. The images are chosen for being clear, close up images that invoke a positive responsive in the user. All but two sections of the site contain an image or video of a hedgehog to encourage and reward the user for exploring the site.
- The navigation logo was drawn in Inkscape. On large devices, it includes the name of the hospital. On smaller devices, the text is removed but the logo remains. On very small devices, unfortunately it was decided to remove the logo to allow space for the links. The logo is a very simple design, easily recognised as a hedgehog at different sizes.
- The hero images were chosen for being large quality, close up images. The positioning of the hedgehogs in the images gives the impression of them approaching or looking to the headings in the hero sections.
- Linear-gradients were applied in the CSS to the background image on the Why Help Hedgehogs section of the index age and the background image of the contact page. This improved readability of the text over the images but still allowed them to be viewed clearly. 
- The images used on the website were edited in Gimp and exported as webp to reduce size. The large background of the contact page was compressed using TinyPNG to improve performance.

### Colour
The colours used were sampled from the hero image on the index page. They include a dark brown, dark red, green, light yellow and off-white. A black was used for text that was chosen separately. The colours were chosen to convey an overall earthy and natural feel. Several were tested for readability until the final selection were decided. It was decided not to use to many or too vibrant colours and to allow the imagery to be the focus.

### Typography
Google Fonts was used to import the Raleway font to style.css to be used as the main font. Verdana was chosen for headings. These simple sans-serif fonts were selected as they are quite easy to read and not distracting for the user. A small increase in line height and letter spacing in style.css improved readability. Font sizes were styled to change across screen sizes. 

### Buttons and Links
- Links in the header and footer were styled white with a green fade-in transition to provide feedback to the user when they were interacting with the links. 
- Inline links and buttons were styled similarly to each other. It was decided on a dark red colour to style both so as not to confuse the user. The colour chosen as it was easily readable without being too distracting. Inline links were given an increase in font weight to stand out further from surrounding text. CTA buttons and the submit button on the contact form were styled with white text on the dark red. This inverts when hovered over to provide feedback to the user that they are about to interact with an element.

### Wireframes
Wireframes were created in Balsamiq.
- Home Wireframe
![Home Wireframe](readme-docs/index.png)

- Help A Hog Wireframe
![Help A Hog Wireframe](readme-docs/help.png)
- Contact Us Wireframe
![Contact Us Wireframe](readme-docs/contact.png)

### Mockups
Mockups were created in Gimp to visualise the layout with images in place and experiment with colours. The final colours and were not decided until the website was tested with Lighthouse.
![Gimp Mockup](readme-docs/hog-hospital-gimp-mockup.png)

## Technologies Used

- [HTML5](https://en.wikipedia.org/wiki/HTML5): mark-up language.
- [CSS3](https://en.wikipedia.org/wiki/CSS): styling.
- [GIT](https://git-scm.com/): for version control.
- [GitHub](https://github.com/): for host repository.
- [Gitpod](https://www.gitpod.io/): online IDE.
- [Google Fonts](https://fonts.google.com/): to import fonts.
- [Font Awesome](https://fontawesome.com/): to import icons.
- [Balsamiq](https://balsamiq.com/): to create wireframes.
- [GIMP](https://www.gimp.org/): to edit images, create a mockup and select colours.
- [Inkscape](https://inkscape.org/): to create the logo.
- [TinyPNG](https://tinypng.com/): to compress images.

## Testing
### [HTML Validator](https://validator.w3.org/)


### [CSS Validator](https://jigsaw.w3.org/css-validator/)