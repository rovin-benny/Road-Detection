# Road Detection

This repository contains a machine learning-based solution for road detection. It leverages the TernausNet architecture to predict and detect roads in images. The project is implemented using Python and Jupyter Notebooks.

## Files Overview

- **Single_Image_binary_masking.ipynb**: Jupyter notebook to perform binary masking on a single image.
- **Data Loader (1).ipynb**: A notebook for loading and preprocessing data.
- **Model Trainer (1).ipynb**: A notebook to train the road detection model.
- **Model_Tester_and_Performance_Metrics_Final.ipynb**: Evaluate the model and calculate performance metrics.
- **Ternaus Architecture Creator_vgg.ipynb**: Code to create and configure the TernausNet architecture with a VGG encoder.
- **real.py**: Real-time implementation script for road detection.

## Real-Time Road Detection

For real-time road detection, we used the **ReComputer J101** platform, which allows us to deploy the model in real-world environments. The system uses a camera mounted on a vehicle to capture live video, process the frames, and detect roads in real time.

## Installation

Clone the repository and install the necessary dependencies:

```bash
git clone https://github.com/rovin-benny/Road-Detection.git
cd Road-Detection
pip install -r requirements.txt
