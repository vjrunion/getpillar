Pillar 
======
##The Pillar Grid System
#Mobile First Templating and Responsive Grid.

Pillar uses a 5 x 6 grid that allows for smaller devices and mobile presentation. You can create odd and even based groups with up to 30 sections for each block in the grid.  All positioning and sizing is done via (percent and em) so there is no loss in the actual box model within a browser.

##Grid Constructors

##local group ------ ]
* To declare a new section in the grid.
	<section class="local-group">
		You new pillar group.
	</section>

##boundary ------ ]
* Declares an area that exists as contstant to another area.

##pillar ------ ]
* This class uses units of 1-5.

    Calculation = $base-width: percentage(64/320);
    
    Example = .pillar-two { width: $base-width * 2 }

##fill ------ ]
* This class uses units of 1-6.
    
    Calculation = $base-height: percentage(80/480);
    
    Example = .fill-two { height: $base-height * 2 }

##edge ------ ]
* This make a standard presentation box with paddings and margins.

##Made with love from:

<img src="http://sass-lang.com/assets/img/logos/logo-235e394c.png" style="width:25%;margin:5em;padding:1em;">
