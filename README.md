# Build a Static Web Page Using HTML, CSS, and Bootstrap

This is a responsive website and I make it using front-end library bootstrap.

# Stuffs used in this website:
HTML5,
CSS3,
BOOTSTRAP,
Font awsome for icons,
Google fonts 

# Speciality:
use of fixed background(wrap),
use of cards responsively,
use of carousel with carousel caption,
responsive navabars


# In The HTML & Bootstrap Part: 


# Document Setup:
The document begins with the <!DOCTYPE html> declaration, specifying HTML5 as the document type.
The <html> element sets the language attribute to English (lang="en").
The <head> section includes meta tags for character encoding (utf-8) and viewport settings for responsive design.
Bootstrap CSS, FontAwesome icons, and a custom stylesheet (style.css) are linked for styling.

# Navbar:
A responsive navigation bar is implemented using Bootstrap classes, with links to different sections of the page (e.g., Home, About, Services, Team, Contact).
The navbar includes a brand logo and a toggle button for mobile view.

# Carousel/Slider:
The carouselExampleCaptions component is a Bootstrap image slider with indicators and captions.
It contains three slides, each with background images and text overlays (e.g., "Bootstrap" and "Complete Website Layout").

# Jumbotron:
A large, full-width section (jumbotron) introduces a brief description of web hosting services, accompanied by a "Web Hosting" button.

# Welcome Section:
This section includes a welcoming message (Built with ease) and a brief introduction to the website and Bootstrap.

# Three Column Section:
Three columns highlight different technologies used in the website (HTML5, Bootstrap, CSS), each with an icon and brief description.

# Two Column Section:
A two-column layout showcases information about responsive web design, with text on one side and an image on the other.

# Fixed Image Background:
A section designed for a visually striking, fixed background image.

# Meet the Team:
A card-based layout introduces three team members, each with a profile image, name, brief bio, and a link to their profile.

# Philosophy Section:
Another two-column layout explains the website's philosophy with text and an image side by side.

# Connect Section:
Social media icons link to various platforms (GitHub, LinkedIn, Google+, Kaggle, YouTube), allowing users to connect with the website's creator.

# Footer:
The footer provides contact information, service hours, and service areas. It also includes the company logo and a copyright notice.

# Scripts:
The document ends with scripts for Bootstrap and Popper.js to enable interactive features, like the carousel and navbar toggle.

This page uses Bootstrap's grid system and utility classes to create a responsive, professional-looking layout. The structure is designed for ease of navigation and clear presentation of information, with a focus on responsiveness and user interaction.


# In The CSS Part: 


# Font and Body Styling:
The @import rule imports the "Montserrat" font from Google Fonts.
The html and body selectors apply this font across the entire website, along with setting the color to a dark grey (#222).

# Scroll to Top Button:
up class positions a button fixed near the bottom of the viewport, allowing users to scroll back to the top.

# Navbar:
navbar adds padding to the navigation bar.
navbar-nav li adds spacing between navigation items.
nav-link customizes the font size of the links.

# Carousel:
carousel-inner .im1, .im2, .im3 apply background images and set the height to full viewport height, making the carousel images cover the entire screen.
carousel-caption centers the caption text vertically within each carousel item, with large text sizes and shadow effects.
Media queries adjust the font sizes and layout for smaller screens, ensuring text remains readable on mobile devices.

# Buttons:
btn-primary customizes the primary button color and border, with hover effects changing the color slightly.

# Jumbotron:
jumbotron adds padding and sets a light background color, making it distinct from the rest of the content.

# Icons and Cards:
Font Awesome icons are styled with specific colors and sizes for tech-related icons and social media icons.
card class ensures cards fill their container's height.

# Footer:
The footer has a dark background with light text, maintaining readability.

# Media Queries:
Specific breakpoints are defined for screens wider than 1200px, 768px, and 576px, adjusting the layout and font sizes to ensure a responsive design.

# Carousel Transition:
carousel-item ensures smooth transitions between slides.

Overall, the CSS aims to create a visually appealing and responsive website, with a focus on consistent branding through typography, color schemes, and spacing across different screen sizes.
