
# Segment Anything Model (SAM) for Image Segmentation

This repository demonstrates the use of Meta's Segment Anything Model (SAM) for versatile image segmentation tasks. This project showcases two use cases:
1. **Default Implementation of SAM** — Applying the model to a variety of image datasets with point-based or bounding-box-based segmentation.
2. **Satellite Image Segmentation Use Case** — Adapting SAM to the specific domain of satellite imagery for environmental and urban analysis.

## Table of Contents
- [Overview](#overview)
- [Installation](#installation)
- [Usage](#usage)
  - [Default SAM Implementation](#default-sam-implementation)
  - [Satellite Image Segmentation](#satellite-image-segmentation)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Overview

This repository contains code to install and use SAM for different segmentation tasks. The key features include:
- Loading pre-trained SAM models.
- Applying SAM to various images using point-based or bounding-box-based segmentation.
- Custom use case of **satellite imagery segmentation**, demonstrating SAM's flexibility.

## Installation

To get started, clone the repository and install the dependencies.

### 1. Clone the repository
\`\`\`bash
git clone https://github.com/your-username/segment-anything-satellite.git
cd segment-anything-satellite
\`\`\`

### 2. Install Dependencies
\`\`\`bash
pip install git+https://github.com/facebookresearch/segment-anything.git
pip install opencv-python matplotlib
\`\`\`

### 3. Download Pre-trained Model Checkpoint
You need to download the SAM pre-trained model checkpoint.
\`\`\`bash
wget https://dl.fbaipublicfiles.com/segment_anything/sam_vit_h_4b8939.pth
\`\`\`


## Results

- **Default SAM Implementation:** Applied on objects like cars, groceries, and people for object segmentation.
- **Satellite Image Segmentation:** Segmented different regions of a satellite image, showcasing SAM's flexibility in environmental monitoring and analysis.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request with improvements, new use cases, or bug fixes.

