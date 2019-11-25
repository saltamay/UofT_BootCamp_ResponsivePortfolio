# UofT SCS Full-Stack Web Development Boot Camp Project #2: Custom CSS and Media Queries Responsive Portfolio

### Overview

Personal portfolio page design built with Bootstrap framework that has "Home",  "Portfolio", and "Contact" pages that is aimed to showcase portfolio projects I am working on as well as my contact information.

### Description

After I built basic portfolio, I realized that it does not look good on different screen sizes.  I wanted to enhance it by giving it responsiveness and redesign it with mobile-first in mind.

### Build with:

HTML5 and custom CSS3 with Media Queries

### Development Strategy

1. Use three `@media screen` tags, each with one of these `max-width`s: `980px`, `768px` and `640px`.
    - You use `980px` because you never want any of the content to be cut off. Since the desktop layout is about 960px wide, you want the media queries to kick in before your content gets cut off.
    - `768px` is about the width of a tablet and `640px` is about the width of a phone in landscape.
2. Make the layout match the following screenshots:
    - `index.html`: [980px](notion://www.notion.so/stamay/Images/980-index.jpg), [768px](notion://www.notion.so/stamay/Images/768-index.jpg), [640px](notion://www.notion.so/stamay/Images/640-index.jpg)
    - `portfolio.html`: [980px](notion://www.notion.so/stamay/Images/980-portfolio.jpg), [768px](notion://www.notion.so/stamay/Images/768-portfolio.jpg), [640px](notion://www.notion.so/stamay/Images/640-portfolio.jpg)
    - `contact.html`: [980px](notion://www.notion.so/stamay/Images/980-contact.jpg), [768px](notion://www.notion.so/stamay/Images/768-contact.jpg), [640px](notion://www.notion.so/stamay/Images/640-contact.jpg)
3. Make the position of the header `static` (the default positioning) when the screen is `640px` wide. The header design takes up a lot of room; you don't want it to stick to the top of a small screen and leave no room for the rest of your site.
4. Be sure to include the `viewport` tag in all your HTML files, otherwise your media-queries won't function as expected on mobile devices. *(Hint: You won't need to use exact pixels for anything other than the container)*
5. **Protip**: Use the Chrome extensions [Window Resizer](https://chrome.google.com/webstore/detail/window-resizer/kkelicaakdanhinjdeammmilcgefonfh) and [Browser Width](https://chrome.google.com/webstore/detail/browser-width/mlnegepkjlccabakompdmbcmdieaideh) to see the browser dimensions in Chrome.
6. Deploy your new portfolio (now with media queries!) to GitHub Pages.
