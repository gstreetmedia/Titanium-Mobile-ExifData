Titanium Mobile Exif Data
==========================

A straight up Javascript Class for reading EXIF data from either a filepath or a Blob


Easy to use:

Alloy.Globals.Exif = require("Exif");

||

var Exif = require("Exif");

Then when you want the EXIF data of any file (string) or blob (TI.Blob);


For a filepath (ie nativePath)

var data = Exif.fromPath("thefullnativepathtoyourfile.jpg");


For a Ti.Blob (e.g. from the Gallery)

var data = Exif.fromBlob(SomeBlobObject);


For nicely formatted output try:

console.log(Exif.pretty(Exif.fromPath("thefullnativepathtoyourfile.jpg")));
