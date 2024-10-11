# Urine Test Dipstick Reader

This project is designed to process images of urine test dipsticks, detecting specific areas on the dipstick to analyze the results. The program identifies different regions on the dipstick.

## Features

- **Colored Region Detection**: Identifies specific colored regions on the dipstick based on predefined color ranges for test results.
- **Black Rectangle Detection**: Detects black rectangular regions or borders on the dipstick for alignment or reference.
- **Text Detection**: Detects and highlights any relevant text or labels on the dipstick.
- **QR Code Detection**: Identifies any QR codes on the dipstick or packaging for scanning additional information.
- **Shape Selection**: Detects regions with specific shapes, particularly rectangles, to assist in determining test result areas.
- **Circle Detection**: Identifies circular regions in the image for additional test readings.
- **Final Processed Image**: The output is an image with all detected areas marked, which helps in reading the dipstick results accurately.

## Installation

To run this project, ensure the following dependencies are installed:

- Python 3.x
- OpenCV (`pip install opencv-python`)
- NumPy (`pip install numpy`)
- Matplotlib (`pip install matplotlib`)

## Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/yousraa21/Urine-Test-Dipstick-Reader.git
