# Grubby
Provides convenient links and combined README for the Grubby the Grape website.

Repository for the Front-End: https://github.com/CoryMut/GrubbyFrontEnd  
Repository for the Back-End: https://github.com/CoryMut/GrubbyBackEnd

Hello! This repository was made to provide a convenient way to learn about the Grubby the Grape website without needing to go to the other repositories (since I decided to seperate the back and front end code entirely).

If you would like to view the code or seperate README files for either section, the links are provided above.

Grubby the Grape is a character made by my brother (@TheFantasticIan on Twitter) who stars in a series of comics he makes in his spare time. There are over 180 comics currently, and I thought it would be cool to make a place for theme to be shown in one convenient place, rather than on a thread on Twitter. The original website I made can be viewed here: https://www.grubbythegrape.com/ but it was pretty buggy and not written well (I made this prior to being a student at Springboard). Thus, I thought a redesign with more features would be a great way to show how far I have come.

Unauthenticated visitors to the site can view the latest comic, view and search for all the comics in the series, and ask Grubby for infinite dad jokes. Users that decide to make an account can addionally add comics to their favorites as well as react to the latest comic by selecting one of several supported emojis.

Authorized visitors (admins) can upload comics. This was something I wanted to get right, as it was a major sticking point on the previous version of this site. The comic is first resized to a bunch of different sizes (to be used in the front-end via srcSet) with the goal of making the site more performant. Each resized image is then sent to a CDN hosted by DigitalOcean. Meanwhile, the user is provided with status updates for each step and is provided a clear error message communicating which step of the process caused an error.

New features will continue to be added, including an eventual transfer to the regular grubbythegrape domain. If you have any feedback or questions or a great idea of something to add, I can be reached at cory@corymutchler.com

Stack:
- React
- Node.js
- Express
- PostgreSQL
- DigitalOcean Spaces (CDN for images)
- Jest (Testing)
- Hosted Using: DigitalOcean App Platform

