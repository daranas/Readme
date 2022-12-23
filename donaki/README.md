# Donaki

This website is a static page that has been optimized using Gulp to minify CSS & JS files to make the website loading faster and lighter.

## Application Structure  
```
/
├─ assets/
│  ├─ css/          # Contains CSS (Cascading Style Sheet) files
│  ├─ images/       # Contains Image files
│  └─ js/           # Contains JavaScript files
└─ dist/            # Contains your compiled assets
```

## Installation

Donaki requires [Node.js](https://nodejs.org/) v10+ to run.

Install the dependencies and devDependencies.

```sh
npm install
```

To execute automation tasks

```sh
gulp build
```
after the build is complete you can check the optimized website files in the dist folder

## Library & Tools

Donaki is currently extended with the following library & tools.
Instructions on how to use them in your own application are linked below.

| Plugin | README |
| ------ | ------ |
| Bootstrap | https://github.com/twbs/bootstrap |
| OwlCarousel | https://github.com/OwlCarousel2/OwlCarousel2 |
| jQuery | https://github.com/jquery/jquery |
| Gulp | https://github.com/gulpjs/gulp |