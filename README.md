
# UDEMY COURSE - BOOTSTRAP PROJECT 1

## Go to the Project Page
❗ https://gulcanc.github.io/Bootstrap-1/

## The Purpose of the Project
💦 Learning and creating high quality Bootstrap 4 theme and UI from scratch

💦 Learning the Bootstrap 4 utilities, classes, components & JS widgets using a custom sandbox environment

💦 Learn semantic HTML5 & modern CSS3 techniques

## About the Project

This project is a fully responsive social media type site. We have a fixed navbar at the top, after that there is a home container which is a main show case area with a background image. This section containes the texts with icons and a form. After home section there are 3 sections (explore, create and share) that each of them a header and body section. Finally, there is a footer at the end of the page. 

## Techniques Used 

We add a navigation menu to the navigation bar using an unordered list of clickable list items with different "IDs". We use a button for the navigation menu so that the navigation menu is properly displayed on the small screen.

       <button
          class="navbar-toggler"
          data-toggle="collapse"
          data-target="#navbarCollapse" >
          <span class="navbar-toggler-icon"></span>
        </button>

**⚡ Home Section** 

At the show case area we use flex box to align the texts and the icons. **d-flex** is used for the parent elements and it automatically aligns items horizantally. **align-self-start** and **align-self-end** are used for the child elements to individually change their alignment on the cross axis. For the texts, we use **col-lg-8** class name for large screens, while for small screens we use **d-none** which means we do not want the texts are dipslayed in small screens. For this section, we use dark overlay its **position is absolute** that means we want it basically covers the entire home section. 

For form we use **card-form, form-group, form-control** class names. 

**⚡ Explore, Create and Share Sections** 

These three sections have a header section that contains a title, a paragraph and a button. Under the header section, they have a container that includes 6 columns div **col-md-6** for medium screens, under below the medium screens, these two div elements stack on top of each other. Here, first div is the image and we use **img-fluid** class so that it fits inside the container for different sizes.  The second div contains a title, a paragraph and the icons with texts. 

**⚡ Footer Section**

In the footer we have a contact button; when we click this button, a modal will be opened. Here we use **data-toggle**, **data-target** class names. We have to add the content of this modal outside of the footer. Here we add a button to close the modal and we use the property/value pairs **class="close"**, **data-dismiss="modal"**.

**⚡ Smooth Scrolling**

To the body section we add **data-spy="scroll"**, **data-target="main-nav"** and **id="home"**. After that, we use javascript to init scrollspy for smooth scrolling.


