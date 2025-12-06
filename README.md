# OpenCV-Live-Effects-Studio

This project explores real-time image & video processing using OpenCV in C++.
We began with basic webcam streaming and progressively built interactive visual effects that can be toggled using keyboard controls.

Implemented features include:

- Live grayscale, custom grayscale & sepia filters

- Naive vs fast blur comparison

- Sobel edge detection (X, Y & gradient magnitude)

- Cartoon-style filter (blur + edges)

- Blur + quantization for poster effect

 Face detection with selective background blur

- Meme-style overlays (custom captions)

- Record video clips with filters applied

- Depth-based background desaturation effect (DA2 model)

This will help understand pixel-level manipulation, performance trade-offs, and multi-step real-time video processing.

🔧 Requirements
Build Tools

    macOS (12+ recommended: Monterey / Ventura / Sonoma)

    C++17 compatible compiler (Clang)

    CMake ≥ 3.19

Xcode Command Line Tools

    xcode-select --install

Dependencies

    Install via Homebrew:

    brew install opencv
    brew install cmake

Build Instructions

    mkdir build
    cd build
    cmake ..
    make
    ./LiveVideoFilters


macOS may prompt for camera access permission.
Go to System Settings → Privacy & Security → Camera → allow Terminal.

| Key         | Action                     |
| ----------- | -------------------------- |
| `1`-`9`     | Switch effects             |
| `S`         | Save frame                 |
| `R`         | Start/Stop video recording |
| `Q` / `ESC` | Quit                       |
