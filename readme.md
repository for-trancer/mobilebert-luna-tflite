# MobileBERT TFLite Model for Luna

This repository contains the MobileBERT TFLite model trained on the MASSIVE dataset, which includes over 60 intent labels for robust offline text intent recognition. The model is optimized for on-device NLP tasks, enabling efficient and accurate intent classification without requiring an internet connection.

## Features
- **Optimized for Mobile**: Uses TensorFlow Lite (TFLite) for efficient on-device inference.
- **Offline Intent Recognition**: Processes text-based intent classification without an internet connection.
- **Lightweight and Fast**: Compact MobileBERT architecture ensures minimal latency.
- **Trained on MASSIVE Dataset**: Covers diverse intent labels for better accuracy in real-world scenarios.

## Model Details
- **Model Architecture**: MobileBERT (fine-tuned for intent classification)
- **Dataset**: MASSIVE (Multilingual and Task-Oriented Semantic Parsing)
- **Number of Intent Labels**: 60+
- **Format**: `.tflite`
- **Use Case**: Offline text intent recognition

## Usage
This model can be integrated into mobile applications using TensorFlow Lite for real-time, offline text-based intent classification.

## Future Enhancements
- Additional fine-tuning for **domain-specific** intents.
- Improved **multilingual support**.
- Seamless integration with **voice assistants** like Luna.

## License
This project is licensed under the **MIT License**.
