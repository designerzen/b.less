# b.less #
A collection of _LESS Mixins_ that provides mixins, shortcuts and useful constants for developing websites and native applications. 

## Why? ##
There are not many libraries that focus on fonts, typography and native OS specific styles but this one does.
I wrote and collated this data for use in projects far and wide.

### Usage : ###
There are 2 different ways to use this library...
	
	1. Import the library into your main less file ```import url(b.less)```

	2. Use the independent library files in the ```mixins/``` folder
	
Files included :
	
	b.less - _compiled class containing all the mixins and constants_
	
	mixins/
		colour.less - _colour mixins_
		colour.native.less - _OS colour palette_
		colour.palette.less - _Loads of colours with predefined names_
		font.less - _Mixins and shorthands_
		font.i18n.less - _Internationalised base fonts_
		font.native.less - _Fonts currently used by the operating system_
		font.stacks.less - _Fallback fonts and predefined stacks_
		print.less - _A useful mixin for adding in print styles_
		typography.less - _Mixins for typography_
		utilities.less - _common layout and image mixins_
	
	build/
		scripts used by package.json file to create the library
	
Build :
	
Credits :
* Chirag Mehta for his work creating the colour name list [homepage](http://chir.ag/projects/name-that-color)
* Font Stacks inspired by [AwayBack](http://www.awayback.com/revised-font-stack/)
* Denis Leblanc - [denisleblanc.com](http://denisleblanc.com)
* Elyse Holladay
* Dave from [cssfontstack.com](http://www.cssfontstack.com/)
* Robert Penner for his great ease equations