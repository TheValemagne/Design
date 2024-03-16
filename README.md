# Angular Project #

This is a two-week made with [Johanne Kirsch](https://github.com/johanna-kirsch) in 2022 for the mobile web developement durent our bachelor's degree at the ISFATES/DFHI in Metz, France. The main goal was to create a responsive web page for a topic of our choice using Angular. As it is only a programming exercise, the focus was on the correct utilization of Angular and Typescript as well as the implementation of forms, navigation and responsive elements. The application could be started with Docker or with ng serve.

How to run this application with Docker:
- Install dependencies: ``npm install``
- Build project: ``npm run build``
- Create a docker image: ``docker build -t ng-star-wars .`` or load the provided image: ``docker load < star_wars_image.tar``
- Run it: ``docker run -d -p 1234:80 ng-star-wars``
- Open locally with ``http://localhost:1234/``

# Note #
The text is in french

# Credits #
The application uses a droid loader that gets displayed before the quiz results, which was taken from [this CodePen project](https://codepen.io/franksLaboratory/pen/mdyewbW) by Frank's Laboratories, licensed under the MIT license and therefore free of use.
