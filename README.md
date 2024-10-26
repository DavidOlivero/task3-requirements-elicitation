<div align="center">
    <img src="./assets/logo.png" width="700" height="200">
</div>

# Project Documentation for Integration

This project focuses on the implementation of numerical integration methods using the SymPy library of Python. The goal is to provide a detailed guide on how to launch the project and install all the necessary tools.

## Prerequisites

To work with this project, you need to have Python 3.x and Jupyter Notebook installed. Additionally, you need to install the SymPy library and LaTeX for documentation.

## Installation of Tools

### Installation of Python and Jupyter Notebook

To install Python and Jupyter Notebook, follow these steps:
1. Download the Python installer from the official Python website. [Install python here](https://www.python.org/)
2. Run the installer and follow the instructions to install Python.
3. Once Python is installed, open a terminal or command window and run the command `pip install jupyter`. In case you get a permissions error, just run the following command `pip install --user jupyter`

### Installation of SymPy

To install SymPy, run the command `pip install sympy` in a terminal or command window.

### Installation of LaTeX

To install LaTeX, follow these steps:
1. Download the LaTeX compiler called LatexMk from the official LaTeX website. [Install LatexMk here](https://miktex.org/packages/latexmk)
2. If you work in Windows, you must install perl. [Install Perl here](https://strawberryperl.com/) 
3. Run the installer and follow the instructions to install LaTeX.
4. Once LaTeX is installed, make sure the LaTeX compiler is in the system's PATH.

### Installation of TEXStudio or LaTeXWorkshop (for VSCode users)

If you are using TEXStudio or LaTeXWorkshop in VSCode, you need to install these tools to work with LaTeX documents. Follow these steps:

1. Download the TEXStudio editor from the official TEXStudio website. [Install TEXStudio here](https://www.texstudio.org/)
2. Run the installer and follow the instructions to install TEXStudio.
3. If you are using VSCode, you can install the LaTeXWorkshop extension. Open VSCode, go to the Extensions view, and search for 'LaTeX Workshop'. Click on the install button to install the extension.

## Launching the Project

To launch the project, follow these steps:
1. Open a terminal or command window and navigate to the project directory.
2. If you are using VSCode, open the LaTeX document in the LaTeX Workshop extension and select the option "Recipe: latexmk (xelatex)" to compile the document. This project uses xelatex due to custom font settings.
   If you are using TEXStudio, change the settings to use xelatex for compilation.
3. Open Jupyter Notebook and load the associated Jupyter notebook for the project. The Jypyter notebooks they are in the jupyter-validations folde.

## Project Structure

The project is structured as follows:
- `assets`: Contains the project resources, such as images.
- `config`: Contains the LaTeX document associated configuration files.
- `jupyter-validations`: Contains the Jupyter notebooks associated with the project.
- `pages`: Contains the LaTeX documents.

