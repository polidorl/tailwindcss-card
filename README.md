# Frontend Mentor - Results summary component solution
 
 ## The challenge
 In this challenge from Frontend Mentor (https://www.frontendmentor.io), we are challenged to build the 'Results summary component' using HTML and the Tailwind CSS framework. The main goal is to demonstrate the use of the Tailwind CSS framework by re-creating the layout provided in the /design folder, ensuring that the component is fully responsive.

 En este desafío de Frontend Mentor (https://www.frontendmentor.io), se nos reta a construir el componente 'Results summary component' utilizando HTML y el frameworks Taiwindcss. El objetivo principal es demostrar el uso del frameworks  de Tailwind CSS al re-crear   el diseño proporcionado en la carpeta /design, asegurando que el componente sea completamente responsivo.

Your users should be able to:

- View the optimal layout for the interface depending on their device's screen size

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Where to find everything](#where-to-find-everything)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Sharing your solution](#sharing-your-solution)
  - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

## The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Where to find everything

Your task is to build out the project to the designs inside the `/design` folder. You will find both a mobile and a desktop version of the design. 

The designs are in JPG static format. Using JPGs will mean that you'll need to use your best judgment for styles such as `font-size`, `padding` and `margin`. 

All the required assets for this project are in the `/assets` folder. The images are already exported for the correct screen size and optimized.

We also include variable and static font files for the required fonts for this project. You can choose to either link to Google Fonts or use the local font files to host the fonts yourself. Note that we've removed the static font files for the font weights that aren't needed for this project.

There is also a `style-guide.md` file containing the information you'll need, such as color palette and fonts.


### Links

- Solution URL:  https://github.com/polidorl/tailwind-card
- Live Site URL:  https://polidorl.github.io/tailwind-card.git/

## My process

### Built with

- Semantic HTML5 markup
- Frameworks Tailwindcss
- Mobile First

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

## Sharing your solution

There are multiple places you can share your solution:

1. Share your solution page in the **#finished-projects** channel of the [community](https://www.frontendmentor.io/community). 
2. Tweet [@frontendmentor](https://twitter.com/frontendmentor) and mention **@frontendmentor**, including the repo and live URLs in the tweet. We'd love to take a look at what you've built and help share it around.
3. Share your solution on other social channels like LinkedIn.
4. Blog about your experience building your project. Writing about your workflow, technical choices, and talking through your code is a brilliant way to reinforce what you've learned. Great platforms to write on are [dev.to](https://dev.to/), [Hashnode](https://hashnode.com/), and [CodeNewbie](https://community.codenewbie.org/).

We provide templates to help you share your solution once you've submitted it on the platform. Please do edit them and include specific questions when you're looking for feedback. 

The more specific you are with your questions the more likely it is that another member of the community will give you feedback.


### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

## Author

 polidor.lisbeth4@gmail.com
linkedin/lisbeth-emperatriz-polidor-solano

## Acknowledgments

https://www.youtube.com/watch?v=Pxs2WKdvBRU&t=395s
Como crear un Proyecto desde cero con Tailwind.(Responsive)
AlexCGDesign

En el archivo package.json tenemos el script que se ejecuta en el terminal para
generar el CSS optimizado con la purga aplicada o el flag --minify
```
 "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "tw:build": "ENV=PRODUCTION npx tailwindcss -i ./src/css/tailwind.css -o ./src/css/estilos.css --minify",
    "tailDev": "npx tailwindcss -i ./src/css/tailwind.css -o ./src/css/estilos.css --watch"
  },
  ```