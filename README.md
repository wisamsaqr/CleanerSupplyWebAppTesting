# Cleaner's Supply Web Application Testing Using Katalon

# Test Plan

### Senario 1

- Navigate to web site https://www.cleanersupply.com/
	- assert Url
	- assert title
	- assert cart notification is 0
	
- Fill the search input with the term "Plastic"
	- assert the placeholder disappears
	- assert the value is reflected
- Click Search button
	- assert Url
	- assert title
	- assert the page header.
	- assert The result for "Plastic" appears

- Check the  'Packaging Products' filter
	- assert the loading indicator appears 
	- assert the loading indicator disappears.
	- assert the page url.
	- assert Packaging Products is checked.
	- assert Selected Filter section appears and has 'Packaging Products' item in it.
	- assert The result for "Plastic" appears with the same number next to the filter.
	- assert the filter changes. (needs lots of time to track changes)
	- assert the pagination changes.

- Check the 'Plastic Bags' filter
	- assert the loading indicator appears 
	- assert the loading indicator disappears.
	- assert the page url.
	- assert  'Plastic Bags' is checked.
	- assert Selected Filter section  has  'Plastic Bags' item in it.
	- assert The result for "Plastic" appears with the a new  number next to the filter.
	- assert the filter changes. (needs lots of time to track changes)
	- assert the pagination changes.
	
- Click on Color Group Tab filter
 	- assert the filter contents appear.
 	- check + turns to - 
 
 - Click on "Green" color filter.
 	- assert the loading indicator appears 
	- assert the loading indicator disappears.
	- assert the page url.
	- assert  the border of the color is black.
	- assert Selected Filter section  has  'Green' item in it.
	- assert The result for "Plastic" appears with the a new  number next to the filter (1).
	- assert the filters changes.
	- assert the pagination disappears

- Click on the resulted products "View Details" button.
	- assert hover over the product.
	- assert hover over the button of view details.
	- assert page Url
	- assert page title.
	- assert the product.
	- assert price in range .
	- assert list price is the same 

- Click "X-large" product Variant.
	- assert hover over the variant.
	- assert the page Url has a new sku.
	- assert "X-large" is selected.
	- assert the stock # changes.
	- assert the price changes.
	- assert the product title changes.
	- assert the list price changes.
	- assert in stock section changes from unavailable.
	- assert the image changes.
	- assert volume pricing table changes.

- Click "Green" color product Variant.
	- assert hover over the variant.
	- assert the page url has a new sku.
	- assert "Green" color is selected and the filter title has Green.
	- assert the stock # changes.
	- assert the product title changes.
	- assert the image changes.	

- Fill Quantity To 5 .
	- assert the value is reflected.

- Click on add to cart.
	- assert hover over the button.
	- assert "loading appears"
	- assert "added to cart" appears
	- assert "add to cart" returns normal.
	- assert the header cart notification has 1 item.
	- assert the header cart notification has the price for the 5 items.

 Click "large" product Variant.
	- assert hover over the variant.
	- assert the page Url has a new sku.
	- assert "large" is selected.
	- assert the stock # changes.
	- assert the price changes.
	- assert the product title changes.
	- assert the list price changes.
	- assert the image changes.
	- assert volume pricing table changes.

- Click "Blue" color product Variant.
	- assert hover over the variant.
	- assert the page Url has a new sku.
	- assert "Green" color is selected and the filter title has Green.
	- assert "BLue" color is selected.
	- assert the stock # changes.
	- assert the product title changes.
	- assert the image changes.	

- Fill Quantity To 3 .
	- assert the value is reflected.

- Click on add to cart.
	- assert "loading appears"
	- assert "added to cart" appears
	- assert "add to cart" returns normal.
	- assert the header cart notification has 2 items.
	- assert the header cart notification has the price for the new 3 items.
	
-Navigate to the cart
	-Click on cart icon
		-assert the design on click
		-assert the mini cart visibility
		-assert URL
		-assert title
		-assert header
		-assert products in the cart
		-assert the quantity 
		-assert price
		-assert order summary price
		-assert order item number
		
-Click on 'Proceed To Checkout'
	-assert on click design
	-assert URL
	-assert title
	-assert header
	-assert order total
	-assert number of items
	-assert sub total of the elements
	
-Select 'Checkout As Guest' 
	-Assert 'checkout as guest' is checked
	
	-Click on 'continue' button
	 	-assert on click design
	 	-assert URL
	 	-assert title
	 	-assert header
	 	
- Fill Shipping Address and payment method with fake data
	-fill 'Company' name field
		-assert value is reflected
		-assert on active design
		
	-fill 'first Name' field
		-assert value is reflected
		-assert on active design
		
	-fill 'Last Name' field
		-assert value is reflected
		-assert on active design
		
	-fill 'Address Line 1'
		-assert value is reflected
		-assert on active design
		
	-fill the 'Address Line 2'
		-assert value is reflected
		-assert on active design
		
	-fill 'Zip/Postal Code' field
		-assert value is reflected
		-assert on active design
		
	-fill 'city' field
		-assert value is reflected
		-assert on active design
		
	-select state/Province 
		-assert value is reflected
		-assert on active design
		
	-fill phone number field
		-assert value is reflected
		-assert on active design
		
	-fill email field
		-assert value is reflected
		-assert on active design
	-fill 'name on card' field
		-assert value is reflected
		-assert on active design
		
	-fill -Credit Card Number' field
		-assert value is reflected
		-assert on active design
		
	-fill 'Security Code' field
		-assert value is reflected
		-assert on active design
		
	-add 'Expiration Date' month
		-assert value is reflected
		-assert on active design
			
	-add 'Expiration Date' year
		-assert value is reflected
		-assert on active design	
		
-Click on review order button
	-assert URL
	-assert title
	-assert heading
	-assert shipping address
	-assert payment method
	-assert order total
	-assert my cart info
	
-Close browser

### Senario 2

- Navigate to web site https://www.cleanersupply.com/
	- assert Url
	- assert title
	
-Hover on 'Tags & Forms' header items
	-assert background color
	-assert sub menu visibility 
	
-Select 'Computers & Registers' category
	-assert on active design
	
	-click on computers & Registers
		-assert title
		-assert URL
		-assert header
		-assert computer & Register sunb nav
		
-Select the 'Casio' manufacturer
	-assert URL
	-assert selected filters section
	-assert number of elements in the sub filters
	
-Select 'SP1000' Model
	-assert URL
	-assert selected filters section
	-assert number of elements in the sub filters
	
-Enter the resulted product 
	-Click on the resulted product
		-assert URL
		-assert title
		-assert product name
		-assert sub nav
		-assert the price
		
	-Add 10 items from the product
		-assert the value is reflected
		-assert the price
		
	-Click on add to cart button
		-assert the button design on click
		-assert the cart number
		-assert the cart price
		-assert the quantity
		-assert the price
		
-Navigate to the cart
	-Click on cart icon
		-assert the design on click
		-assert the mini cart visibility
		-assert URL
		-assert title
		-assert header
		-assert products in the cart
		-assert the quantity 
		-assert price
		-assert order summary price
		-assert order item number
		
-Click on 'Proceed To Checkout'
	-assert on click design
	-assert URL
	-assert title
	-assert header
	-assert order total
	-assert number of items
	-assert sub total of the elements
	
-Select 'Checkout As Guest' 
	-Assert 'checkout as guest' is checked
	
	-Click on 'continue' button
	 	-assert on click design
	 	-assert URL
	 	-assert title
	 	-assert header
	 	
- Fill Shipping Address and payment method with fake data
	-fill 'Company' name field
		-assert value is reflected
		-assert on active design
		
	-fill 'first Name' field
		-assert value is reflected
		-assert on active design
		
	-fill 'Last Name' field
		-assert value is reflected
		-assert on active design
		
	-fill 'Address Line 1'
		-assert value is reflected
		-assert on active design
		
	-fill the 'Address Line 2'
		-assert value is reflected
		-assert on active design
		
	-fill 'Zip/Postal Code' field
		-assert value is reflected
		-assert on active design
		
	-fill 'city' field
		-assert value is reflected
		-assert on active design
		
	-select state/Province 
		-assert value is reflected
		-assert on active design
		
	-fill phone number field
		-assert value is reflected
		-assert on active design
		
	-fill email field
		-assert value is reflected
		-assert on active design
	-fill 'name on card' field
		-assert value is reflected
		-assert on active design
		
	-fill -Credit Card Number' field
		-assert value is reflected
		-assert on active design
		
	-fill 'Security Code' field
		-assert value is reflected
		-assert on active design
		
	-add 'Expiration Date' month
		-assert value is reflected
		-assert on active design
			
	-add 'Expiration Date' year
		-assert value is reflected
		-assert on active design	
		
-Click on review order button
	-assert URL
	-assert title
	-assert heading
	-assert shipping address
	-assert payment method
	-assert order total
	-assert my cart info
	
-Close browser

### Senario 3 

- Navigate to main page
	- assert Url
	- assert title
	- assert cart notification is 0
	
- Click on quick order button in main page
	- assert Url
	- assert title

For All products:
- fill  product stock # 
	- assert the  value
	- assert focus css changes.
	- assert qty input appears with value 1
	- assert the item info apperas 
	- assert price appears.
	- assert total appears.
	- assert remove button apperas.
	
- Edit quanity randomly from 5 to 50.
	- assert the value is reflected.
	- click outside the input.
	- assert the price changes.
	- assert the total chagnes.
	
-Navigate to the cart
	-Click on cart icon
		-assert the design on click
		-assert the mini cart visibility
		-assert URL
		-assert title
		-assert header
		-assert products in the cart
		-assert the quantity 
		-assert price
		-assert order summary price
		-assert order item number
		
-Click on 'Proceed To Checkout'
	-assert on click design
	-assert URL
	-assert title
	-assert header
	-assert order total
	-assert number of items
	-assert sub total of the elements
	
-Select 'Checkout As Guest' 
	-Assert 'checkout as guest' is checked
	
	-Click on 'continue' button
	 	-assert on click design
	 	-assert URL
	 	-assert title
	 	-assert header
	 	
- Fill Shipping Address and payment method with fake data
	-fill 'Company' name field
		-assert value is reflected
		-assert on active design
		
	-fill 'first Name' field
		-assert value is reflected
		-assert on active design
		
	-fill 'Last Name' field
		-assert value is reflected
		-assert on active design
		
	-fill 'Address Line 1'
		-assert value is reflected
		-assert on active design
		
	-fill the 'Address Line 2'
		-assert value is reflected
		-assert on active design
		
	-fill 'Zip/Postal Code' field
		-assert value is reflected
		-assert on active design
		
	-fill 'city' field
		-assert value is reflected
		-assert on active design
		
	-select state/Province 
		-assert value is reflected
		-assert on active design
		
	-fill phone number field
		-assert value is reflected
		-assert on active design
		
	-fill email field
		-assert value is reflected
		-assert on active design
	-fill 'name on card' field
		-assert value is reflected
		-assert on active design
		
	-fill -Credit Card Number' field
		-assert value is reflected
		-assert on active design
		
	-fill 'Security Code' field
		-assert value is reflected
		-assert on active design
		
	-add 'Expiration Date' month
		-assert value is reflected
		-assert on active design
			
	-add 'Expiration Date' year
		-assert value is reflected
		-assert on active design	
		
-Click on review order button
	-assert URL
	-assert title
	-assert heading
	-assert shipping address
	-assert payment method
	-assert order total
	-assert my cart info
	
-Close browser


### Testing Website Header

- Navigate to web "site https://www.cleanersupply.com/".
	- assert url.
	- assert title.
	
- Click brand nav item
	- assert url.
	- assert title.
	
- Fill the search input with the "Plastic"
	- assert the placeholder disappearance.
	- assert the value is reflected.
	- assert the search autocomplete dropdown is displayed.
	
- Click search button
	- assert that url contains "search-results".
	- assert that url contains "plastic".
	- assert that title contains "Search Results".
	- assert "SEARCH RESULTS" header.
	- assert "PLASTIC" term in product list header.
	
- Hover "Quick Order"
	- assert hover color is reflected.
	
- Click "Quick Order"
	- assert that url contains "quick-order".
	- assert that title contains "quick order".
	- assert "Quick Order" active tab.
	
- Hover "Reorder"
	- assert hover color is reflected.
	
- Click "Reorder"	(unauthenticated user is redirected to login page)
	- assert that url contains "previously-ordered".
	- assert that title contains "Log In - Cleaner's Supply".
	- assert "RETURNING CUSTOMER?" sub-header.
	
- Hover "My Account"
	- assert hover color is reflected.
	
- Click "My Account"
	- assert account dropdown is opened.
	- assert that account dropdown info contains "LOGIN TO TRACK AN ORDER OR MANAGE YOUR ACCOUNT.".
	
- Hover "Cart"
	- assert cart items no icon is zero.
	- assert hover color is reflected.
	- assert cart dropdown is opened.
	- assert that cart dropdown contains "YOUR CART IS EMPTY AND VERY SAD".
	
- Click "Cart"
	- assert that url contains "shopping-cart".
	- assert that title contains "Shopping Cart - Cleaner's Supply".
	- assert that page header contains "SHOPPING CART".
	
• Menu Test Cases
- Hover "Tags & Forms".
	- assert hover design is reflected.
	- assert that sub-menu appears.
	
- Click "Tags & Forms"
	- assert that url contains "Tags-Forms".
	- assert that title contains "Dry Cleaning Tags, Forms & Invoices - Cleaner's Supply".
	- assert "DRY CLEANING TAGS, FORMS & INVOICES" header.
	
- Hover "Counter & Check-In".
	- assert hover design is reflected.
	- assert that sub-menu appears.
	
- Click "Tags & Forms"
	- assert that url contains "Counter-Check-In".
	- assert that title contains "Store Counter & Check-In Supplies - Cleaner's Supply".
	- assert "STORE COUNTER & CHECK-IN SUPPLIES" header.
	
- Hover "Bags"
	- assert hover design is reflected.
	- assert that sub-menu appears.
	
- Click "Bags"
	- assert that url contains "Bags".
	- assert that title contains "Dry Cleaning Bags - Cleaner's Supply".
	- assert "DRY CLEANING BAGS" header.
	
- Hover "Pressing & Spotting"
	- assert hover design is reflected.
	- assert that sub-menu appears.
	
- Click "Pressing & Spotting"
	- assert that url contains "Pressing-Spotting".
	- assert that title contains "Pressing, Spotting Tools & Supplies - Cleaner's Supply".
	- assert "PRESSING, SPOTTING TOOLS & SUPPLIES" header.
	
- Hover "Packaging"
	- assert hover design is reflected.
	- assert that sub-menu appears.
	
- Click "Packaging"
	- assert that url contains "Packaging".
	- assert that title contains "Packaging Supplies - Cleaner's Supply".
	- assert "PACKAGING SUPPLIES" header.
	
- Hover "Racks"
	- assert hover design is reflected.
	- assert that sub-menu appears.
	
- Click "Racks"
	- assert that url contains "Racks".
	- assert that title contains "Racks & Rack Accessories - Cleaner's Supply".
	- assert "RACKS & RACK ACCESSORIES" header.
	
- Hover "Tailoring"
	- assert hover design is reflected.
	- assert that sub-menu appears.
	
- Click "Tailoring"
	- assert that url contains "Tailoring".
	- assert that title contains "Tailoring Supplies - Cleaner's Supply".
	- assert "TAILORING SUPPLIES" header.
	
- Hover "Laundromat"
	- assert hover design is reflected.
	- assert that sub-menu appears.
	
- Click "Laundromat"
	- assert that url contains "Laundromat".
	- assert that title contains "Laundromat Supplies - Cleaner's Supply".
	- assert "LAUNDROMAT SUPPLIES" header. 

### Testing Website Footer
- Verify Footer Top.
	- Verify background color
	- Verify contains img 

- Verify footer body
	- verify background color

- Verify exclusive email footer item
	- Verify title
	- Verify info
	- Fill the email.
		- verify placeholder disappers.
		- veify the value is reflected.
	- Click on sign up 
		- Verify the success message 'Thanks for signing up'
		- Verify the email input value is empty

- Verify Social media footer item
	- verify title
	- For all links.
		- verify the icon.
		- click on the link
			- verify a new tab is opened with the same url of href

- Verify connect with us section.
	- verify title
	- verify email and email icon
	- verify contact availability .
	- verify phone numbers (English -korean - international)
	- click Chat
		- verify chat icon
		- verify new window opens.
		
- Verify my account section.
	- verify title
	- for all urls.
		- verify text
		- verify url

- Verify about us section.
	- verify title
	- for all urls.
		- verify text
		- verify url

- Verify featured categories section.
	- verify title
	- for all urls.
		- verify text
		- verify url

- Verify online tools section.
	- verify title
	- for all urls.
		- verify text
		- verify url

- Verify request a catalog. (can have its own senario)
	- verify title.
	- verify url.
	- verify page heading.

- Verify request free classifieds.  (can have its own senario)
	- verify title.
	- verify url.
	- verify page heading.
	
- Verify choosing a region.
	- verify title.
	- select a country.
		- verify url

- Click on "leave feed back"
	- verify the modal appears.
	(optional)
	- verify title.
	- verify subtitle
	- fill feedback textarea
		- verify value is reflected.
	- fill email.
		- verify value is reflected 
	- verify captcha.
	- click submit.
	- verify success message "THANKS FOR YOUR FEEDBACK, WE APPRECIATE IT!"

### The End...
