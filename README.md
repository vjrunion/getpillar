Pillar 
======

<img src="https://github.com/jvrunion/getpillar/blob/master/app/images/pillar.png">

#####Mobile First Templating and Responsive Grid.

####Dependancies
NODEJS - [ http://nodejs.org/download/ ]


SASS - Install

	gem install sass

Yeoman

 	npm install -g yo
 	
Yeoman Generator for AngularJS

 	npm install -g generator-angular
 	
New Dir

	mkdir new-project
	
Then `cd` to `new-project` then run:
	`yo-angular new-project` AppName is optional

Pillar uses a 5 x 6 grid that allows for smaller devices and mobile presentation. You can create odd and even based groups with up to 30 sections for each block in the grid.  All positioning and sizing is done via (percent and em) so there is no loss in the actual box model within a browser.

###Local group

To declare a new section in the grid.

	<section class="local-group">
		You new pillar group.
	</section>

A local group refers to a block that is at the highest level in the DOM tree.  All of its children will be able to reset their block dimension in ratio to this parent block's declartaion.  This is usefull when defining small area's with meaningfull and targeted content.

###Boundary

Declares an area that exists as contstant to another area.



###Pillar

This class uses units of 1-5.

    Calculation = $base-width: percentage(64/320);
    
    Example = .pillar-two { width: $base-width * 2 }

###Fill

This class uses units of 1-6.
    
    Calculation = $base-height: percentage(80/480);
    
    Example = .fill-two { height: $base-height * 2 }

###Edge

This make a standard presentation box with paddings and margins.

######Made with love from:

- Angular
- SASS
- GRUNT
- NODE
- BOWER
- YEOMAN
