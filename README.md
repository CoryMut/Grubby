# Grubby
Provides convenient links and combined README for the Grubby the Grape website.

Repository for the Front-End: https://github.com/CoryMut/GrubbyFrontEnd  
Repository for the Back-End: https://github.com/CoryMut/GrubbyBackEnd

Hello! This repository was made to provide a convenient way to learn about the Grubby the Grape website without needing to go to the other repositories (since I decided to seperate the back and front end code entirely).

If you would like to view the code or seperate README files for either section, the links are provided above.

Grubby the Grape is a character made by my brother (@TheFantasticIan on Twitter) who stars in a series of comics he makes in his spare time. There are over 180 comics currently, and I thought it would be cool to make a place for theme to be shown in one convenient place, rather than on a thread on Twitter. The website can be viewed here: https://www.grubbythegrape.com/

Unauthenticated visitors to the site can view the latest comic, as well as flip through them chronologically. There is also an all comics section, that allows users to search for a specific comic. Users that decide to make an account can addionally add comics to their favorites as well as react to the latest comic by selecting one of several supported emojis.

Authorized visitors (admins) can upload comics. This was something I wanted to get right, as it was a major sticking point on the previous version of this site. The comic is first resized to a bunch of different sizes (to be used in the front-end via srcSet) with the goal of making the site more performant. Each resized image is then sent to a CDN hosted by DigitalOcean. Meanwhile, the user is provided with status updates for each step and is provided a clear error message communicating which step of the process caused an error.

There are basic tests for the pivotal routes and components, but plans are underway to expand these tests and add some form of continuous integration.

New features will continue to be added. If you have any feedback or questions or an idea of something to add, I can be reached at cory@corymutchler.com

Stack:
- React
- Node.js
- Express
- PostgreSQL
- DigitalOcean Spaces (CDN for images)
- Jest (Testing)
- Hosted Using: DigitalOcean App Platform

