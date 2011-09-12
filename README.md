#  HTML5 Boilerplate [http://html5boilerplate.com](http://html5boilerplate.com)

## Stated project aims.
* Produce an unstyled shopify theme directly based on the html5Boilerplate code
* Include code snippets that a majority of Shopify themes would benefit from but also make them easily removable

## Changelog:

### v.0.2 : September 1st, 2011

#### autocompletedataarray.js
* Removed as it turns out we can;t use the paginate function in a page Shopify doens;t think we should be paginating in, meaning we can't loop through an array in it's entirety (50 limit)
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

## Summary:

This is a set of files that a front-end developer can use to get started on a website, with following included:

1. Everything from HTML5 Boiler plate that can work under Shopify.
2. A Jquery based autocomplete function for the search box
3. All Shopify Template files optimised with HTML5 elements (coming after release 0.1)
4. A checkout.css file to reset Shopify's own CSS styles, with space and hooks to then style the pages as you would like (coming after release 0.1).
5. A snippets folder full of relevent, HTML5 optimised off the shelf tools helpful for Shopify dev. (coming after release 0.1)

## Releases

Watch the [current tickets](https://github.com/Tetsugaku-San/HTML5-Boilerplate-for-Shopify/issues) to view the areas of active development.

