This project implements background removal using the Segment Anything Model (SAM) and a user-friendly interface built with Gradio. The system provides three different modes:

1. Single Object Selection

    Upload an image and click on the object you want to keep.
    The system automatically generates an output image with only the selected object and a transparent background.

2. Multi-Point Object Selection

    Upload an image and click on multiple parts of the object you want to keep.
    Each click adds a point to the selection, refining the area to segment.
    A "Clear Points" button is available to reset the selected points.
    Once satisfied, click "Segment Object" to get the output image with the object and transparent background.

3. Multi-Object Retrieval

    Upload an image and click on different objects to select them; each click adds to the "Selected Points" list.
    Clicking "Segment Objects" retrieves all selected objects and removes the background, showing them in the final output.