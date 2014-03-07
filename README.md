TitaniumMobileExifData
======================

A straight up Javascript Class for reading EXIF data from either a filepath or a Blob


Easy to use:

Alloy.Globals.Exif = require("Exif");

||

var Exif = require("Exif");

Then when you want the EXIF data of any file (string) or blob (TI.Blob);

Just call either

var data = Exif.fromPath("thefullnativepathtoyourfile.jpg");

or if you have the file loaded (e.g. from the Gallery)

var data = Exif.fromBlob(SomeBlobObject);


For nicely formatted output try:

console.log(Exif.pretty(Exif.fromPath("thefullnativepathtoyourfile.jpg")));
