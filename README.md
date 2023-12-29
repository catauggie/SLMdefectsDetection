# Predicting Defects in SLM-Produced Parts Based on Melt Pools Clustering Analysis

## Overview

This repository contains the code and data related to the paper titled "Predicting Defects in SLM-Produced Parts Based on Melt Pools Clustering Analysis." The paper explores a novel approach to defect prediction in Selective Laser Melting (SLM) by leveraging advanced clustering analysis of melt pools.

## Repository Structure

- **load_process_tsne_clust.ipynb**:  facilitates the analysis of video data for predictive clustering using t-SNE. The key steps include:

1. **Load Video Frames:** The notebook begins by loading frames from a specified video folder, preparing them for subsequent processing.

2. **Conversion to Images:** The frames are then converted into images, creating a visual dataset suitable for analysis.

3. **Random Frame Selection:** To manage computational efficiency, 50,000 random frames are selected from the dataset for further analysis.

4. **Vectorization:** The selected frames are vectorized to convert visual information into numerical representations, a crucial step for applying machine learning techniques.

5. **t-SNE Application:** t-SNE (t-Distributed Stochastic Neighbor Embedding) is applied to the vectorized frames, enabling effective clustering for further insights.

The notebook provides a streamlined pipeline for video data preprocessing and clustering analysis, offering a foundation for predictive modeling in the context of additive manufacturing processes.

- **XYPT parsing.ipynb**: This Jupyter Notebook serves the purpose of exploring and visualizing video data coordinates for randomly selected frames. The main functionalities include:

1. **Random Frame Coordinates:** The notebook employs a method to locate the coordinates of randomly selected frames, providing spatial insights into the video data.

2. **Layer Visualization:** It includes visualizations for exploring different layers within the video frames, enhancing the understanding of the additive manufacturing process.

3. **Defect Visualization:** The notebook further offers visualizations focusing on defect detection within the video frames, aiding in the identification and analysis of potential manufacturing issues.

This file is an essential component in the analysis pipeline, offering a visual representation of key data points and defects, contributing to a comprehensive understanding of the additive manufacturing process.

- **`README.md`**: The main README file providing an overview of the repository.

## Getting Started

### Prerequisites

- Jupyter Notebook

### Installation

1. Upload the repository: `git clone https://catauggie/SLMdefectsDetection`
2. Navigate to the project directory using Jupyter Notebook

### Usage

1. Open Jupyter Notebook: `jupyter notebook`
2. Run the notebooks in the `code/` directory sequentially.

## Contributing

We welcome contributions! If you'd like to contribute to this project, please follow our [Contribution Guidelines](CONTRIBUTING.md).


