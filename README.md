
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

**HOME SECTION** 

At the show case area we use flex box to align the texts and the icons. **d-flex** is used for the parent elements and it automatically aligns items horizantally. **align-self-start** and **align-self-end** are used for the child elements to individually change their alignment on the cross axis. For the texts we use **col-lg-8** class name for large screens, while for small screens we use **d-none** which means we do not want the texts are dipslayed in small screens. For this sectionwe use dark overlay its **position absolute** that means we want it basically covers the entire home section. 

For form we use **card-form, form-group, form-control** class names. 

