## Universal Résumé Template

## What This Is

This is the repository housing my personal resume, which I host here: tmpname.dev/resume

## Source
Based on https://github.com/Thomashighbaugh/resume

<hr>

## How to run it
Clone the git repository 
```
git clone 'repo'
```

Navigate to the base directory:

```
cd resume
```

Install the dependencies:

```
npm install
```

Start the development server after building the stylesheet out of the Tailwind configuration:

```
npm build && npm serve
```

Only generate CSS that is used on the page which results in a much smaller file size:

```
npm build
```

<hr>

## Starting Point

`docs/index.html` is the main content file. By copying HTML: add pages, sections, subsection, and other parts.

`npm run build` enables drag and drop support of the `docs` directory, which you find helpful unloading your copy on GitHub if terminal/command prompt is not your thing. 


## Custom CSS

Code from `tailwind.config.js` and `tailwind.css` transpiles to `docs/style.css`.

<hr/>

## Balanced Columns

Removing `col-fill-auto` class will make both columns equally tall. Moreover, removing `md:h-letter` and `md:h-letter-col` classes will eliminate fixed proportions of the letter or A4 page — thereby removing unnecessary vertical space when displaying short columns.

<hr/>


## Printing

### Chrome

Right-click → Print.  

OR 

You can save it as a PDF which will probably keep the SVG image and the other things being stripped out by the print optimizations, but there are use cases for that as well and its not like there really is a `right way` 

------

### Firefox

File → Print.

### Adobe Acrobat Reader

File → Print.

By clicking on the **Page Setup** button, you are taken to the window with A4 and Letter options.



