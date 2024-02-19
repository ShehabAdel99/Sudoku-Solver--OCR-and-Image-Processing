# Sudoku Solver: OCR and Image Processing


This project presents a Sudoku solver that combines Optical Character Recognition (OCR) and image processing techniques to solve Sudoku puzzles extracted from images. Leveraging OCR capabilities, the program detects the Sudoku grid and its digits, enabling efficient puzzle solving using computer vision algorithms.


## Key Features


- Preprocessing: Various preprocessing techniques are applied to the input image to enhance the clarity of the Sudoku grid and digits. These techniques include grayscale conversion, noise reduction, and contrast adjustment.

- Grid Extraction: The program employs the Hough Transform algorithm along with edge detection methods to accurately detect the lines of the Sudoku grid. Morphological operations are also applied to refine the grid detection results.

- Number Extraction: Template matching techniques are utilized to identify individual digits within each cell of the Sudoku grid. 

- Sudoku Solving: A backtracking algorithm is implemented to solve the Sudoku puzzle extracted from the image. This algorithm efficiently explores possible solutions while adhering to Sudoku rules, enabling the program to find the correct solution.

- Visualization: Provides visualizations of intermediate steps such as preprocessing, grid detection, and number extraction.

## Getting Started



1) Installation:

   - Clone the repository.
   - Install required dependencies using pip install -r requirements.txt.

2) Usage:

   - Run the main script sudoku_solver.py, providing the input image path as an argument.
   - Adjust parameters in the script for different preprocessing and processing options.

3) Example:


```
python sudoku_solver.py --image_path /path/to/input/image.jpg
```

## Dependencies
 - Python 3.x
 - OpenCV
 - NumPy
 - Matplotlib



## Authors

- Shehab Adel Ramadan
- Omar Tarek Mohamed

## Acknowledgments
- Special thanks to [OpenCV](https://opencv.org/) & [NumPy](https://numpy.org/) for their invaluable contributions.
- Inspired by various Sudoku solver implementations and computer vision projects.
