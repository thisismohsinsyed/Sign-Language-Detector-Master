
# Sign Language Detector

## Overview
This repository contains the code for a Sign Language Detector project, which enables the detection and interpretation of sign language gestures using machine learning. The project includes scripts for data collection, processing, model training, and deployment.

## Project Structure
- `1- collect_data.ipynb`: Jupyter notebook for collecting sign language gesture data.
- `2- Hand_Landmarks_extraction.ipynb`: Notebook for extracting hand landmarks from the collected data.
- `3- train_model.ipynb`: Notebook for training the machine learning model.
- `4- Real_time_deployment.ipynb`: Notebook for deploying the model in real-time using a webcam.
- `5- Hand landmarks_Data.pickle`: Processed hand landmarks data.
- `6- SVM Model.p`: Pickled SVM model trained on the processed data.
- `data/`: Directory containing raw data of sign language gestures.
- `model.p`, `SVM_model.p`: Additional serialized models.
- `Web_Deployment/`: Files related to the web deployment of the model.
  - `5- Web_Deployment.py`: Python script for running the Flask web server.
  - `Templates/`: HTML templates for the web interface.
    - `result.html`: HTML template for displaying results.
    - `upload.html`: HTML template for uploading gesture images.

## Installation
1. Clone this repository:
   ```
   git clone [https://github.com/thisismohsinsyed/Sign-Language-Detector-Master.git]
   ```
2. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

## Usage
To start collecting data, run the notebook:
```
jupyter notebook 1- collect_data.ipynb
```
Follow similar steps to process data and train the model using the respective notebooks.

To deploy the model via a web interface, navigate to the `Web_Deployment` directory and run:
```
python 5- Web_Deployment.py
```
Access the web interface at `http://localhost:5000`.

## Contributing
Contributions are welcome! Please read the `CONTRIBUTING.md` for details on our code of conduct, and the process for submitting pull requests.

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Authors
- **Syed Mohsin** - *Initial work* - [thisismohsinsyed](https://github.com/thisismohsinsyed)

