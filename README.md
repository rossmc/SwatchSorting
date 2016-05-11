# Magento Swatch Sorting
#### Overview
The configurable swatches feature which was added in Magento 1.9 does not sort the swatches by position set in the Magento admin panel. For instance  such as size are often ordered incorrectly, i.e. M, XL, S, L. This module rectifies this.

Credit for this solution should go to @Harshit who gave his solution on [stackoverflow](http://stackoverflow.com/a/28867699/1814446), I've simply just put it into a module so that it can be added easily to any Magento store without the need to override core Magento files.  The module uses the preferred method of class rewrites for updating Magento core files.

#### Installation
* Download latest version [here](https://github.com/rossmc/SwatchSorting/archive/master.zip). 
* Unzip to Magento root folder.
* Clear cache.
* The configurable swatches will now be ordered by the attribute's options poistions