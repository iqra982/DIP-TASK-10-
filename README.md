2023-SE-13
# DIP-Task-10
Task 10
This project implements a JPEG-like compression pipeline for color images using OpenCV, NumPy, and Matplotlib within a Google Colab environment. The system processes user-uploaded images by performing 8x8 block-based Discrete Cosine Transform (DCT) and quantization across the R, G, and B channels independently, featuring a Huffman coding demonstration for data encoding. Users can adjust compression strength via a scale_factor variable to analyze the trade-off between file size and quality. The program evaluates performance by calculating the Compression Ratio (CR), Mean Squared Error (MSE), Peak Signal-to-Noise Ratio (PSNR), and Rate-Distortion (RD), while visualizing results through a comparison of the original image, the compressed version, and an amplified difference image to highlight compression artifacts.

