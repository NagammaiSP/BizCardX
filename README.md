EasyOCR: Effortless Text Extraction
EasyOCR, a Python package, simplifies the OCR process by providing a hassle-free method for extracting text from images and scanned documents. Its ease of installation and minimal dependencies make it an ideal choice for OCR tasks.

Key Features of EasyOCR:
Simple Installation: Install EasyOCR with a single pip command.
Minimal Dependencies: Requires minimal dependencies, facilitating a smooth setup process.
Easy Integration: Easily integrate EasyOCR into your project with just one import statement.
Straightforward Usage: With only two lines of code, you can perform OCR effortlessly.

Project Overview
BizCardX offers a user-friendly interface for extracting and managing business card data efficiently. The tool employs EasyOCR for text extraction, followed by classification using regular expressions. Users can interact with BizCardX through a Graphical User Interface (GUI) built with Streamlit.

Key Components of BizCardX:
GUI Interface: Provides an intuitive interface for users to upload business card images and extract information.
Data Classification: Utilizes regular expressions to classify extracted text into relevant categories such as company name, contact details, etc.
Database Integration: Stores extracted data in a MySQL database, allowing users to easily manage and retrieve information.

Getting Started
To start using BizCardX, follow these simple steps:

Install Dependencies: Install the required libraries using the following pip command:

pip install streamlit easyocr mysql-connector-python pandas 
Execute BizCardX: Run "Bizcard.py" using the streamlit run command:

streamlit run Bizcard.py
Usage: Upon execution, a webpage will be displayed in your browser with options to upload business card images and perform extraction. Follow the on-screen instructions to extract and manage business card data effortlessly.

Libraries/Modules Used
Pandas: Used for creating a DataFrame with scraped data.
mysql.connector: Facilitates storing and retrieving data from the MySQL database.
Streamlit: Utilized for creating the graphical user interface.
EasyOCR: Employs text extraction from images.

Workflow
BizCardX follows a straightforward workflow:

Upload & Extract: Users upload business card images via the GUI interface, and EasyOCR extracts text from the images.
Data Classification: Extracted text is classified using regular expressions to identify relevant information.
Data Storage: Classified data is stored in the MySQL database for easy retrieval and management.
