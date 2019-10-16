# EmptyShelfDetection
Empty Shelf detection in supermarket and send details

The following steps are given to run this :
 1. Installations : 
  1) tensorflow
  2) opencv
  3) os
  4) numpy
  5) matplotlib
  6) random
  7) pickle
  8) pytesseract
  9) smtplib
 2. You can skip steps 3 and 4 because the data have stored in pickle form.
 3. Download the training data from this link: https://1drv.ms/u/s!AtGLZaD3uwaBgdZguP0aYaG1sY2oOA?e=KiqKwR
 4. Separate empty And not empty photos and save them if Data/Empty and Data/NotEmpty directory.
 5. Run the CreateData.ipynb if you did steps 3 and 4, this will create the dataset and save in pickle. Otherwise, go to step 6.
 6. Run the BiuldModel.ipynb, this will build a model for this binary classification, accuracy is approx ~90%.
 7. Add email details in Email.ipynb and make sure to do less secure on in your email settings.
 8. Run the Email.ipynb, this will be sent an email if the shelf is empty.
 9. If you want to check another photo then you must rename it in the format "Full_name-price.jpg" in order to send details.
 
 Thanks.
 
