# Task
PDF to JSON Converter
This Python application reads a PDF file, extracts structured data from it, and converts this data into JSON format. It utilizes Pydantic for data validation and serialization.

Dependencies
Make sure you have the following dependencies installed:
1.PyMuPDF
2.Pydantic
3.PyPDF2
You can install them using pip:
pip install PyMuPDF pydantic PyPDF2

How to Run:
Clone the repository or download the project files to your local machine.

Navigate to the project directory: cd path/to/your/project/directory
Upload your PDF file:
Place the PDF file you want to convert in the same directory as your Python script (pdf_to_json.py).

Update file paths:
Open pdf_to_json.py and update input_pdf with your PDF file name and output_json with your desired output JSON file name.

Run the script:
Execute the script in your preferred Python environment (Jupyter Notebook, Python script, etc.).

python pdf_to_json.py
Check the output:
After running the script, the structured data extracted from the PDF will be saved as a JSON file (output.json) in the same directory.
