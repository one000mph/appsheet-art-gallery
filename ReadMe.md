### README

#### Usage

`node server.js`

Access at localhost:8000 OR go to http://appsheet-photo-gallery.herokuapp.com for a stable version of the app. Note that the version on herokuapp may not be up-to-date with the latest version on github.


#### Features

* Randomize image order on page reload
* Jump back to top with link sticky footer
* Click image to show/hide meta-data
* Images load on scrollstop, improving UX and decreasing browser load
* Images are retrieved by a client-side script, minimizing initial load time
* HTML containers for new images are also dynamically generated and loaded
* Site is responsive to mobile view

#### Known Bugs

* Encoding of special characters is not recognized in the .getJSON() method so sometimes you might see a '?' or � character in the meta data. This could possibly be fixed by using a .ajax() call instead of .getJSON()

### Design Question

**How would you improve the UX of Amazon.com? What would you change, and why?**

On the main page I would simplify the menus to contain only 4-6 items. For example "Your Account" and "Your Lists" contains far too many menu items for all of them to be useful. The media items such as Amazon Cloud Drive, Kindle, and Video libraries could fall under some appropriately title "Digital Content" category. The gift menu items under the "Your Lists" menu could also be consolidated into a Registry & Gifts sections. In general good UI design contains simple menus that contain only the most common tasks.

Search technology is also good enough that Amazon.com could eliminate many of these menu items by including them in their search index. Based on my brief initial browsing it seems that Amazon.com already has included most, if not all, of these items in the main search index so they could eliminate these links any time. Amazon.com might benefit by doing some quantitative analysis of the most-used functions on their website. Using this information they can improve the user experience by eliminating many of the extraneous links and buttons. Since Amazon.com is a service that tries to market to a diverse user base of all ages, interests, and technology-literacy this analysis would be time-consuming, but would probably yield very informative results.

The UX for buying a product on Amazon is fairly straightforward for an experienced user, but a less experienced user might be overwhelmed by the amount of information displayed on the screen. In addition to the essential product details there is a huge amount of links and marketing material that are displayed on a product information page. It seems that Amazon prioritizes their marketing of additional products over making relavant information easy to access since a user has to scroll 3-4 times to access Product Details and Reviews. Suggestions for additional items based on the user's browsing history are displayed above the information.

Amazon.com attempts to provide a huge amount of information and services to their users. Although the current site design does successfully provide access to all these features, the sheer number of existing links is still overwhelming even to experienced users. My main advice is to reduce the number of links and advertising on the page as much as possible, considering that less advertising may decrease overall sales even as it improves the UX of the website. The goal would be to minimize the number of clicks, scrolls, and other navigation steps that users must make to find the information that they need.