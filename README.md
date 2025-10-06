# Project-File-Renamer
The File Renamer tool takes a folder path, extracts its name to create a code, and then renames all internal files using that code. It also generates a log (.txt) with the list of original names and the list of renamed names.

---

## How it works

The **File Renamer** automates the process of naming large volumes of documents according to a predefined rule:

1.  **Input:** You provide the path to the folder (directory) containing the files to be renamed.
2.  **Code Generation:** The project takes the **folder name** and uses it to generate a unique code or standardized prefix using the letters in even-numbered positions.
3.  **Renaming:** All files within the folder are renamed en masse using the generated code and adding a "_i" with a different value of i for each filename.
4.  **Log (Output):** A `.txt` file is generated that acts as an **operation catalog**, listing the **original** file names and their corresponding **new** names.

---

### Prerequisites

* Programming language: **Python 3.12.11**
* Environment: **Google Colab**
* Specific libraries: **OS, datetime**
  
---

