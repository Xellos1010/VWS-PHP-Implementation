# VWS-PHP-Implementation
These are PHP scripts which use a REST call to Get and Post targets using Vuforia Web Service

Implementation:
Step 1:
Copy all files to a webserver

Step 2 formatting the Image to upload:
You need to add the Binary Data for the jpg or png with a name of theFile

You can upload images by making a Form Submission to imageupload in the following format
(This is the Unity Call)
postForm.AddBinaryData("theFile", bytes, ImageTitle.text+".jpg", "text/plain");
Post Name = theFile
bytes = information for picture in jpg or png format
ImageTitle.text = the title for the photo

Step 3 formatting the meta data:
(This is the Unity Call)
postForm.AddField("meta", BuildMetaData());
Post Name = meta
You can build the data in whatever format you require

I will append this at some point with an html form submission demo since I pulld this from a unity project
