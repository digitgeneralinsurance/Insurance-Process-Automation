# UC-01

Evaluate damage from images/video

To minimize the cost involved in manual inspection, calculating claim amount by analyzing images/videos.

UC-01-1)Provide car overlay on the camera launch.
UC-01-2)Capture contour matching event & click image.
UC-01-3)Compare actual & knowledge base image.
UC-01-4)Calculate discrepancy(dimension) of image by calibrating it with knowledge base image. 

# UC-02

To get the user details from vendor websites like car details (color, make, model,engine number, chassis number) & owner details etc. 

UC-02-01) Get the headers from vendor websites.
UC-02-02) Modify headers & add required values.
UC-02-03)Using OCR get captcha string & add to request.
UC-02-04) Create API for getting registration number & return vechiile owning state name
UC-02-05)HTTP request to the vechile owning state
UC-02-06)Create JSON from response object.

# UC-03

Provide user Link to upload the video/Images & store it in mySQL DB identified by claimID

UC-03-1)UI Form with user detail & browse button.
UC-03-02)Pick video from the browsed location.
UC-03-03)Store it as blob in My SQL DB.
UC-03-04)Store Video size, format & claimID in DB.

# UC-04

Get stored video/Image from mySQL DB based on claimID & put it in destination output folder.

UC-04-1)UI Form with claim ID.
UC-04-02)Pick video from the browse location.
UC-04-03)Store it as blob in My SQL DB.
UC-04-04)Store Video size, format & User details in DB.

# UC-05

To get the data related to pricing, IDV, make, model, variant, RTO & premium from the CoverFox.

UC-05-01)Collect JSON data through fiddler from vendor websites like make, model & variantID.
UC-05-02)From VariantID fetch vechileID data from all available make & models.
UC-05-03)From VechileID create dynamic quoteID
UC-05-04)Fetch all data with URL + quoteID
UC-05-05) Store into my SQL database.

# UC-06

Convert a recoreded voice message into text.

UC-06-01) API search which is free ware which provide accurate results.
UC-06-02) Implement the CMUSphnix API.
UC-06-03)Fetch the converted text string.
UC-06-04) Store the converted text in MySQL DB.

# UC-07

To extract data like car, make, model exluding the images present in PDF. 

UC-07-01) Parse the contents of the PDF file like Images, model, make, image. 
UC-07-02) Create the output in JSON or HTML format.

# UC-08

Based on the parameteres from mobile which will be unique will be attached with the user fingure print.

UC-08-01)Find parameters which are common to mobile device.
UC-08-02)Analyze the readings & data points to find unique pattern.
UC-08-03)Store the unique pattern as MFP against that user.

# UC-09

To send user information of claim status, pdf file & update messages on customer's mobile.

UC-09-01)Getting the customer number.
UC-09-02) Send customer information pdf to customer mobile on whats app.


# UC-10

To get the aura of an indivisuals personality based on data scrambling from twitter, Facebook.

Approach is still under discussion.
