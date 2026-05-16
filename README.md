<div align="center">
   <img src="https://github.com/user-attachments/assets/322f81b8-3629-43bf-bde9-f312df7b5823" alt="SpecSheet Logo" width="40%" height="10%">
</div>

<h1 align="center">SpecSheet — Swagger / OpenAPI to Excel Converter</h1>

<p align="center">
  A Lightweight GUI-Based <b>Swagger</b> and <b>OpenAPI Specification Extractor</b> for converting API schemas into structured <b>Excel Sheets</b>.
</p>

<p align="center">
  Built for developers, architects, and documentation workflows to accelerate the extraction and visualization of <b>OpenAPI</b> and <b>Swagger Specifications</b> without manually navigating raw JSON or YAML files.
</p>

<br>

<div align="center">

![Platform](https://img.shields.io/badge/Platform-Windows-blue)
![OpenAPI](https://img.shields.io/badge/OpenAPI-3.x-green)
![Swagger](https://img.shields.io/badge/Swagger-Supported-success)
![License](https://img.shields.io/badge/License-Proprietary-red)
![GUI](https://img.shields.io/badge/GUI-CustomTkinter-purple)

</div>

<br>

---

# What is SpecSheet?

SpecSheet is a `Python-based` desktop application that converts `Swagger/OpenAPI` specifications into clean, structured, and export-ready `Excel` sheets.

The application automatically extracts:
* API Endpoints
* HTTP Methods
* Request Payloads
* Query Parameters
* Path Parameters
* Header Parameters
* Endpoint Summaries
* Request / Response Structures

SpecSheet helps eliminate the manual effort involved in reading raw OpenAPI files and documenting API structures in spreadsheets.
<br>

---

# Key Features

### Swagger / OpenAPI to Excel Conversion
Convert OpenAPI and Swagger specifications into structured Excel spreadsheets with a single click.

### Structured API Documentation Export
Generate organized Excel sheets containing:
* API endpoints
* HTTP methods
* Parameters
* Payload structures
* Endpoint descriptions
* Request body schemas

### OpenAPI JSON and YAML Support
Supports both:
* `.json`
* `.yaml`
Swagger/OpenAPI specification formats.

### Lightweight GUI Application
Simple and intuitive graphical interface built using CustomTkinter.

### Dark Mode and Light Mode
Switch between modern Dark and Light themes for visual comfort.

### Zero Dependency Installation
No Python installation required for end users. Simply download the executable and run the application.

### One-Click Excel Export
Instantly generate `.xlsx` output files for documentation and analysis workflows.
<br>

---

# Installation And Activation
- Download the `SpecSheet.dist.zip` file from the **Official** [**Github Releases Page**](https://github.com/Yashvant-Chhapwale/SpecSheet-Swagger_To_Excel_Converter/releases/tag/v1.0.0).
  ![Releases Page >> Download `SpecSheet.dist.zip`](https://github.com/user-attachments/assets/8949edb7-3c67-4872-a301-7935f4ffe873)<br>
- Open File Explorer and Navigate to the **directory** where **`Specsheet.dist.zip`** has been downloaded.
- **Right-Click** on `SpecSheet.dist.zip` and Choose `Extract All` to **decompress** the archive.
- Open the Extracted folder and **Double-Click** on `SpecSheet.exe` to Launch the Application.
- If prompted with a **Security Warning**, **Click** `Run` to grant the necessary permissions.<br>
  ![Click>>Run](https://github.com/user-attachments/assets/d551337e-58ea-4628-9176-8eefc762c40c)<br>
- Once the Application Starts, **Enter** the `Swagger/OpenAPI URL` into the provided field and **Click** on `Generate SpecSheet`.
<br>

---

# Supported Specification Formats
* Swagger 2.0
* OpenAPI 3.x
* JSON Specifications
* YAML Specifications
<br>

---

# Tech Stack

<div align="center">

<a href="https://docs.python.org/3/">
<img src="https://github.com/user-attachments/assets/f3575d17-400b-4a22-9b4b-6588a1f9ac4d" alt="Python 3" width="20%" height="30%" />
</a>

<a href="https://petstore3.swagger.io/">
<img src="https://github.com/user-attachments/assets/e407ef4b-0b40-4a21-920a-ce2b8efbfffa" alt="Swagger OpenAPI" width="20%" height="30%" />
</a>

<a href="https://github.com/TomSchimansky/CustomTkinter">
<img src="https://github.com/user-attachments/assets/01c7d152-64d5-440a-95bc-3433dafd6876" alt="CustomTkinter GUI Library" width="20%" height="30%" />
</a>

<a href="https://nuitka.net/user-documentation/">
<img src="https://github.com/user-attachments/assets/2dc09c08-880e-403a-9a9b-49f39add2e65" alt="Nuitka Python Compiler" width="20%" height="30%" />
</a>

<br>

<b>Click on a Tool to View its Documentation</b>

</div>

<br>

---

# GUI Snapshots

### Dark Mode:

<img src="https://github.com/user-attachments/assets/ec6a7915-fb70-403d-adc3-2a0e21d58f27" alt="Swagger OpenAPI Excel Generator Dark Mode GUI" width="100%" height="50%" />

<br>

### Light Mode:

<img src="https://github.com/user-attachments/assets/acd7f1f5-53c7-45f4-ae72-3b21cafc7cac" alt="Swagger OpenAPI Excel Generator Light Mode GUI" width="100%" height="50%" />

<br>

---

# Sample Excel Output

<img src="https://github.com/user-attachments/assets/4a8274e3-6d0c-40a3-8ebd-667be73fa432" alt="OpenAPI Swagger Excel Output Example" width="100%" height="50%" />

<br>

---

# Example OpenAPI Datasets

### Sample OpenAPI JSON Link:
[https://petstore3.swagger.io/api/v3/openapi.json](https://petstore3.swagger.io/api/v3/openapi.json)

### Sample OpenAPI YAML Link:
[https://petstore3.swagger.io/api/v3/openapi.json](https://petstore3.swagger.io/api/v3/openapi.yaml)
<br>

---

# Resources and Technologies
- **`Sample OpenAPI_Dataset (JSON URL)`:** **[https://petstore3.swagger.io/api/v3/openapi.json](https://petstore3.swagger.io/api/v3/openapi.json)**
- **`Sample OpenAPI_Dataset (YAML URL)`:** **[https://petstore3.swagger.io/api/v3/openapi.yaml](https://petstore3.swagger.io/api/v3/openapi.yaml)**
- **`Programming Language`:** **[Python 3](https://docs.python.org/3/)**
- **`Excel Generator / Editor`:** **[openpyxl](https://pypi.org/project/openpyxl/)**
- **`JSON_Parser`:** **[pyjson](https://pypi.org/project/pyjson/)**
- **`YAML_Parser`:** **[pyyaml](https://pypi.org/project/PyYAML/)**
- **`HTTP Request_Handler`:** **[requests](https://pypi.org/project/requests/)**
- **`Image_Rendering Tool`:** **[pillow](https://pillow.readthedocs.io/en/stable/)**
- **`GUI_Library`:** **[Custom Tkinter](https://pypi.org/project/customtkinter/)**
- **`Build_Engine`:** **[Nuitka](https://nuitka.net/user-documentation/)**
<br>

---

# Use Cases

SpecSheet can be used for:
* API Documentation Extraction
* Swagger Specification Visualization
* OpenAPI Spreadsheet Generation
* API Schema Export
* Endpoint Inventory Generation
* API Structure Analysis
* OpenAPI Documentation Workflows
<br>

---

# License

SpecSheet is distributed as closed-source proprietary software.

Usage and integration are permitted under the included license agreement, but redistribution, reverse engineering, relicensing, and rebranding are prohibited.
<br>

---

# Discussions and Suggestions

📌 Share your **feedback**, **ideas**, and **feature** suggestions here:
<div align="center">
   
[`To Discussions Page 🚀`](https://github.com/Yashvant-Chhapwale/SpecSheet-Swagger_To_Excel_Converter/discussions/1)
</div>

---
