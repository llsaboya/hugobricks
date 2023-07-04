---
title: Header 
---

### Logo image

This sets the image in the header. Omitting a value here results in a 'text logo' as you can see on this website. The text logo consists of the value in `title` field that can be found in the 'general.yaml' file in the data folder and the `logo_subtitle` field that you can find in this data file.

### Logo subtitle

When you choose to omit the value for `logo_image` the 'text logo' will appear. The text logo consists of the value in `title` field that can be found in the 'general.yaml' file in the data folder and this `logo_subtitle` field.

### Mobile view at

This numeric value determines at which width the class 'mobilemenu' is added to the body. This class acts as a adjustable media query. In the example it   is set to 1000, which means a width of 1000 pixels.

### Sticky_header

When you choose CSS 'sticky' header refers to a type of header element that maintains its position on the screen while scrolling, up until a specified point where it becomes fixed. Unlike a regular static header, a sticky header will stay visible to the user, even as they scroll through the content on the webpage. A 'sticky' header is achieved by applying the CSS position property with a value of 'sticky' to the header element.

### Menuitems:

This is an array that holds the footer menu. The items in this array consist of a `title` and a `link` field. In the title you put the page title and in link you put the relative url of that page.

### Call To Action (CTA)

In terms of UX/UI a so called Call To Action (CTA)  prompts users to take a specific action on a website or application. CTAs are typically designed in a way that grabs the user's attention.


```
cta:

  active: true
  
  title: Get started
  
  link: /get-started/
  
```

Active it (or not), then define the internal/relative hyperlink it by giving the given page the button clik leads to.


### Preheader

Preheader is defined as the first 'section', at the top of the page body.

If you activate it, feel free to choose dark or light style (playing with the text color and background color). Then show the relevant text to show.

```
preheader: 
  active: true
  is_light: true
  text: Open Mon-Fri from 9.00-5.00
```

as you can see in the data/header.yaml hugobricks relevant code snippet.



> NOTE: And that's it! Feel free to have a look companion 'footer' section in the documentation.