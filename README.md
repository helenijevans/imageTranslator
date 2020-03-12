# imageTranslator

The ultimate plan for this project is to read in images and translate any text found within. 
The primary use for this would be in foreign countries to read signs.

At the moment, working on getting OpenCV to detect and output strings of Latin-Alphabet text it finds in images.

Results from testing current program:
* Can read text from fed-in font types with a 100% accuracy rate
* The closeness of characters doesn't affect the above behaviour
* Can't read with 100% accuracy for texts outside of trained fonts
* Accuracy worsens with more cursive fonts
