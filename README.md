#  HTML5 Boilerplate For Shopify [http://html5boilerplateforshopify.com](http://html5boilerplateforshopify.com)

## Summary:

This is a set of files that a front-end developer can use to get started on a website, with following included:

1. Everything from HTML5 Boiler plate that can work under Shopify.
2. A Jquery based autocomplete function for the search box (in as of v 0.3)
3. All Shopify Template files optimised with HTML5 elements (probably complete around 0.6)
4. A checkout.css file to reset Shopify's own CSS styles, with space and hooks to then style the pages as you would like. (in at 0.2)
5. A snippets folder full of relevent, HTML5 optimised off the shelf tools helpful for Shopify dev. (somewhere around 0.7)

## Changelog:

### v.0.5 : October 15th 2011
* Updated product.liquid & index.liquid to fall in line with HTML5. This marks the completion of all basic liquid templates.
* Updated article.liquid, page.liquid & index.liquid to fall into line with the article publishing guidelines from Readability (http://www.readability.com/publishers/guidelines/)
* Implemented Colorbox v1.3.18 (http://jacklmoore.com/colorbox/) as a standard mage viewer. Considered only serving it to product pages, articles and standard text pages but that didn't leave many pages out so it's in everything now.
* Implemented FlexSlider v1.7 (http://flex.madebymufffin.com/) why? every shopify shop has a carousel on the front page, I might as well build one in we can all use. This one is small, responsive and touch happy.
* Created demo carousel on index.liquid, loops through a collection of products called "frontpage"
* Asked the Shopify community for feedback....

### v.0.4 : September 27th, 2011
* Updated README file
* Updated collection.liquid to include semantic structure. Each collection is housed inside a section element with a header that contains the collections title & optional description. Pagination is outside the header, at the top and bottom of a standard ordered list. I have given the section a class of "collection" so it's easy to target, and also given it an ID of that collections unique handle. This means you can style all collections as required but also do collection specific styling using the ID.
* Updated search.liquid to fall in line with the collection.liquid changes. Paginates every 10 results, pagniation is hidden if there are less than 10, remember to update all 3 pagination elements if you change this number. Each LI in the results list has a class of either product or page, depending on whether or not that item in the result search results arrayn has an image associated with it. Products have images, pages do not. I'll leave it up to you to decide what to do with this, suffice to say in can mess with your pretty search results pages if you have some things with images and some without.
* Updated page.liquid to fall into line with (broadly) the article.liquid layout. Added a unique ID on the root article element of that pages handle, and added a class of "page"
* Went back & updated article.liquid to contain have the posts handle as it's ID, and the class of "post" (just like page.liquid).
* Updated 404.liquid to fall in line with the other templates, just replaced a div with a section and added an ID to the root article.
* Updated blog.liquid to hide pagination when there are less than a page of results, added unique ID (blog_posts) and a class (collection). I kept the class of collection, because it still *is* a collection of results, just a different set than a product search. They are presented with different elements (DL for blogs, OL for products) so they are easy to style differently.


### v.0.3 : September 14th, 2011
* Updated the two blog templates, blog.liquid and article.liquid to have proper HTML5 elements and spent some time making sure the <time> element was being used properly with correctly formatted ISO8601 datetime attributes. It doesn;t seem like much but it took ages to make sure they were right and that the sections / article elements were correctly nested and the document outline was working as you'd want it to.
* Also fiddle with headings on the theme.liquid page to ensure there were headings to set the document outline properly.

### v.0.2 : September 1st, 2011

#### autocompletedataarray.js
* Removed, as it turns out we can't use the paginate function in a page Shopify doesn't think we should be paginating in, meaning we can't loop through an array in it's entirety (50 limit)
(see http://wiki.shopify.com/Pagination)

#### checkout.css
* By default, shopify provides generic styling for the checkout process which, although perfectly good, will not suit your store. You also cannot turn off this CSS. Because of this I have added a reset style sheet, based on Eric Meyer's reset 2.0 (http://meyerweb.com/eric/tools/css/reset/), *only* to the checkout.css file. You should add your own declarations in the same file and remember to add the !important after each declaration you add.

#### 404.liquid
* Replaced with a cut n paste from the original boiler plate release

### v.0.1 : September 1st, 2011

### 0.1 changelog

#### checklist.txt
* Runs through a list of small jobs you should perform in your shopify shop to get things working 100% with this release

#### robots.txt
* Removed as already provided by Shopify (check shopname.myshopify.com/robots.txt for the content of yours if you wish) & not user editable.

#### .htaccess
* Removed. Not relevant.

#### humans.txt
* Removed. Not useful as we don't have access to the root.

#### crossdomain.xml
* Removed. Not useful as we don't have access to the root.

#### Build Folder
* Removed as none functional within Shopify

#### Img, JS &CSS Folder
* Removed and relevant contents rolled into the assets folder


#### CONTRIBUTORS
[Miles Cheverton AKA The Tall Designer](http://www.thetalldesigner.com) 

## License:

Major components:

* Modernizr: MIT/BSD license
* jQuery: MIT/GPL license
* DD_belatedPNG: MIT license
* YUI Profiling: BSD license
* HTML5Doctor CSS reset: Public Domain
* CSS Reset Reloaded: Public Domain

Everything else:

* [The Unlicense](http://unlicense.org) (aka: public domain)