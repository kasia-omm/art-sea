# Welcome ArtSea [*place link*](ArtSea) 
### ArtSea was created from the need of crafting 

<!-- create table of contents -->

# List of Features

The purpose of this web page is to give user details about services provided by ArtSea, Sligo based art and craft party provider and organiser. <br>
The ArtSea website is designed allowing three pages: index.html representing Home Pahe, services.html page representing the Services breakdown offered by ArtSea and contact.html allowing for submission Contcat Us form page. Below you will find a list of features for each page.

<strong>The Home page consists of:</strong>

<ol>
    <li>Logo - name ArtSea with icon of a painter's palette</li>
    <li>Menu</li>
<ul>
        <li>Home - the main landing page</li>
        <li>Services - breakdown of party packages on offer</li>
        <li>Contact Us - form for user to fill out</li>
</ul>
    <li>Hero Image - relevant to the business and theme of the website image with text overlay box and repsonsive button</li>
    <li>Introduction - short paragraph inviting users to check out the content of Services Page</li>
    <li>Four buttons that redirect the user to the relevant section of the Services Page</li>
    <li>Small gallery - indication of types of art and craft activities on offer</li>
    <li>Footer - breakdown of essential information relating to ArtSea such as:
<ul>
        <li>Business logo (name) and address
        <li>Contact Details: redirection to the Contact Us page, Telephone Number and E-mail Address</li>
        <li>Social Media Icons linking to ArtSea social media pages</li>
        <li>Site Map - liks to each page for ease of use</li>
</ul>
</ol>

<strong>The Services page consists of:</strong>

<ol>
    <li>Logo - name ArtSea with icon of a painter's palette</li>
    <li>Menu</li>
<ul>
        <li>Home - the main landing page</li>
        <li>Services - breakdown of party packages on offer</li>
        <li>Contact Us - form for user to fill out</li>
</ul>
    <li>4 sections - each describing party packages on offer (this section may be expanded as business grows and changes, keeping the same format)</li>
        Section features include:
        <ul>
            <li>text area</li>
            <li>text area with gallery</li>
            <li>gallery section with image width of 300px, height will be automatically set to fit the space provided</li>
            <li>embeded videos</li>
        </ul>
    <li>Footer - breakdown of essential information relating to ArtSea such as:
<ul>
        <li>Business logo (name) and address
        <li>Contact Details: redirection to the Contact Us page, Telephone Number and E-mail Address</li>
        <li>Social Media Icons linking to ArtSea social media pages</li>
        <li>Interactive Map - showing location of the business with possibility of generating directions through Google Maps</li>
</ul>
</ol>

<strong>The Contact Us page consists of:</strong>

<ol>
    <li>Logo - name ArtSea with icon of a painter's palette</li>
    <li>Menu</li>
<ul>
        <li>Home - the main landing page</li>
        <li>Services - breakdown of party packages on offer</li>
        <li>Contact Us - form for user to fill out</li>
</ul>
    <li>One section where 50% is allowed for an image and 50% is allowed for a Contact us form</li>
    <li>Form includes the following fields:</li>
    <ul>
        <li>First Name - required field</li>
        <li>Second Name - required field</li>
        <li>Mobile Number - required field</li>
        <li>Email Address - required field</li>
        <li>Dropdown list of party options to choose from</li>
        <li>Texarea - allowance of 30 columns and 10 rows</li>
        <li>Responsive Submit button - after user clicks submit, thank you message appears</li>
    </ul>

# UX/UI

## Site Goals

## Design choices

The design of the website focused on the art and craft part of the business choosing lively colours and images.

<ol>Theme colors:</ol>
<li>Header and Footer - #41B3A3</li>
<li>Sections title backgrounds - #C38D9E</li>
<li>Button background - aliceblue </li>
<li>Text color - #000F04</li>
<li>Bold text - #384955</li>

<span width="100" height="100">![ArtSea_Color_Palette](/assets/images/ArtSea_color_palette_smaller.png)<span>

## User Stories

User experience:

Persona 1 - Parent that wants to organise a birthday party for his/her child, living in Sligo or thin 30 min drive. He/She is looking for party where kids' creativity will be used to have time with their friends and create something they can bring home. The parent is looking for a party where all supplies are provided and minimum effort is required. They want to be able to book the party shortly after consulting the webpage. 

Persona 2 - Birthday party organiser for partner, friend, parent, children where the birthday is round such as  18th, 21st,30th, 40th, 50th, 60th, 70th, etc. They are looking for party with a twist where the group will spend quality time together, making a piece of art and craft and have fun by possibly destroying it in the Craft and Destroy Room. Suitable for non-drinkers, creative people or those that prefer non-physical activities. Quality time with their party is more important than going out. They are looking for package with meal - allow partner discounts for local restaurant. 

Persona 3 - Stag and Hen party oraniser, typically brother, sister of best friend. They are looking for a fun, different stag or hen party with the emphasis on 

First time user knows that the website is about art and craft birthday party organiser.
First time user learns about services provided by ArtSea.
First time user is called to action - to book a party.
Firts time user finds contact details to make booking easily.

## Wireframes

# Testing

### Bug 1
After adding content that was copied from index.html page to  services.html page, the services.html stopped working as per screenshot below:

![Bug 1](/assets/images/bug1.png)

Bug was fixed by temporarily commenting out code copied from main page info section in the services.html section. I then realised that the codes for the <nav></nav> section contained spaces and services.html page name started with Capital letter. After correcting all those, services.html page started working again.

![Bug 1 Fixed](/assets/images/Bug1_Fixed.png)

<em>Note: I realised that website is not deployed and link is breaking each time I open the portal. This bug will need to be fixed once the website is deployed.</em>

<em>Note: After brainstorming with mentor, I came to the conclustion that I shouldn't be using a full http link to the page where user should be directed to, but a relative link instead. Correcting this issue resolved the problem with link breaking.</em>

### Bug 2 

I realised that I downloaded the largest images rather than small so I needed to replace exising images in the assets/images folder to smaller.

### Bug 3 

On main page when I clicked on Lets's party! button, it was opening page in a separate tab but with error 404: File not found as per image below. I fixed it by correcting href link as services.html page name changed from Capital letter to small letter. 

# Deployment

# Citation of All sources
Images Photo by <a href="https://unsplash.com/@pawel_czerwinski?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Pawel Czerwinski</a> on <a href="https://unsplash.com/s/photos/wave-art?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>

Photo by <a href="https://unsplash.com/@pawel_czerwinski?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Pawel Czerwinski</a> on <a href="https://unsplash.com/s/photos/wave-art?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>

Photo by <a href="https://unsplash.com/@szamanm?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Piotr Musioł</a> on <a href="https://unsplash.com/s/photos/wall-drawing?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>

Zdjęcie dodane przez Sharon McCutcheon: https://www.pexels.com/pl-pl/zdjecie/dzieci-wielobarwne-farby-reczne-1148998/ 

Photo by <a href="https://unsplash.com/@emily_webster?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Emily Webster</a> on <a href="https://unsplash.com/s/photos/crafting-people?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>

https://blog.logrocket.com/five-cool-css-header-styles-with-cross-browser-compatibility/ 

<a href="https://www.flaticon.com/free-icons/wave" title="wave icons">Wave icons created by Freepik - Flaticon</a>

Photo by <a href="https://unsplash.com/@daniellajardim?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Ella Jardim</a> on <a href="https://unsplash.com/s/photos/crafting?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>

Photo by <a href="https://unsplash.com/@micheile?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">micheile dot com</a> on <a href="https://unsplash.com/s/photos/crafting?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>

Photo by <a href="https://unsplash.com/@grant_durr?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Grant Durr</a> on <a href="https://unsplash.com/s/photos/clay-painting?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>

Photo by <a href="https://unsplash.com/@lavievagabonde?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Jasmin Schreiber</a> on <a href="https://unsplash.com/s/photos/crafting?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  
Photo by <a href="https://unsplash.com/@jonathanborba?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Jonathan Borba</a> on <a href="https://unsplash.com/?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>

https://www.w3schools.com/howto/howto_js_topnav.asp

Photo by Vanessa Loring: https://www.pexels.com/photo/children-doing-crafting-7869797/

Photo by Monstera: https://www.pexels.com/photo/happy-black-girl-with-colorful-crown-with-pompoms-7139982/

Photo by <a href="https://unsplash.com/@ibrahimboran?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Ibrahim Boran</a> on <a href="https://unsplash.com/s/photos/birthday-party-art?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  
Photo by <a href="https://unsplash.com/@taelynnmae?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Taelynn Christopher</a> on <a href="https://unsplash.com/s/photos/birthday-party-art?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  
  Photo by <a href="https://unsplash.com/@timmossholder?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Tim Mossholder</a> on <a href="https://unsplash.com/s/photos/birthday-party-art?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>

  Photo by Teona Swift: https://www.pexels.com/photo/folded-fabric-with-colorful-paints-on-white-background-6850777/

  Photo by <a href="https://unsplash.com/@khachiksimonian?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Khachik Simonian</a> on <a href="https://unsplash.com/s/photos/wings-art?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  
  
# Future Features

Suggested future features:
<ul>
    <li>Testimonial Page - reviews and testimonials received from users, possible link to Trustpilot if used</li>
    <li>Gallery page - Expand gallery by adding more photos from hosted parties</li>
    <li>Suppliers' section - showcase trusted suppliers by including their logos with link to their online stores, possibility to add affiliate links</li>
    <li>Places to Stay - partner up with local hotels/Airbnbs and offer dicsounted accomodation</li>
</ul>

# Summary