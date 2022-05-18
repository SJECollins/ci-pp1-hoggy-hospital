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
- The header element features a navbar that is used across all pages. It remains at the top of the screen as the user scrolls down the pages so they can easily navigate to different pages without having to return to the top of the page.
- To the right of the navbar are links to the three main pages of the website. On hover, the links transition to green to ackowledge the users interaction. The "active" page has a bottom-border in green to reflect which page the user is on.
- The navbar features a logo to the left side which navigates to the main page. On larger screens the logo features a hedgehog with text of the name of the organisation. On smaller devices, the logo is replaced with a simple hedgehog to maintain branding but provide space for the links. On very small screens, the logo is removed to allow the links to be easily accessed and prevent misclicking on small devices.
- The background colour is a black and the text is in white to provide good contrast. The transition and bottom-border are in green as it contrasts well with the black.

### Footer
- The footer element features social media links for the organisation. It features across all pages.
- The links feature a similar transition to green as the navbar.

### Index Page

The first page comprises four sections that introduce the user to the organisation, provide information about work of the organisation, and features a video accompanied by a call to action and an invitation to explore the website further.

#### Hero Image - index.html
- The hero section contains a large hero image of a hedgehog overlaid by the title of the website and organisation.
- The title features an ease-in transition when the page loads to draw the users eye.
- The section contains a call-to-action contact button below the title. Although the contact page is easily visible on the navigation bar, the button being immediately displayed in the header means the user can find contact information quickly.

#### About Section
- The about section features three short paragraphs of text giving the user an introduction to the organisation. These paragraphs are intentionally short so as to encourage the user to keep reading. 
- The section is styled such that on large screens the paragraphs display as a row, but wrap to fit beneath each other on smaller devices.
- The text contains inline links to the How To Help page and Contact Us page, where appropriate. These are styled in the same colour as the CTA button in the Hero section.

#### Why Help Hedgehogs Section
- This section provides information to the user about the reasons animals come into the care of the organisation. This serves to provide motivation for the user to become emotionally invested in the work the organisation undertakes.
- The section is styled with a background image which appears as the user scrolls down so that as the text information comes into focus, so too does the hedgehog's face. This also is aimed at appealing to the user to become emotionally invested while rewarding them with a cute image as they scroll down the page. The background image also serves to break up the page so it appears as distinct sections.

#### Who You're Helping Section
- The video element with accompanying text serves as a covert call to action. 
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

