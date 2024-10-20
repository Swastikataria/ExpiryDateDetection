# ExpiryDateDetection

Overview

This OCR model is designed to accurately detect expiry or manufacturing dates from product labels, calculate the remaining days until expiry, and highlight relevant keywords such as "best before," "expiry date," and similar terms. It is capable of recognizing various date formats and efficiently processing images to extract essential date information.

Features
- Image Processing: After capturing images of product packaging, Preprocessing techniques such as binarization and Gaussian blur for noise reduction are applied to improve the OCR accuracy. 
- Expiry Date Detection: The model can identify dates from various formats, including standard numeric dates (e.g., dd/mm/yyyy), text-based dates, and ambiguous formats (e.g., 040917).
- Keyword Identification: It detects keywords like "best before" or "expiry date" to locate relevant product information.
- Remaining Days Calculation: For identified expiry dates, the model calculates the number of days remaining until the product expires, displaying "Expired" if the date has passed.


![image](https://github.com/user-attachments/assets/a820b8f3-6657-4b23-a419-5278ea55136f)
