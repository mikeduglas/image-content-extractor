# Image contents extractor
A class that allows an image content extraction (i.e. it removes from the image an area around the "actual" contents).

Below are the original image (with a background around a content) and the cropped one:  
![Original image](https://github.com/mikeduglas/image-content-extractor/blob/master/screenshots/card1.jpg?raw=true)  
![Cropped image](https://github.com/mikeduglas/image-content-extractor/blob/master/screenshots/card1_cropped.jpg?raw=true)  

### Demo program
An utility that extracts image contents (removes a background area around the actual contents).
![Image contents extractor UI](https://github.com/mikeduglas/image-content-extractor/blob/master/screenshots/ice_1.jpg?raw=true)  

### Interactive mode
Run ice.exe to open the utility in UI mode.  
When a user opens an image, the extraction process is running automatically and cropped image is displayed immediately. Adjusting of Color difference level and Line difference level repeats the extraction process with new settings. To save cropped image click Save.

### Command line mode
ice.exe Source=SourceFilePath Target=TargetFilePath [ColorDiffLevel=IntegerValue] [LineDiffLevel=FloatValue]  

Command line parameters:
- Source: source image file
- Target: cropped image file
- ColorDiffLevel: Color difference level (omittable, 7 by default)
- LineDiffLevel: Line difference level (omittable, 2 by default)
  
Example:  
ice.exe Source=.\images\card1.jpg Target=.\images\card1_cropped.jpg

### Requirements
- C6.3 and higher
- ABC and Clarion template chains

### Dependencies
- [gdiplus](https://github.com/mikeduglas/gdiplus)
- [printf](https://github.com/mikeduglas/printf)
- [trackbar](https://github.com/mikeduglas/Trackbar): optional (used in the utility, not required by the class itself).

### Contacts
mikeduglas@yandex.ru

### Price
Contact me directly.

