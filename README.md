# Project Name

## Setup Instructions for Beginners

### Step 1: Install Python and pip

#### Windows
1. **Download Python:**
   - Go to the [Python download page](https://www.python.org/downloads/).
   - Download the latest version of Python for Windows.
2. **Run the Installer:**
   - Run the downloaded installer.
   - **Important:** Check the box that says "Add Python to PATH" before clicking "Install Now."
3. **Verify the Installation:**
   - Open Command Prompt:
     - Press `Win + R`, type `cmd`, and press Enter.
   - Type the following commands and press Enter after each:
     ```bash
     python --version
     ```
     ```bash
     pip --version
     ```
   - You should see the installed versions of Python and pip.

#### Mac
1. **Check Existing Python Installation:**
   - Open Terminal (`Cmd + Space`, type "Terminal," and press Enter).
   - Check the installed Python version:
     ```bash
     python --version
     ```
     or
     ```bash
     python3 --version
     ```
   - MacOS usually comes with Python 2.x pre-installed. You need Python 3.x.

2. **Install Python 3:**
   - Install [Homebrew](https://brew.sh/):
     ```bash
     /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
     ```
   - Install Python 3 using Homebrew:
     ```bash
     brew install python
     ```
   - Verify the installation:
     ```bash
     python3 --version
     ```
     ```bash
     pip3 --version
     ```

### Step 2: Download and Unzip the Project
1. **Download the Project:**
   - Go to the project GitHub page.
   - Click the green "Code" button.
   - Select "Download ZIP" and save the file to your computer.
2. **Unzip the File:**
   - Unzip the downloaded file to a location of your choice.

### Step 3: Set Up the Virtual Environment
1. **Open Terminal/Command Prompt:**
   - On Windows: Open Command Prompt.
   - On Mac: Open Terminal.
2. **Navigate to the Project Folder:**
   - Use the `cd` command to navigate to the unzipped project folder:
     ```bash
     cd path/to/unzipped/project-folder
     ```
3. **Create a Virtual Environment:**
   - **Windows:**
     ```bash
     python -m venv venv
     ```
   - **Mac:**
     ```bash
     python3 -m venv venv
     ```
4. **Activate the Virtual Environment:**
   - **Windows:**
     ```bash
     venv\Scripts\activate
     ```
   - **Mac:**
     ```bash
     source venv/bin/activate
     ```

### Step 4: Install Project Dependencies
1. **Install Dependencies Using pip:**
   - With the virtual environment activated, install the dependencies listed in `requirements.txt`:
     ```bash
     pip install -r requirements.txt
     ```
   - If you're on a Mac and using `pip3`, use:
     ```bash
     pip3 install -r requirements.txt
     ```

### Step 5: Run the Project
1. **Run the Main Script:**
   - Run the project's main Python script:
     ```bash
     python app.py
     ```
