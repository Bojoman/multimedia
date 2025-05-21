SAQ & Wavelet Image Compression Demos
This project includes two interactive demos for image compression techniques using JavaScript and HTML5 <canvas>. These demos are designed for educational and experimental purposes and provide visual insight into quantization and wavelet-based compression.

🔹 Files
multimedia.html — Simple SAQ Image Compression
A demo that applies Scalar Amplitude Quantization (SAQ) directly to image pixels. You can:

Upload any image.

Toggle grayscale conversion.

Adjust quantization bit depth (1 to 8).

Compare original and compressed image side-by-side.

View estimated image sizes before and after compression.

Key Features:

Real-time bit depth slider.

Works for both color and grayscale images.

Estimates PNG-compressed size in KB.

compression.html — Wavelet + SAQ Compression
A more advanced demo that applies Haar Wavelet Transform followed by SAQ on each color channel.

You can:

Upload an image (resized to 256×256).

Choose 1-level or 2-level Haar decomposition.

Adjust SAQ bit depth.

View the reconstructed image using inverse Haar transform.

Key Features:

Multi-level wavelet decomposition.

Per-channel compression for color preservation.

Accurate SAQ simulation after wavelet transformation.

🛠 Technologies Used
HTML5 & JavaScript

Canvas 2D API

FileReader API

Haar Wavelet Transform (manual implementation)

📂 Usage
Clone or download the repo.

Open either multimedia.html or compression.html in your web browser.

Upload an image and interact with the sliders/options.

⚠️ Notes
These demos run entirely in the browser — no image data is uploaded or stored.

For best results, use smaller or square images (e.g., 256×256) to reduce processing time.

The Haar transform demo resizes all images to 256×256 for simplicity.

📘 Educational Purpose
These demos are part of a visual learning tool to understand:

Quantization effects

Tradeoffs between compression and quality

How wavelet transforms improve compression efficiency
