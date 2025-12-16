My application contains 4 pages: Home, Product,Item and Cart pages

1. Home page:
At the top we have our navigation bar with links to the other pages, these links when using a mobile emulator disappear and a burger
menu button appears, when its clicked, the navigation links appear again. 
In our content area we have some text and 2 embeded videos using iframe, one is downloaded to our computer and the other one is online.
The text and videos are responsive as well.
Lastly in our footer section we have a sticky footer with information text and links that is as well responsive.

2. Products page
Since our navigationbar and footer are the same we will only cover the content area, items are loaded using the product array.
Each item card contains the image of the item, the name,the color, the discription, the stock, a view more and an add to cart button. 
The add to cart button saves the product to our localStorage,
 The view more button uses sessionStorage to load the item in our item page using the same card layout
 The page also has a back to top button that directs our user to the top of the page, which on mobile version is transparent to improve
 visibility on small mobile devices
 The page at the top has a select drop that can filter the items using the stock value
 The whole content area is responsive
 
3. Item page
Since our navigationbar and footer are the same we will only cover the content area
As said before, the items are loaded using the sessionStorage and have the same card layout as the products in products page
The whole content area is responsive

4. Cart page(advanced)
Since our navigationbar and footer are the same we will only cover the content area
The items are displayed using a grid loaded from the localStorage
Items are displayed in rows, showing the item picture, the name-color, the price and the quantituy allowing the user to change the quantity
of an item, remove a whole row of item regardles of quantity, remove an item by setting the quantity using the - and + buttons , is allowed as wel;
typing the quantity number is allowed as wel;
At the bottom of our cart area we have an empty cart button that empties our cart and clears localStorage data, we also have the total
and a discount code input area that changes the total if a correct discount is entered
The whole content area is responsive

Generally:
All of the pages are responsive and work perfecly on mobile emulators
All of the files have passed validation checks
All of the pages contain comments that make the code clear and readable
Adoption of version control using github has also been implemented
The application followed the marking sheet and its aiming for full marks
