JPEG Image Compression:

This project implements a complete JPEG compression pipeline in Python, starting from an input image matrix and processing it through various stages of the JPEG algorithm. The implementation avoids the use of built-in library functions (except for basic image reading) to give an in-depth understanding of the compression process.

Steps I performed:

- Block-based Compression: Processes the image in 8x8 blocks, as per the JPEG standard.
- Discrete Cosine Transform (DCT): Applies 2D DCT to compress image frequency components.
- Quantization: Reduces image precision to achieve compression.
- Zigzag Ordering: Encodes quantized values into a sequence for efficient run-length encoding.
- Run-Length Encoding (RLE): Compresses sequences of values efficiently.
- Custom Implementation: Avoids external libraries for core computations, focusing on step-by-step development.

File Overview:

-JPEG_Image_Compression.ipynb: Contains the entire implementation of the JPEG compression pipeline with explanations and visualizations.


