# Music Genre Classification Using Deep Learning

## Project Overview
This project involves developing a deep learning model to classify music audio into 10 distinct genres. The model leverages Convolutional Neural Networks (CNNs) to process audio features extracted from music tracks, achieving high accuracy on both training and validation datasets.

## Features
- **Music Genre Classification**: Classifies audio files into 10 genres such as Jazz, Blues, Classical, etc.
- **Deep Learning Model**: Built with TensorFlow and Keras, using CNNs optimized for audio data.
- **Data Processing**: Utilizes Librosa for audio feature extraction, including Mel-frequency cepstral coefficients (MFCCs).
- **High Accuracy**: Achieved over 97% accuracy on training data and approximately 90% on validation data.

## Project Structure
- **Train_Music_Genre_Classifier.ipynb**: Jupyter notebook containing the training process, including data preprocessing, model architecture, and training loop.
- **Test_Music_Genre.ipynb**: Jupyter notebook for testing the trained model on unseen data and evaluating its performance.
- **training_hist.json**: JSON file containing the training history, including loss and accuracy metrics for both training and validation datasets.
- **Audio Files**: Example audio files used for training and testing, e.g., `blues.00000.wav`, `jazz.00054.wav`.

## Installation
To run this project locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/YourUsername/MusicGenreClassification.git
    cd MusicGenreClassification
    ```

2. **Install required dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the training notebook**:
    Open `Train_Music_Genre_Classifier.ipynb` in Jupyter Notebook and execute the cells to train the model.

4. **Test the model**:
    Open `Test_Music_Genre.ipynb` in Jupyter Notebook to test the trained model and see the results.

## Dependencies
- Python 3.7+
- TensorFlow
- Keras
- Librosa
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Usage
To classify a new music track, add your audio file to the appropriate location and run the test notebook. The model will output the predicted genre.

## Results
The model was trained on a large dataset of labeled music tracks and tested with unseen data. The final model achieved:
- **Training Accuracy**: 97.7%
- **Validation Accuracy**: 90.3%

## Contributing
Contributions are welcome! If you'd like to improve the project, feel free to fork the repository and submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For any inquiries, feel free to reach out at your.email@example.com.

---

**GitHub Repository**: [Music Genre Classification](https://github.com/YourUsername/MusicGenreClassification)
