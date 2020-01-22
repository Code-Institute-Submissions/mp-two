# 360 Park Finder

We all love to explore and discover new things, especially new places. This project allows skateboarders, BMXers, scooters, or anything of the like to do just that. Park users can begin their journey with 360 Park Finder!

Users can easily search the globe for new and exciting parks to be explored. Users can be travelling and looking for a fresh new park to discover or users can be interested in expanding on their local spots.

## UX

Please see the wireframes used for prototyping the UI/UX design in the "assets/planning" directory.

This project is a tool for discovery. It's clean design and colour scheme, inspired by the trending 'dark theme', allows users to effortlessly reach a new destination by searching for a location or browsing the entire map, provided by Google Maps APIs.

### User Stories

As a kid moving across the country this summer. I want to be able to enter my new address and find any parks close by so that I can meet other BMXers. They might even be at my new school.

As someone who hasn't been on their 'board in over a decade. I'd like to find any local parks near my new home. As I'm needing a new hobby to lose some weight. 

## Features

### Included Features

* Navigation
    - The navigation is responsive and will tuck away neatly on screens narrower than 992px.

* Help modal
    - Users can access a short but detailed list explaining the steps to achieving their needs. This information is resting in a modal that slides on top of all other content. 

* Landing
    - The landing page is clean, only showing a welcome message and call to action button.

* Search
    - Users can search for a location in the input field. The most relevant matches to the users search string will be displayed in a drop-down list. 

* Map
    - Users will be shown on the map the location they have searched, highlighted by the orange marker. Alternatively users can browse the map freely to explore, or drag the orange marker for address information. 

* Park markers
    - There is already a comprehensive list spanning multiple continents of parks to discover, highlighted by blue markers. Upon click/tap the address information will be displayed if present.

* Footer
    - Social links can be found comfortably sitting at the bottom of all pages.

### Future Features

There are multiple features that have not been implemented to date. A richer understanding and more experience of back-end technologies is essential for the following features:

* User Account
    - A simple account that would allow users of the project to identify themselves and store favourite parks.

* User Content
    - Users would be able to add new parks, add their own reviews and star ratings. 

* User Forum
    - A forum for users to meet new park users or discuss matters of importance.

## Technologies Used

* HTML5 & CCS3: Essential languages used to build a websites foundations.

* Bootstrap: An easy to use, responsive framework. Bootstrap was used to allow easy implementation of the responsive and collapsible navigation. Bootstrap's grid system was also used for simplicity and efficiency.

    - https://getbootstrap.com/

* Font Awesome: A vast and free library of responsive icons. This library was used for the social link icons found in the footer. The search icon is also sourced on Font Awesome.

    - https://fontawesome.com/

* Google Maps API: Multiple Google Maps APIs were used. Google Maps JS API to allow the map to display and interactable. Google Places API to allow for the drop-down list of possible search locations. Google Geocoding API to allow for the processing of the search. From search location name/address to coordinates for the map. 

    - https://developers.google.com/maps/documentation

* JS and jQuery: These technologies were essential for the function of the Google Maps APIs, to allow Bootstrap to collapse the menu, and to allow Bootstap to display/hide the help modal.

    - https://jquery.com/

## Testing

The website was hosted locally and bugs or unintended behaviors were identified and resolved to the best of my abilities. The code was then pushed to GitHub periodically and hosted on a GitHub page where the site could be accessed on different physical devices. Identifying compatibility issues or any further unintended behaviours with different view ports.

Unintentional behaviour has been identified in the following scenario; When a user types out a new location string and selects their preferred match from the drop-down list. The map resorts to the initial load state of location and zoom. Until the user clicks/taps the search button. Where the request is fulfilled and the map centers on the new location. 

### https://www.freeformatter.com/html-validator.html

Found 2 issues!

The element “button” must not appear as a descendant of the “a” element.
From line 114, column 44 to line 114, column 89

Malformed byte sequence: “a9”.
At line 140, column 52

These issues were quickly resolved allowing the project to conform to best practices and standards.

## Deployment

As the site was already version controlled by Git and GitHub, I felt that the best course of action would be to take advantage of GitHub's GitHub Pages functionality, which allowed me to deploy the website without needing any further deployment tools, or methods.

I still don't fully understand how to deploy the project to the production environment. This will require further study. 

## Credits

The logo was designed in the planning stage on Adobe Xd.

The Google Maps API javascript code was sourced from: 

- https://www.codexworld.com/autocomplete-location-search-box-google-maps-javascript-api-jquery-ui/

The code used to import the KML file for the database of existing parks was sourced from:

- https://developers.google.com/maps/documentation/javascript/kml

## My Comments

I received feedback from my last project about the volume of my git commits. I have fallen into this bad habit again, of not performing "a larger number of micro commits". This will have to be a focus of my next project. Along with a better understanding of what it takes to document and deploy a project to a production environment.