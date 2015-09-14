# Desktop
PythonANPR
This is a collection of functions written specifically for locating letters from a license plate.
For now it only works on 6 character license plates with a quite high accuracy.
The reading of the characters is done via Pytesseract.
The code as is can be run on any computer with the right dependency's.
The output is a print of the found characters in the license plate.

Things to do:

- Remove dependency on pytesseract and build it with the normal Tesseract version so I can specify which characters to drop etc.
- Expand the code to add a function that creates a ROI for the characters
- Make a robust heuristic for a rough location of the license plate (different ROI approach)
- Streamline the code and remove unnecessary stuff.
