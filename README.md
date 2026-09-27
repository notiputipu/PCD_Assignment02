# Pencitraan digital 2 - simple version

This version follows the supplied example's basic approach: one low-contrast image,
histogram equalization, and before-and-after histograms. There are no mathematical
derivations, PSNR calculations, or SSIM calculations.

1. Extract the full ZIP.
2. Run `python -m pip install -r requirements.txt`.
3. Open `Pencitraan digital 2.ipynb` in Jupyter, VS Code, or Colab.
4. Make sure the working directory is the extracted project folder, then run all cells.
5. Fill in your name and student ID and review the observations before submission.

For a standalone run from the project folder: `python image_enhancement_simple.py`.
Jupyter or your notebook editor is installed separately. In Google Colab, upload and
extract the ZIP, then change to the extracted `Pencitraan_digital_2_Simple` directory.

The notebook contains executed outputs. The `images` folder contains the input,
source photograph, grayscale copy, and enhanced result. The `figures` folder contains
histograms and the combined comparison. The PDF contains a short analysis report.

The input is a simulated low-contrast grayscale derivative of NASA's Eileen Collins
photograph, distributed as the public-domain scikit-image astronaut sample.
https://scikit-image.org/docs/stable/api/skimage.data.html#skimage.data.astronaut

The uploaded example refers to city.jpg, which was not attached. This project uses
the same sample photograph as the earlier Pencitraan digital 2 version. The name and
student ID from the example were not copied. If you change the image, update the
observations to match your own result.
