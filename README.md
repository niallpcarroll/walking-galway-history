
# Walking Galway History

The aim of this website is to provide clear and concise information on walking tours of Galway, Ireland, which focus on the city's history.

It is aimed primarily at tourists and visitors to Galway, and it is designed to provide eaily accessible and up-to-date information about the walking tours on offer.

Find the link to the site [here](https://niallpcarroll.github.io/walking-galway-history/)


![Image of the site depicted on different devices](assets/images/readme-images/responsive-site.)



## Contents

- [User Experience](#user-experience)
  - [User Stories](#user-stories)
- [Design](#design)
  - [Colour Scheme](#colour-scheme)
  - [Typography](#typography)
  - [Imagery](#imagery)
  - [Wireframes](#wireframes)
- [Features](#features)
  - [General Features on Each page](#general-features-on-each-page)
  - [Future Implementations](#future-implementations)
  - [Accessibility](#accessibility)
- [Technologies Used](#technologies-used)
  - [Languages Used](#languages-used)
  - [Frameworks, Libraries & Programs Used](#frameworks-libraries--programs-used)
- [Deployment & Local Development](#deployment--local-development)
  - [Deployment](#deployment)
  - [Local Development](#local-development)
    - [How to Fork](#how-to-fork) 
    - [How to Clone](#how-to-clone)
- [Testing](#testing)
- [Credits](#credits)
  - [Code Used](#code-used)
  - [Content](#content)
  - [Media](#media)
  - [Acknowledgments](#acknowledgments)

## User Experience
The Walking Galway History website is designed to be easy and intuitive to use. It does not aim to provide extensive information on the history of Galway, but rather aims to encourage visitors to actually take part in the walks.

### User Stories
The website should be very straightforward for first-time users - the aim of the website is clear and the necessary details are easily accessible.

Recurring visitors....

## Design
### Colour Scheme
![Image of the colour palette used](assets/images/readme-images/color-palette.)

Choice of colours...


### Typography
The site uses two fonts: "Poppins" for general text and "Madimi One" for headings. 

![Image of the font used in headings, Madimi One](assets/images/readme-images/font-headings)


"Madimi One" is a fun, almost brush like font. It is a quite bold font, used in uppercase to make it stand out.


![Image of the font used in general text, Poppins](assets/images/readme-images/font-general-text.)


"Poppins" is a sans serif-font, easier to read.
### Imagery
The images used on the website are up-to-date images of Galway, and they are all images of locations which visitors can expect to visit if they take part in a walking tour.

![Screenshot of some of the images on the site](assets/images/readme-images/images.png)
### Wireframes 
These were the original ideas for the three different sections:

Image of wireframe for mobile devices:
![Image of the wireframe for mobiles](/assets/readme-images/Mobile_Wireframe.png)
***
Image of wireframe for tablets:
![Image of the wireframe for tablets](/assets/readme-images/tablet_wireframe.png)
***
Image of wireframe for large screens:
![Image of the wireframe for large screens ](assets/images/readme-images/)
***


### Other
One unfortunate design feature... 

Other solutions, like hiding a div in the page above and addressing the link there, where discarded.
## Features
This site contain three different sections in a single html-page:
- Home page
- Gallery page
- Contact page
### General Features on each page
**The header** sticks at the top of the viewport and gives the visitor access to the navigation bar anywhere on the site. When using a tablet or smaller, the menu bar hides behind a menu icon.

The h1-heading changes the amount of rows it is dispensed on depending on which device you are using. It is designed to make it fit better on smaller / larger screens.

![Screenshot of the sites header](assets/images/readme-images/)

**The Home page** aims to give the visitor clear information about the walking history tours, including times and other considerations (e.g. accessibility).

![Screenshot of the sites landing page](assets/images/readme-images/)

**The Gallery page** is designed to give the visitor a preview of some of the historical sites they will visit in the course of the walk. There is some text to describe the various images, with the aim of encouraging viewers to visit the sites in person.

![Screenshot of the sites inspiration page](assets/images/readme-images/)

**The Contact page** is designed to engage visitors, giving them the option to make an enquiry or to sign up for newsletters or details of occasional related events.

![Screenshot of the sites recipe page](assets/images/readme-images/)

**The footer** contains links to Facebook, YouTube and Instagram to encourage visitors to keep in contact via social media.

![Screenshot of the sites footer](assets/images/readme-images/)

The site is responsive - the design changes to be more compatible depending on which screen size the visitor uses.
### Future Implementations
The site has an infinite number of possibilites to incorporate. Some features that are planned but not yet executed are:
- The possibility of a comments / review section. 
- The possibility of an additional page with images and information of seasonal / occasional tours which might interest visitors.


### Accessibility
The site is made to be accessible. Measures taken are:
- High colour contrast between backround and text
- Alt attributes on all images
- Aria labels on all icons

## Technologies Used

### Languages Used
This website has been created using HTML and CSS
### Frameworks, Libraries & Programs Used
Google Fonts -  For fonts

Git - For version control

Github - To save & store files and deployment

Gitpod - IDE used to write the code

Font Awesome - For icons used in header and footer

Balsamiq - For wireframes
## Deployment & Local Development

### Deployment
Github pages is used to deploy this site. To deploy the site yourself, follow these instructions:

- Sign in to Github
- Go to the repository for this project called [*walking-galway-history*](https://github.com/niallpcarroll/walking-galway-history.git)
- Click *settings*
- In the column to the left, click *pages*
- From the dropdown, select *main branch* and then save
- The site is now deployed!
### Local Development

#### How to Fork
To fork the repository:

- Log in to Github


- Go to the repository for this project called *walking-galway-history*

- Click the Fork button in the top right corner
#### How to Clone
- Log in (or sign up) to GitHub.

- Go to the repository for this project, [*walking-galway-history*](https://github.com/niallpcarroll/walking-galway-history.git).

- Click *Code* and choose whether you would like to clone with HTTPS, SSH or GitHub CLI and copy the link.

- Open the terminal in your code editor and change the current working directory to the location you want to use for the cloned directory.

- Type the following command in the terminal (after the git clone you will need to paste the link you copied in step 3 above):

      git clone { & THE LINK FROM STEP 3 }


## Testing
### Automated testing
#### W3C
I have used W3C validator to validate my HTML code and CSS code. I validated them via direct input.

Both passed without errors. The warning in the CSS validation was regarding imported imported stylesheets - in this case the Google Fonts stylesheet.

![Screenshot of the W3C website after it validated this sites HTML code](assets/images/readme-images/)


![Screenshot of the W3C website after it validated this sites CSS code](assets/images/readme-images/)
#### Lighthouse
Lighthouse is a tool created by Google to test a website's: Performance, Accessibility, Best Practices, SEO and Qualification as a Progressive Web Application.

It gives scores on the usability of the site. The test is done for a desktop version and a mobile version.

**The score for a mobile device:**

![Screenshot of the Lighthouse score for a mobile device](assets/images/readme-images/)


**The score for a desktop device:**

![Screenshot of the Lighthouse score for a mobile device](assets/images/readme-images/)

Overall the scores are good. For a mobile device, the performance is lacking a bit. This is mostly due to some images being larger than they need to be for a mobile screen.

#### WAVE
Wave is another tool to test the accessibility of the site. This is the result:

![Screenshot of WAVE score result after first test](assets/images/readme-images/)

After the first test there was an error. It was that the label element in the navbar did not av any text content (only the menu icon). An Aria label was later added and the error was corrected.

### Manual Testing
#### Features
Below is a table with the sites features, how it has been tested and what the outcome were.

|Feature|Test case|Outcome|
|---|---|---|
|Header |Scroll down through site |Sticks to top of viewport |
|Nav bar - Home |Click |Redirected to home page |
|Nav bar - Gallery |Click |Redirected to Gallery page |
|Nav bar - Contact |Click |Redirected to Contact page |
|Nav bar - Icon (tablets and smaller) |Click |Menu shows |
|Contact form - hidden |Click |Contact form shows |
|Contact form|Give the required information|Form is successfully sent|
|Contact form (desktop)|Scroll down through site|The Contact form sticks to top of viewport (under the header) inside Contact page|
|Contact form - submit button|Click|Submits form|
|Contact form - reseet button|Click|Resets form|
|Social media link - Instagram |Click |Redirected to Instagram |
|Social media link - Youtube |Click |Redirected to Youtube |
|Social media link - Facebook |Click |Redirected to Facebook |

#### Screen size compability
Below is a table with different devices and the outcomes when visiting the site using different screen sizes.

|Device|Site responsive <768px|Site responsive 768px to 991px|Site responsive 992px to 1919px| Site responsive >=1920px| Renders as expected |
|---|---|---|---|---|---| 
|Galaxy Fold |Good |N/A |N/A |N/A |Good |
|iPad Mini |N/A|Good |N/A |N/A |Good |
|Laptop (1366px wide) |N/A |N/A |Good |N/A |Good |
|Desktop (1920px wide) |N/A |N/A |N/A | Good|Good |

#### Browser compability
Below is a table with different browsers, how the site appears on them and how the sites responsiveness is on them.

|Browser|Intended appearance|Intended responsiveness|
|---|---|---|
|Chrome |Good |Good |
|Safari |Good |Good |
|Edge |Good |Good |
|Firefox |Good |Good |

## Credits

### Code Used
The following code where taken from Code Institutes *Love Running* project and later on adapted to this project.

```
  #menu-toggle {
        display: none;
    }

    #menu-toggle-label {
        font-size: 5rem;
        padding: 2rem 5rem 0 0;
        display: block;
    }

    #menu-toggle:checked~nav {
        display: block;
    }

    #menu-toggle:checked~label {
        display: none;
    }
 ```
    


### Content    


Remaining content is written by myself.
### Media
All images are licensed to use in commercial products. 
Images were taken from:

https://www.pexels.com
### Acknowledgments
Mentor


