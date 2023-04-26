# Eye Vein Detection In Python

Eye Vein Detection is a Python script that detects and highlights the veins in an eye image using OpenCV. This script can be useful for medical professionals, researchers, and anyone interested in studying the veins in the eye.

## Installation

To use this script, you must have Python 3.x and OpenCV 4.x installed on your system. If you do not have them installed, you can install them by following the steps below:

- Install Python 3.x from the official website: https://www.python.org/downloads/
- Install OpenCV 4.x using pip:
    
    ```bash
    pip install opencv-python==4.6.0.66
    ```

Next, clone this repository to your local machine using the following command:
    
    ```bash
    git clone https://github.com/SahSofts/EyeVeinDetection.git
    ```

Next, navigate to the repository folder and install the required dependencies using pip:
    
    ```bash
    cd EyeVeinDetection
    pip install -r requirements.txt
    ```

## Usage

To use this script, you must provide it with eye images to analyze. The images must be in JPG format and stored in a folder called images within the repository folder.


1. Install the required `opencv-python` module using the command `pip install opencv-python`.

2. Download or clone the repository.

3. Open the `EyeVeinDetection.ipynb` Jupyter notebook file using Jupyter Notebook or JupyterLab.

4. Run the cells in the notebook file.

5. The output will be displayed in the notebook itself. The script will display the original eye image with green marks of detection on the image's veins, and alongside it, it will display another image with all detected veins in white.

Note: If you want to use this code in a Python script or module, simply copy the relevant code cells from the notebook into a Python file with a `.py` extension, and add the required import statements for the `opencv-python` module. Remember to remove any unnecessary cells that may cause errors when running the script.