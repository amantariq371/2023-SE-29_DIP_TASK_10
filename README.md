# 2023-SE-29_DIP_TASK_10
DIP_LAB_10
JPEG-like DCT Compression with Huffman Coding (Color Images)

This Python program demonstrates JPEG-like compression on user-uploaded color images. It divides each channel into 8×8 blocks, applies the Discrete Cosine Transform (DCT), performs quantization using a scaled JPEG matrix, and reconstructs the image using inverse DCT, showing typical compression artifacts. Additionally, it demonstrates Huffman coding on the first channel to simulate entropy coding. The program computes Compression Ratio (CR), Mean Squared Error (MSE), PSNR, and Rate-Distortion (RD) to evaluate compression performance. Finally, it displays the original image, compressed image, and an amplified difference image to visualize the loss caused by compression.

Libraries: OpenCV, NumPy, Matplotlib, Google Colab files
