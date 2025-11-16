4D Coupled Mandelbrot Explorer
Interactive prototype using pygame + numba + numpy.

Controls:
  Arrow keys : pan (move the 2D Mandelbrot plane)
  d          : zoom in
  a          : zoom out
  w / s      : move the 3rd dimension (real part of k)
  e          : speed up time
  q          : slow down time
  r          : reverse time
  SPACE      : pause / unpause time
  ESC / close: quit

Requirements:
  Python 3.8+
  pip install numpy numba pygame

Save this file and run: python 4D_Coupled_Mandelbrot_Explorer.py

Notes:
 - It computes a 2D slice where the pixel grid represents the initial c_0 (the usual Mandelbrot plane).
 - The third dimension controls Re(k). The fourth dimension is Im(k) and evolves in time.
 - Coloring uses smooth escape-time and a small palette gradient. Use max_iter/scale values in the code for quality/performance tradeoffs.

This is a single-file prototype meant to be a starting point you can tweak (palette, iterations, performance, etc.).
