D1 Web Shop – Code Challenge

24-Hour Frontend Implementation

This project is my implementation for the D1 Web Shop Homepage based on the design provided in the Sketch mockup.
The goal was to translate the wireframes into a pixel-perfect, responsive, scalable, and maintainable front-end using Foundation Sites, SCSS, and modern web best practices.

Requirements Completed

Build the homepage exactly from the provided wireframe
Fully implemented the D1 homepage layout
All typography, spacing, and layout matched to design as closely as possible
All assets extracted from the Sketch file and optimized

responsive
Mobile and desktop support
Section-level responsive SCSS using breakpoint mixins
Flexible layout with proper spacing and stacking behavior

Foundation Framework used
Installed using the Foundation starter template

<<<<<<< HEAD

SCSS Architecture
Modular component-based SCSS
Variables, mixins, and breakpoints created for maintainability
Avoided inline styles or CSS clutter

scss/
\_settings.scss // Foundation settings
\_variables.scss // Colors, fonts, spacing, radius, breakpoints
\_mixins.scss // Flex utilities, responsive mixins
\_global.scss // Reset + base styles
\_header.scss // Topbar, navbar
\_hero.scss // Hero section
\_top.scss // All main sections after hero
\_footer.scss // Footer section
app.scss // Main compiled SCSS importing all above

Tech Stack
Front-End

HTML5
CSS3 / SCSS
Foundation 6
JavaScript (minimal)
Build Tools
Gulp
Dart Sass

Folder Structure
├── assets/
│ └── images/ # Exported images & icons from Sketch
│
├── scss/
│ ├── \_header.scss
│ ├── \_hero.scss
│ ├── \_top.scss
│ ├── \_footer.scss
│ ├── \_variables.scss
│ ├── \_mixins.scss
│ ├── \_settings.scss
│ ├── \_global.scss
│ └── app.scss
│
├── js/
│ └── app.js
│
├── index.html
├── gulpfile.js
├── package.json
└── README.md

Installation & Running Locally

1. Clone the repository
   git clone https://github.com/johnrenelle2930/code-challenge-payumo.git

2. Install dependencies
   yarn install

3. Start the development server
   yarn start

This will compile SCSS, watch for changes, and spin up a local dev environment.

Notes

=======
SCSS Architecture
Modular component-based SCSS
Variables, mixins, and breakpoints created for maintainability
Avoided inline styles or CSS clutter

scss/
\_settings.scss // Foundation settings
\_variables.scss // Colors, fonts, spacing, radius, breakpoints
\_mixins.scss // Flex utilities, responsive mixins
\_global.scss // Reset + base styles
\_header.scss // Topbar, navbar
\_hero.scss // Hero section
\_top.scss // All main sections after hero
\_footer.scss // Footer section
app.scss // Main compiled SCSS importing all above

Tech Stack
Front-End

HTML5
CSS3 / SCSS
Foundation 6
JavaScript (minimal)
Build Tools
Gulp
Dart Sass

Folder Structure
├── assets/
│ └── images/ # Exported images & icons from Sketch
│
├── scss/
│ ├── \_header.scss
│ ├── \_hero.scss
│ ├── \_top.scss
│ ├── \_footer.scss
│ ├── \_variables.scss
│ ├── \_mixins.scss
│ ├── \_settings.scss
│ ├── \_global.scss
│ └── app.scss
│
├── js/
│ └── app.js
│
├── index.html
├── gulpfile.js
├── package.json
└── README.md

Installation & Running Locally

1. Clone the repository
   git clone https://github.com/johnrenelle2930/code-challenge-payumo.git

2. Install dependencies
   yarn install

3. Start the development server
   yarn start

This will compile SCSS, watch for changes, and spin up a local dev environment.

Notes

> > > > > > > 90f5c79 (Updated ReadME)
> > > > > > > All assets were exported from the provided Sketch mockup.
> > > > > > > Layout and spacing were matched according to the design.
> > > > > > > Code is structured with scalability in mind to accommodate future pages and components.
