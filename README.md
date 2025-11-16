## Project Name- 
Restoring and Enhancing Degraded Text Documents for Reliable OCR
## Project Description-
This project builds a simple, effective image-cleaning pipeline to prepare degraded text documents for OCR. It converts images to grayscale, reduces noise, improves contrast, enhances text with morphology, corrects the background, and then applies OCR to extract clear, readable text.

#### Summary - 
This project introduces a straightforward preprocessing pipeline designed to clean and enhance such images prior to OCR. The pipeline incorporates grayscale conversion, Gaussian filtering for noise reduction, morphological operations for character enhancement, and automatic background correction. Following preprocessing, the cleaned document undergoes OCR for text extraction. The primary objective is to enhance image clarity, thereby enabling more accurate text recognition by OCR systems.


#### Course concepts used - 
1. Grayscale Conversion
2. Morphological Operations
3. Noise Removal 

#### Additional concepts used -
1. OCR
2. Background Correction
   
#### Dataset - 
1. https://users.iit.demokritos.gr/~bgat/HDIBCO2014/benchmark/
2. https://www.kaggle.com/datasets/shaz13/real-world-documents-collections
3. https://www.kaggle.com/competitions/denoising-dirty-documents/data

#### Novelty - 
1. Adapts conventional image processing methods specifically for handwritten and degraded documents.
2. Balancing noise reduction with detail preservation.
3. The pipeline is optimized for uneven lighting and variable ink density, making it robust for diverse document types.
   
### Contributors:
1. Hannah Miriam Shebin (PES1UG23EC114)
2. Shreya Jaideep Save (PES1UG23EC288)
3. H Architha (PES1UG23EC112)

### Steps:
1. Clone Repository
https://github.com/DIP-2025-MINI-PROJECT/Restoring-and-Enhancing-Degraded-Text-Documents-for-Reliable-OCR.git

2. Install Dependencies
Toolboxes:Image processing toolbox,Computer vision toolbox 

    Built-in functions:mread, rgb2gray, im2double, imgaussfilt, imadjust, adapthisteq, imsharpen, imbinarize, bwareaopen, strel, imdilate

3. Run the Code
   Matlab Code: Code_Restoration of Degraded Text Documents.mlx

### Outputs:
  Important intermediate steps:
  
  1.Ensure above mentioned toolboxes are installed correctly
  
  2.Ensure given input image and its path are correct in the code
  
  Final output images

### References:
1. https://ieeexplore.ieee.org/document/10134173 - A Review on Enhancement Techniques for Historical Document Images Using Binarization
2. https://www.researchgate.net/publication/294727398_History_Document_Image_Background_Noise_and_Removal_Methods - Document Image Background Noise and Removal Methods
3. https://www.mdpi.com/2079-9292/13/7/1394 - A Review of Document Binarization: Main Techniques, New Challenges, and Trends
 
### Limitations and Future Work:
Limitations:
Fixed Parameter Approach,Poor Performance on Severely Degraded Documents,No Layout or Structure Preservation

Future Work:
Deep Learning Integration,Intelligent Post-Processing,Multi-Script and Layout Analysis
