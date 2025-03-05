# RBF Calculator

A simple Radial Basis Function (RBF) calculator using Tkinter and Matplotlib.

## Features
- Allows users to input sigma values and center points.
- Accepts a list of (x, y) points to compute RBF values.
- Computes squared radii and Gaussian function values.
- Displays results in a tabular format using a Tkinter Treeview.
- Provides a visualization of data points and centers using Matplotlib.

## Requirements
Ensure you have the following dependencies installed before running the application:

```sh
pip install numpy pandas matplotlib
```

## How to Use
1. Run the Python script:
   ```sh
   python main.py
   ```
2. Enter the sigma value in the input box.
3. Specify the center points in the format `x1,y1;x2,y2`.
4. Enter the data points in the text area (one per line in `x,y` format).
5. Click the **Calculate** button to compute the RBF values.
6. View the results in the displayed table.
7. Click on visualization to see a plotted representation of the data.

## Example Input
- **Sigma:** `1`
- **Centers:** `0,0;2.5,2.5`
- **Points:**
  ```
  0,0
  0,2
  0.5,1
  1,0.5
  1,1.5
  1.5,1
  2,0
  2,2
  2,3
  2.5,2.5
  3,2
  3,3
  ```

## Expected Output
- A table displaying `r²` values and corresponding Gaussian function values.
- A visualization of the data points and center locations.

## Screenshot
![RBF Calculator Screenshot](https://raw.githubusercontent.com/BasantSaad/RBF-Calculator/main/screenshot.png)

