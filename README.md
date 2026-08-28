# IMN - Digital Image Processing Labs

Lab exercises for the Digital Image Processing course (Traitement des Images Numeriques), fourth-year Computer Science (2CS).

## Labs

| Lab | Topic | Key techniques |
|-----|-------|----------------|
| TP1 | Image Basics | Format conversion (PNG/JPEG/TIFF), channel decomposition, histogram, HSV |
| TP2 | Filtering & Fourier | Noise simulation, low/high-pass, median, sharpening, DFT analysis |
| TP3 | Histogram & Edges | Manual equalization, Sobel, frequency-domain filtering, morphology |
| TP4 | Image Restoration | Wiener filter, Richardson-Lucy deconvolution, CLAHE, inpainting |
| TP5 | Motion Detection | Recursive mean, Richefeu algorithm, MOG2, optical flow |

## Setup

```bash
pip install numpy pillow opencv-python scipy scikit-image matplotlib
```

## Running

Each lab is a self-contained Jupyter notebook. Open the relevant folder and launch it:

```bash
cd TP1
jupyter notebook TP1.ipynb
```

All images and video files required by each lab are already included in their folder. Generated outputs (`.avi` video masks, converted images) are excluded from version control and will be produced when you run the notebooks.

## Structure

```
IMN/
├── TP1/   image.png
├── TP2/   image.jpg  cameraman.jpg  trui.png
├── TP3/   cameraman.jpeg  thumb_pout.png  trui.png
├── TP4/   lena.jpg  noisy.jpg  02av.jpg
└── TP5/   video.mp4
```
