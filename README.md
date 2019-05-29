XGallery
==========

* Description: Application that allows users to easily create galleris, while still offering a variety of settings, like auto-sliding(on/off), interval, width, height and background color for the carousel, and for each slide you can set the image and caption text with size, color, link.

* Minimal XWiki version supported: 6.2.2

* License: LGPL 2.1


Usage
=====

After installing the extension with EM, go to XCarousel.WebHome

Here click the ADD NEW ENTRY from the Actions section on the right, and give a name to your new carousel.
You will then be prompted to the carousel's edit mode, where you can set it up as you like.
By default the auto-sliding optin will be enabled, and 3 empty slides will be created automatically.
Create or delete as many slides as you want using "Add new slide/Delete Slide" buttons, and set an image for each of your slides.

* Adding an image for each slide is the only mandatory thing to do for the carousel to function.

After the setup is done, you can insert the new carousel into any page using the display macro.

ex: `{{xgallery carousel='Demo'/}}`