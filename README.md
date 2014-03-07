TitaniumMobileExifData
======================

A straight up Javascript Class for reading EXIF data from either a filepath or a Blob


Easy to use:

Alloy.Globals.EXIF = require("Exif");

||

var EXIF = require("Exif");

Then when you want the EXIF data of any file (string) or blob (TI.Blob);

Just call either

var data = EXIF.fromPath("thefullnativepathtoyourfile.jpg");

or

var data = EXIF.fromBlob(SomeBlobObject);


