# PDFSegmenter

This is a Spring Boot web application that allows users to upload a PDF file, segment the PDF based on gaps between paragraphs, and automatically download the segmented PDF files as a ZIP archive.

# Features:-
Upload a PDF file through the web interface.
Segment the PDF into multiple files based on the spacing between paragraphs.
Automatically download the segmented files in a ZIP format.
No need to navigate to a separate page for downloading—download begins automatically after the upload is complete.

# Technology Stack
Java: Core language
Spring Boot: Web framework
Thymeleaf: Template engine for rendering HTML views
Apache PDFBox: For processing and manipulating PDF files
Maven: Build automation tool

# Requirements
Java 17 or higher installed on your system.
Maven installed to build the project.
Apache PDFBox dependency for PDF manipulation.
Basic knowledge of running Spring Boot applications.

# Setup Instructions
1.Clone the repository:
git clone https://github.com/jainrishabh2310/PDFGEN.git
cd PDFGEN

2.Build the Project:
Ensure Maven is installed on your system. Run the following command to download dependencies and build the project:
mvn clean install

3.Run the Application:
Once the build is complete, you can run the application using the following command:
mvn spring-boot:run


# How to Use the Application
  Upload a PDF File:

Click the "Choose File" button and select a PDF from your computer.
Press the "Upload PDF" button.
Automatic ZIP Download:

After you upload the PDF, the application will segment it based on paragraph gaps.
Once segmentation is complete, the segmented files will automatically be downloaded as a ZIP file to your computer.
Example:

You upload a PDF file named example.pdf.
The app segments the PDF into multiple parts (e.g., output_paragraph_1.pdf, output_paragraph_2.pdf).
The app automatically generates a ZIP file named segmented_pdfs.zip that contains these segmented PDF files.
The ZIP file is downloaded automatically to your machine.



