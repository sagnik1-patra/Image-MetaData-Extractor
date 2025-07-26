 Image Metadata Extractor
A simple Python tool to extract metadata (filename, format, mode, size) from images stored in a file or a folder. It supports various image formats like .png, .jpg, .jpeg, .bmp, .gif, and .tiff.

 Features
Extract metadata from a single image or all images in a folder.

Supports most common image formats.

Handles errors gracefully.

Automatically trims surrounding quotes from paths.

Command-line input.

 Project Structure
bash
Copy
Edit
Image-Metadata-Extractor/
│
├── extractor.py          # Main script to extract metadata
├── README.md             # Project documentation
 Requirements
Python 3.6+

Pillow

Install required package:

bash
Copy
Edit
pip install Pillow
 How to Run
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/yourusername/Image-Metadata-Extractor.git
cd Image-Metadata-Extractor
2. Run the Script
bash
Copy
Edit
python extractor.py
3. Provide Input When Prompted
Example:

mathematica
Copy
Edit
 Enter full path of image or folder: C:\Users\sagni\Downloads\Image Metadata Extractor\Images\airplane
 You can also provide quoted input, like:

arduino
Copy
Edit
"C:\Users\sagni\Downloads\Image Metadata Extractor\Images\airplane"
 Sample Output
bash
Copy
Edit
 Extracted Metadata:
{'filename': 'image1.jpg', 'format': 'JPEG', 'mode': 'RGB', 'size': (128, 128)}
{'filename': 'image2.png', 'format': 'PNG', 'mode': 'RGBA', 'size': (256, 256)}
 Future Features (Optional)
Save extracted metadata to CSV or JSON

GUI version using Tkinter or PyQt

Add support for EXIF data

 Author
Sagnik Patra
Built using Python and Pillow.
