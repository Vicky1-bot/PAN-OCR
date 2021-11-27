# PAN-OCR 

The purpose of this project is to efficiently extract the text contained in a PAN Card image and store it in JSON. Herein, we are using the following libraries. The current version 2.0 has been run effectively in October 2018. Any recommendations are welcome. We also need to understand the limitations of by tesseract as it won't run on noisy images with salt & pepper grains and/or poor image quality, i.e. anything below 300 DPI.


<img width="941" alt="image" src="https://user-images.githubusercontent.com/76062756/143671422-b7f52f42-bc5d-40eb-ba45-56154a4b726b.png">


# RESULT:
 result in json format,
 
       {
          "Date of Birth": "16/07/1986",
          "Father Name": "DURAISAMY",
          "Name": "D MANIKANDAN oS",
          "PAN": "BNZPM2501F"
      }
 
# USAGE:
   please visit this link ,You got good practical explanation on this project .
   
 
 
# Future work: 
    
    This model might not be suitable for weighty noise based images.but,we can solve this type of issues with deeplearning approach using pretrained modesl like "YOLO" family, "RCNN" family etc.
