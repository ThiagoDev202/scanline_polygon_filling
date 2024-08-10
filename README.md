AI-GAs-RegClass
Overview

AI-GAs-RegClass is a Python-based project focused on rendering 2D images using advanced shading techniques. The core functionalities include implementing Flat and Gouraud shading methods to visualize geometric shapes with color interpolation. This project is highly relevant for computer graphics, visualization, and AI-related applications that require efficient and accurate rendering of 2D shapes.
Features

    Flat Shading: Implements flat shading where each polygon is shaded with a single color based on the polygon's face normal.
    Gouraud Shading: Implements Gouraud shading for smoother transitions between vertex colors, interpolating colors across polygon surfaces.
    Edge Handling: Manages polygon edges with precise calculations, supporting vertical and non-vertical edges.
    Color Interpolation: Provides linear interpolation of colors across the scanlines of polygons.
    Depth Sorting: Sorts polygons based on depth to ensure proper rendering order.

Technologies Used

    Python: The primary programming language used for the development of rendering algorithms.
    NumPy: Utilized for numerical computations, handling arrays, and performing vectorized operations.
    OpenCV: Employed for image manipulation, particularly for converting and saving rendered images.
    Matplotlib: Used for plotting and visualizing the rendered images during the development process.

Code Structure

    Edge.py: Defines the Edge class, handling polygon edges, calculating slopes, and managing vertex colors.
    render.py: Contains the render function, responsible for orchestrating the rendering process, including depth sorting and shading selection.
    flats.py and gourauds.py: Implement the Flat and Gouraud shading techniques, respectively, to render polygons.
    main.py: The entry point for the project, where the rendering process is executed, and the final image is saved.
    interpolate_vectors.py: Provides functions for linear interpolation of vectors, crucial for color transitions in Gouraud shading.
    Constants.py: Stores constants used throughout the project, such as image dimensions.
