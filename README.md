Datatables-Bootstrap3
=====================

Quick Start
-------------------------------
Copy these files and the images inside assets to your project and include them in the page.

1. assets/css/datatables.css
2. assets/js/datatables.js
3. assets/images/*  

Please note : If you copy the images to a folder other than images in your project, be sure to update the image path in the datatables.css file.

Pagination types
-------------------------------

1. Normal:

		//Default Type
        $('.datatable').dataTable(); 
		$('.datatable').dataTable({"sPaginationType": "bs_normal"});	

2. Two Buttons:

        $('.datatable').dataTable({"sPaginationType": "bs_two_button"});
		
2. Four Buttons:

        $('.datatable').dataTable({"sPaginationType": "bs_four_button"});
		
2. Full :

        $('.datatable').dataTable({"sPaginationType": "bs_full"});
