# AUTOMATED_REPORT_GENERATION

*COMPANY*: CODTECH IT SOLUTIONS PVT.LTD

*NAME*: Amol Hanmantrao Shrirame

*INTERN ID*: CT06DM767

*DOMAIN*: B.Tech CSE (Computer Science and Engineering)

*DURATION*: 6 WEEKS

*MENTOR*: NEELA SANTOSH

## DESCRIPTION


### Step 1: Install VS Code and Python

If you haven't already, download and install:

1.  **Visual Studio Code (VS Code):**
     Go to: [https://code.visualstudio.com/](https://code.visualstudio.com/)
     Download and install the appropriate version for your operating system.
2.  **Python:**
    * Go to: [https://www.python.org/downloads/](https://www.python.org/downloads/)
    * Download and install the latest stable version of Python (e.g., Python 3.9+). Make sure to check the box that says "Add Python to PATH" during installation.

### Step 2: Install VS Code Extensions

Open VS Code and install the essential extensions for Python development:

1.  Go to the Extensions view by clicking on the square icon on the sidebar (or press `Ctrl+Shift+X`).
2.  Search for `Python` and install the extension by Microsoft (it's usually the first one). This extension provides rich features like IntelliSense, linting, debugging, and more.

### Step 3: Create Your Project Folder

It's good practice to organize your files in a dedicated project folder.

1.  Create a new folder on your computer, for example, `AutomatedReportProject`.
2.  Open VS Code.
3.  Go to `File` > `Open Folder...` (or `Ctrl+K Ctrl+O`) and select the `AutomatedReportProject` folder you just created.

### Step 4: Set Up a Virtual Environment (Recommended)

A virtual environment isolates your project's dependencies from other Python projects, preventing conflicts.

1.  Open the **Integrated Terminal** in VS Code:
    * Go to `Terminal` > `New Terminal` (or `Ctrl+Shift+``).
2.  Create a virtual environment (named `venv` by convention):
    ```bash
    python -m venv venv
    ```
3.  Activate the virtual environment:
    * **On Windows:**
        ```bash
        .\venv\Scripts\activate
        ```
    * **On macOS/Linux:**
        ```bash
        source venv/bin/activate
        ```
    You'll see `(venv)` in your terminal prompt, indicating that the virtual environment is active.
4.  **Select the Python Interpreter:** VS Code usually detects the virtual environment. If not, click on the Python version in the bottom-right corner of the VS Code status bar and select the interpreter located inside your `venv` folder (e.g., `.\venv\Scripts\python.exe` on Windows).

### Step 5: Install Required Libraries

For this task, you'll primarily need `fpdf` for PDF generation and `pandas` for data handling.

1.  With your virtual environment active in the terminal, install the libraries:
    ```bash
    pip install fpdf pandas
    ```
2.  Create a `requirements.txt` file (optional but good practice for sharing your project):
    * In the terminal, run:
        ```bash
        pip freeze > requirements.txt
        ```
    This file will list all the libraries and their versions your project depends on.

### Step 6: Prepare Your Data

You'll need some sample data to work with. Let's create a simple CSV file.

1.  Inside your `AutomatedReportProject` folder, create a new folder named `data`.
2.  Inside the `data` folder, create a new file named `sales_data.csv`.
3.  Add the following content to `sales_data.csv`:

    ```csv
    Product,Category,Sales,Units,Date
    Laptop,Electronics,1200,1,2024-01-05
    Mouse,Electronics,25,2,2024-01-05
    Keyboard,Electronics,75,1,2024-01-06
    Monitor,Electronics,300,1,2024-01-07
    Pen,Stationery,5,10,2024-01-08
    Notebook,Stationery,10,5,2024-01-08
    Chair,Furniture,150,1,2024-01-09
    Table,Furniture,200,1,2024-01-09
    Desk Lamp,Electronics,40,2,2024-01-10
    ```

### Step 7: Write the Python Script (`report_generator.py`)

Now, let's write the Python code that reads, analyzes, and generates the report.

1.  In your `AutomatedReportProject` folder, create a new file named `report_generator.py`.
2.  Add the following Python code to `report_generator.py`:
 Use the file which is given to you file name : generate_report
### Step 8: Run the Script

1.  Open the Integrated Terminal in VS Code (if it's not already open: `Ctrl+Shift+``).
2.  Ensure your virtual environment is active (you should see `(venv)` in the prompt).
3.  Run the Python script:
    ```bash
    python report_generator.py
    ```
4.  You'll see output in the terminal indicating the script's progress.

### Step 9: View the Generated Report

1.  After the script finishes, a new folder named `reports` will be created in your `AutomatedReportProject` directory.
2.  Inside `reports`, you will find `sales_performance_report.pdf`.
3.  You can open this PDF directly from VS Code's file explorer by clicking on it, or navigate to the folder on your system and open it with your default PDF viewer.

**OUTPUT**:

![Image](https://github.com/user-attachments/assets/dda9e091-c033-409d-8bc4-2464da7686c4)

