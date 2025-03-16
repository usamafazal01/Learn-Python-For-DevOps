# How to Install Python on Windows

## Step 1: Download Python
1. Go to the official Python website: [https://www.python.org/downloads/](https://www.python.org/downloads/)
2. Click on the **Download Python** button (the latest version will be shown).
3. Once the file is downloaded, open it.

## Step 2: Install Python
1. In the installer, check the box **Add Python to PATH** (important for running Python from the command line).
2. Click **Install Now**.
3. Wait for the installation to complete.
4. Click **Close** after the installation is finished.

## Step 3: Verify Python Installation
1. Open **Command Prompt** (Press `Win + R`, type `cmd`, and press `Enter`).
2. Type the following command and press `Enter`:
   ```sh
   python --version
   ```
3. If Python is installed correctly, it will show the installed version.

---

# How to Run Python on GitHub

## Step 1: Create a GitHub Repository
1. Go to [https://github.com/](https://github.com/) and log in.
2. Click on **New repository**.
3. Name your repository (e.g., `My-Python-Project`).
4. Select **Public** or **Private** as per your preference.
5. Click **Create repository**.

## Step 2: Upload Python Files
1. Open your repository and click on **Add file** > **Upload files**.
2. Click **Choose your files**, select your Python scripts (`.py` files), and upload them.
3. Click **Commit changes**.

## Step 3: Run Python on GitHub Codespaces
1. Inside your GitHub repository, click on **Code** > **Codespaces**.
2. Click **Create codespace on main**.
3. Wait for the Codespace environment to start.
4. Open the terminal and run:
   ```sh
   python filename.py
   ```

---

# How to Run Python on Google Colab

## Step 1: Open Google Colab
1. Go to [https://colab.research.google.com/](https://colab.research.google.com/).
2. Click **New Notebook**.

## Step 2: Write Python Code
1. Click on the first code cell.
2. Type any Python code, for example:
   ```python
   print("Hello, Google Colab!")
   ```
3. Click the **Run** button (or press `Shift + Enter`).

## Step 3: Upload and Run Python Files
1. Click **Files** (on the left panel).
2. Click **Upload** and select your `.py` file.
3. Run the file using:
   ```python
   !python filename.py
   
