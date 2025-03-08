# Bugs-Sample

# Below are some Bug Report samples that I wrote while working on previous projects.
---------------------------------------------------------------------------------------------------------------------
# Order can be completed without adding any products to the shopping cart

## Description:

On the website, it is possible to complete an order even if no products have been added to the shopping cart.

## Steps to reproduce:

1. Go to demoblaze.com
2. Do not add any products to the cart
3. Proceed to the cart page
4. Press the “Place Order” button
5. Fill in shipping information (name, credit card)
6. Press the “Purchase” button 

## Actual result:

It is possible to complete the order even if the cart is empty.

## Expected result:

The user should receive an error message or a warning indicating that there are no products in the cart and that at least one product must be added in order to complete the order.

---------------------------------------------------------------------------------------------------------------------
# Multiple identical products in the cart are not grouped

## Description: 

When the user tried to buy identical & multiple products they are not grouped.

## Steps to reproduce:

1. Go to Demoblaze.com
2. Add 5-6 identical iphone 6 phones in the cart (any product will work)
3. Press the cart button (in the top menu)
4. Expected result: The products should be grouped in the same line.
5. Actual result: The products are not grouped inline.
6. User sees 5-6 identical products one under the other instead of seeing only 1 and a quantity multiplier.

# Expected result: 

The products should be grouped in the same line.

# Actual result:

The products are not grouped inline.
User sees 5-6 identical products one under the other instead of seeing only 1 and a quantity multiplier.

---------------------------------------------------------------------------------------------------------------------
# Error 404 - not Found

## Description:

The file petitie_persoana_fizica.php located in the /wp-content/themes/portal/ directory is returning a 404 (Not Found) error when attempting to load it.

## Steps to reproduce:

1. Go to https://www.primariatechirghiol.ro/wp-content/themes/portal/petitie_persoana_fizica.php

## Expected result:

The file petitie_persoana_fizica.php should be loaded properly without returning a 404 error.

## Actual results:

A 404 error is returned, indicating that the requested resource is not found on the server.

---------------------------------------------------------------------------------------------------------------------

#  Missing Email Field on Checkout Page

## Description:

The email field is missing on the checkout page, making it impossible for users to provide their email address during the ordering process.

## Steps to reproduce:

1. Go to demoblaze.com
2. Select any product
3. Add product to cart
4. Go to the cart page
5. Place the order 
6. Fill in the fields
7. Observe that there is no field to enter the email address for the order

## Actual result:

The email field is completely missing on the checkout page, so the user is unable to provide their email address.

## Expected result:

The checkout page should include a field for the user to enter their email address in order to proceed with the order.

---------------------------------------------------------------------------------------------------------------------

# We can complete the order without having a country/address field filled in.

## Descriprion:

On the website, when a user attempts to purchase a product, it is possible to complete the order without filling in all the necessary fields, such as address, country, and street. This behavior could lead to issues in processing deliveries and create confusion for users.


## Steps to reproduce:

1. Go to demoblaze.com 
2. Add a random product to the cart
3. Go to the Cart page
4. Press the “Place Order” button
5. Fill in only the required fields(Name, Credit Card).  
6. Press “Purchase” button and complete the order

## Actual result:

The order can be completed without entering all the necessary information, which could lead to incorrect delivery processing.

## Expected result:

It should be impossible to complete the order without entering all the necessary information including a complete address.    

 


