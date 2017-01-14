﻿ Review criteria:
  
1- Layout & Validation.
2- Functionality.
3- Content.
4- Performance.

/////////////////////////

1- LAYOUT & VALIDATION

	# HTML: 
		*Validation: Missing compatibility with HTML5.
	# HEAD: 
		* Favicon: Change the favicon to be same as our logo.
		* Title: Change the to be same as our brand.
	# BODY: 
		* Margin: Add margin   I suggest 20px , white color.
		* Scrool bar: Increase width; Change color.
		* Font:   Increase the opacity; font-size; font-weight;
		* Footer: Decrease height; rearrange its content on three column.
		
	# NAVIGATION:
		* Logo: Replace the current one.
		* Company + submenu: Replace it with just About us link.
		* Breadcrums: Change location Or Decrease banner width, Add some styles.
		
	# SERVICES PAGE:
		* Banners: Change banner width.
		
	# CONTACT US PAGE:
		* Map: Add style.
		* Contact Form: Add style.
		

2- FUNCTIONALITY

	# NAVIGATION & FOOTER:
		* Contacts : Tel, Email, Social media links And other links
		* Company + submenu: Replace it with just About us link.
		* Breadcrums: Change location Or Decrease banner width, Add some styles.
	
	# CONTACT US PAGE:
		* Map: Serve over HTTPS.
			please note: no map on github site because google map was served over http and Github site accepts only https service. once the site is hosted it will work in shaa Allah .

		* Contact Form: Better to be submitted with some backend code for action and validation.
	# Add server code for testimomnial and patrtners to be dynamics.	

3- CONTENT

	# ALL PAGES: 
		* Update Our Technology Partner; 
		* Update Client Testimonials;
	# HOME PAGE:
		* Content: Needs more content (Summury of every page of the site).


4- PERFORMANCE

	
	Navigation: 
		* Implement Angular SPA using ui-router for Fast and smooth routing between pages.
	Loading time: 
		* Use build system to concat and minify styles and scripts.
			(for now: gulp, then: will migrate to webpack or Rollup).
		* Reduce the amount of vendor code which not needed in the production phase.
	
