# Retrieval-of-Medical-Imaging-Records
DICOM Image Viewer and Metadata Extractor
This Google Colab notebook provides a comprehensive solution for downloading, visualizing, and extracting metadata from DICOM (Digital Imaging and Communications in Medicine) medical images.

Features
Library Installation: Automatically installs necessary Python libraries (pydicom, matplotlib, requests).
DICOM Loading: Demonstrates how to load a sample DICOM file, either from a URL or using a built-in pydicom test file.
Image Visualization: Visualizes the DICOM image using matplotlib, applying appropriate colormaps and handling different PhotometricInterpretation values.
Metadata Display: Extracts and displays relevant DICOM metadata tags, including patient information, study details, image dimensions, and acquisition parameters.
How to Use
Open in Google Colab: Click the "Open in Colab" badge (if available) or upload this .ipynb file to your Google Drive and open it with Google Colaboratory.
Run All Cells: Execute all cells in the notebook sequentially. The notebook is designed to guide you through each step.
The first cell will install the required libraries.
The second cell will load a sample DICOM file. Initially, it attempts to download a file from a URL. If external download issues persist, it falls back to using a stable test file from the pydicom library itself.
Subsequent cells will display the image and its metadata.
Explore: Examine the output of each cell to understand the image visualization and the extracted metadata.
Libraries Used
pydicom: A Python package for working with DICOM files.
matplotlib: A powerful plotting library for Python, used here for image visualization.
requests: An elegant and simple HTTP library for Python, used for downloading DICOM files from URLs.
os: Python's built-in module for interacting with the operating system, used for file path manipulations.
Sample DICOM Data
The notebook uses a sample DICOM file. Initially, it tries to fetch from external URLs, but if these prove unstable, it defaults to pydicom.data.get_testdata_file("CT_small.dcm") to ensure consistent execution. This test file is a small CT image.

Contribution
Feel free to fork this notebook, make improvements, or adapt it for your specific DICOM processing needs.
