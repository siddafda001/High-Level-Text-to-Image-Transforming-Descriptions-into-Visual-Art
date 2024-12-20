# High-Level-Text-to-Image-Transforming-Descriptions-into-Visual-Art

This project explores the conversion of rich-text descriptions into images using state-of-the-art text-to-image models. By extending text prompts beyond plain text and leveraging attributes such as font styles, sizes, colors, and embedded images, this method enhances the flexibility and precision of image generation. The goal is to transform high-level textual descriptions into detailed visual art, allowing for highly customizable and personalized image generation.

## Overview

Traditional text-to-image generation relies on plain text descriptions to guide the generation process. However, this approach lacks the ability to specify attributes like colors, fonts, or the importance of specific parts of the text. This project proposes a solution by using rich-text inputs, which allow for precise control over image attributes such as color, style, and size, ultimately improving the accuracy and detail of the generated images.

## Features

- **Rich-text support**: The system supports rich-text inputs, including font style, size, color, embedded images, and footnotes.
- **Region-based generation**: Text attributes are extracted and applied to specific regions of the image for detailed control.
- **Precise image editing**: The model allows users to edit generated images based on modified rich-text descriptions.
- **Quantitative evaluation**: The project includes a rich-text benchmark for evaluating the performance of text-to-image generation.

## Requirements

To run this project, you will need to set up a Python environment with the necessary dependencies.

### Python version

- Python 3.8+ recommended

### Dependencies

Install the required Python packages from the `requirements.txt` file:

```bash
pip install -r requirements.txt
```

### results

- A lush garden1 with a fountain2. A grand mansion3 in the background. 
- 1A garden is full of vibrant colors with a variety of flowers. 
- 2A fountain made of white marble with multiple tiers. The tiers are intricately carved with various designs. 
- 3An impressive two-story mansion with a royal exterior, white columns, and tile-made roof. The mansion has numerous windows, each adorned with white curtains.

![Screenshot 2024-12-08 203350](https://github.com/user-attachments/assets/cd77871e-cfe7-4da0-8390-0558eeb37c09)

