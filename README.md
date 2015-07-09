# Crafty Cart

## Description
Crafty Cart will be a pseudo-eCommerce application you create using 3rd party data from Etsy

## Objectives

### Learning Objectives

After completing this assignment, you should…

* Understand the basic flow of an angular application
* Demonstrate ability to use multiple controllers and services in angular
* Demonstrating understanding of MVC concepts with Angular Views, Routes, Controllers, and Factory Services.
* Able to integrate 3rd party data using api

## Details

### Deliverables

* A repo containing your angular app with a bower.json and bower_components NOT checked in
* A gh-pages branch that demonstrates the Crafty cart from the same repository (will need bower_components checked in)

### Normal Mode

  Congratulations!  You've recently come into some time to bootstrap your (our) new idea.  We're going to build a Crafty eCommerce Solution that sources artisans from around the globe and sells their wares.  Like many startups with good ideas, we have no data - so we need to integrate Etsy's api for products.

  - Crafty Cart needs to have 3 Views
    - A Product listing View
      - Each product will have the following in listing
        - a buy/add to cart button
        - photo
        - title
        - link back to etsy product (view on etsy)
      - The listing page will need filtering functionality for the following attributes
        - title
        - price
    - Product Detail View
      - Detail view will only have user selected product
        - all the above data is required, but additionally
        - show Description
        - show materials used
        - use larger image
    - A shopping cart view
      - This view will house the items that have been added to cart.
      - you can design how you want, but you will need to have a running total of items in cart, in addition to quantity and title of product.
      - users should be able to remove items from cart



  **Etsy API "getting started":** https://www.etsy.com/developers/documentation/getting_started/api_basics

  - load the active listings: https://openapi.etsy.com/v2/listings/active?api_key=aavnvygu0h5r52qes74x9zvo&callback=?

  - load the item's data, i.e. with the unique id "183182778": https://openapi.etsy.com/v2/listings/183182778?api_key=aavnvygu0h5r52qes74x9zvo&callback=?

  - Notice the `&keywords=...` in the following example URL for searching: https://openapi.etsy.com/v2/listings/active.js?api_key=aavnvygu0h5r52qes74x9zvo&keywords=banana+costume&callback=?.

  
