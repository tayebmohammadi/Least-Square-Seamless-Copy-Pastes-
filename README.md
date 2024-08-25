## Project: Least Squares & Seamless Copy/Paste (CS70 PA3)

### Overview
This project implements a technique for gradient-domain image processing, focusing on "Poisson Blending." The goal is to blend an object or texture from a source image into a target image seamlessly. The approach preserves the gradient of the source region, ensuring that the blended image avoids noticeable seams.

### Files
- **`PA3.ipynb`**: The main notebook containing the problem description, background information, and implementation of the least squares solver.
- **`images/`**: Directory containing example images used in the project.

### Installation
1. Install [Anaconda](https://www.anaconda.com/products/individual) with Python 3.8.
2. Clone the repository.
3. Install required libraries using `pip install -r requirements.txt` (if needed).

### Usage
1. Open `PA3.ipynb` in Jupyter Notebook.
2. Follow the instructions in the notebook to implement and test the least squares solver for gradient-domain image processing.

### How It Works
- **Least Squares Solver**: Implements a least squares solution to blend an image into a background while preserving the gradient.
- **Testing**: The notebook includes test cases to validate the correctness of the implementation.
- **Poisson Blending**: The final section applies the method to blend an object image into a target image interactively.

### Notes
- This project must be completed individually as per course guidelines.
- Ensure the correct Python environment is used for consistency with the provided code.
