# ICA 7: Bootstrap and some Icons
## Introduction
This ICA is designed to introduce you to the world of CDNS, how they work, and to help you get familiar with Bootstrap native elements, the Bootstrap grid system, and Font/Icon CDNs. You will be using Bootstrap to create a simple web page with an array of native elements and use your choice of icons from either Font Awesome or Google Fonts. You will also use a font family from Google Fonts to style the typography of your website.

> [!IMPORTANT]
> You will be adding a lot of "static" default elements to your webpage for the purpose of learning how the Bootstrap framework works. You will need to edit the content of these elements to a reasonable degree to make your webpage "your own". This means you may choose to add your own text, images, and other content to the elements you add to your webpage. How much you change the content is up to you, but you should aim to make your webpage look like a unique and cohesive design.

## Instructions
### Q1. Link Bootstrap to the ica7.html file
Adequate instructions for this question can be found in the Bootstrap documentation [here](https://getbootstrap.com/docs/5.3/getting-started/introduction/). You will need to link the Bootstrap CSS and JavaScript files to your HTML file. You can use the Bootstrap CDN to link the files to your `ica7.html` file.

> [!IMPORTANT]
> The Bootstrap documentation says to put the javascript link at the end of the body tag. While this is a good practice, it's preferable to put it in the head tag. You can do so by adding the `defer` attribute to the script tag. This will make the browser load the script after the page has been parsed (equivalent to putting it at the bottom of the `<body>` element).

### Q2. Add a Bootstrap Navbar
Bessides a `hero` section, the navigation bar is one of the most important elements of a website. It is the first thing a user sees when they visit your website. It is important to make sure the Navbar is visually appealing and easy to use.

Navigate to the Bootstrap documentation to find a a Bootstrap Navbar to add to your `ica7.html` file. You can use any of the Navbar examples provided in the documentation. You can also customize the Navbar to your liking. Make sure to add the Navbar to the top of your `ica7.html` file and configure the links in the Navbar to have navigable functionality on your page.

### Q3 - Q6. Add your choice of four Bootstrap elements
Choose any four Bootstrap elements to add to your `ica7.html` file. In my opinion, the Bootstrap elements `Collapse`, `Card`, `Carousel`, `Scrollspy`, and `Accordion` are likely some of the most effective elements to learn the Bootstrap framework; however, pick any combination of elements you like. Customize the elements to however you feel best fit the webpage.

> [!TIP]
> It's often a good idea to use a combination of elements that work well together. For example, you could use a `Carousel` element to display pictures about a product, and then use a `Accordion` element to display information snippets of each product. This would create a cohesive and visually appealing section of your webpage.

### Q7. Create an HTML user `<form>` using the Bootstrap grid system
You will need to create a form using the Bootstrap grid system. The form should be at least 4 rows tall and use a combination of column widths. You can decide what the form will be used for. This set is just for the form structure and layout. 

> [!TIP]
> Try sketching out your form on a piece of paper before you start coding. This will help you visualize the form structure and layout before you start coding. It's also a good idea to think about the use-cases for your form.
> - What will the form be used for? 
> - What kind of information will the user need to input?
> 
> This will help you structure your form in a way that makes sense for the user.

### Q8. Add Bootstrap Form elements to populate the form
Now, populate your form structure with Bootstrap form elements. You can use any form elements you like, such as input fields, radio buttons, checkboxes, etc. You can also use Bootstrap form validation classes to style your form elements.

> [!WARNING]
> How you organize your form is often the most important aspect of form building; Make sure you employ visual hierarchy techniques when building your forms, for example, Long text inputs should typically be one full row, while numbers, emails, and other short inputs can be placed side-by-side in separate columns. Make sure to group related inputs together so there is thematic cohesion in your form.

### Q9. Add three Font Awesome icons or Google Fonts icons
The purpose of icons are to help guide the users eyes to navigable elements on the webpage. They are also used to help break up large sections of text and to add visual interest to the webpage. Add three icons from a CDN to your `ica7.html` file. You can use either [Font Awesome](https://fontawesome.com/) or [Google Fonts](https://fonts.google.com/icons) icons.

### Q10. Add a Google Fonts font family
The last step is to add a Google Fonts font family to your `ica7.html` file. Be strategic with the font that you choose. You can add the font family to your `ica7.html` file using the `<link>` tag inside the `<head>` of the document, and address the font-family in your `ica7.css` file to apply to fonts to your webpage.

---
# CDNs
CDNs (Content Delivery Networks) are a way to deliver content to the user. They are a network of servers that deliver content to the user based on their geographic location. This allows for faster load times and better performance. CDNs are used to deliver content such as files, images, videos, and other media files. They are also used to deliver web pages and other web content. CDNs are used by many websites and are an important part of the modern web.

# Bootstrap
## Introduction
Bootstrap is a free and open-source CSS framework directed at responsive, mobile-first front-end web development. It contains CSS- and JavaScript-based design templates for typography, forms, buttons, navigation, and other interface components. The main catch of Bootstrap is the flexibility and ease of use of adding CSS styles to your HTML elements in a short-hand notation. This allows for rapid development of web pages and web applications. Bootstrap is also a great tool for learning how to build responsive web pages, as it has a built-in grid system that allows for easy layout of web pages.

## Background
Backgrounds are a fundamental part of any web page. Backgrounds can be set using the class names `bg-{color}` where `{color}` is the name of the color you want to use. For example, you can set the background of an element to be blue by using the class name
 - `bg-primary` - Blue background
 - `bg-secondary` - Grey background
 - `bg-success` - Green background
 - `bg-dark` - Dark background
... and many more

Other background coloring options:
 - A light background of each color is also available by using the class `.bg-{color}-subtle`.
 - The backgound color can be set to a gradient by adding the class `.bg-gradient` to any HTML element.
 - The background color opacity can be set by adding the class `.bg-opacity-{value}` where `{value}` is a number between 0 and 100.
   - The only accepted values of the opacity `{value}`'s are 75, 50, 25, 10.
 - The background color can be set to a transparent color by adding the class `.bg-transparent` to any HTML element.

## Borders
Bootstrap has a variety of border classes that can be used to style the borders of HTML elements. The border classes can be used to add borders to the top, bottom, left, and right sides of an element. The border classes can also be used to add rounded corners to an element. The border classes can be used to add a border to an element, and the border classes can be used to remove a border from an element.

## Buttons

## Colors

## Opacity

## Sizing

## Spacing

## Text

## Grid system
Bootstrap includes a responsive, mobile first fluid grid system that appropriately scales up to 12 columns as the device or viewport size increases. It includes predefined classes for easy layout options, as well as powerful mixins for generating more semantic layouts.

## Elements
Scrollspy
Offcanvas
Navbar
Collapse
Carousel
Card
Button / Button Group
Accordion

# Font Awesome
Font Awesome is a font and icon toolkit based on CSS and LESS. It was made by Dave Gandy for use with Bootstrap, and later was incorporated into the BootstrapCDN. Font Awesome has a 5.3.1 version, and it has 1,588 free icons and 7,842 pro icons. Font Awesome is a web font containing all the icons from the Twitter Bootstrap framework, and now many more.

# Google Fonts
Google Font is a library of free licensed font families, an interactive web directory for browsing the library, and APIs for conveniently using the fonts via CSS and Android. The library is maintained by Google and is very popular among web developers. The library contains over 1,000 free licensed font families and is used on over 20 million websites.