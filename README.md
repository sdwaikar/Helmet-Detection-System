# Helmet Detection System 🏍️

This project develops a deep learning model using TensorFlow to detect helmets in real-time video feeds, achieving an accuracy of over 92%. Designed to enhance road safety, this system identifies whether motorcycle riders are wearing helmets, aiding traffic management and law enforcement in promoting helmet usage.

## Features

- **Real-Time Detection:** Utilizes convolutional neural networks (CNNs) to detect helmets in video streams, achieving real-time performance with high accuracy.
- **Data Augmentation:** Enhanced the training dataset with over 20,000 images, applying techniques such as rotation, scaling, and flipping to improve model robustness against various orientations and lighting conditions.
- **User Interface:** Integrated with Streamlit to create a user-friendly web interface that allows for easy visualization of real-time detections and system analytics.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/YourUsername/HelmetDetectionSystem.git
   ```

2. Navigate to the project directory:
   ```bash
   cd HelmetDetectionSystem
   ```

3. Install required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Start the Streamlit application:
   ```bash
   streamlit run Helmet_Detection_App.py
   ```

2. Access the web interface via a web browser at `localhost:8501` to view the system in action.

## Dataset

The training dataset includes:
- **20,000+ images** of motorcycle riders with and without helmets.
- Images were sourced under a suitable license for public safety applications.

## Results

- **Detection Accuracy:** Achieved 92% accuracy in identifying helmet usage in various real-world scenarios.
- **Model Performance:** The system performs efficiently in diverse environmental conditions, demonstrating robustness across different datasets.

## Skills Demonstrated

- Image Processing with TensorFlow
- Real-Time Object Detection
- Data Preprocessing and Augmentation
- Web Application Development with Streamlit

## License

This project is licensed under the MIT License. See the LICENSE file for more details.
