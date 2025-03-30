# Face Detection Web Application

This project is a Face Detection Web Application developed as part of the CodeClause Internship. It leverages modern web technologies to detect and recognize human faces in real-time using the browser.

## Features
- Real-time face detection using JavaScript.
- Pre-trained models for facial recognition and landmark detection.
- Interactive UI with visual feedback.
- Lightweight and responsive design.

## Technologies Used
- HTML
- CSS
- JavaScript
- Face-API.js

## Project Structure
```
├── face-api.min.js
├── face_expression_model-shard1
├── face_expression_model-weights_manifest.json
├── face_landmark_68_model-shard1
├── face_landmark_68_model-weights_manifest.json
├── face_landmark_68_tiny_model-shard1
├── face_landmark_68_tiny_model-weights_manifest.json
├── face_recognition_model-shard1
├── face_recognition_model-shard2
├── face_recognition_model-weights_manifest.json
├── index.html
├── script.js
├── styles.css
├── tiny_face_detector_model-shard1
├── tiny_face_detector_model-weights_manifest.json
└── vdbg.jpg
```

## How to Run the Project
1. Clone the repository:
```bash
git clone https://github.com/Binoyde12/CodeClauseInternship_Face-Detection-webdev.git
```
2. Open `index.html` in any modern web browser (Google Chrome/Firefox).
3. Allow camera access when prompted.

## Usage
- The application will automatically start detecting faces when the camera is enabled.
- Detected faces will be marked with bounding boxes and landmarks.

## Model Files
The application uses Face-API.js models that include:
- Face Landmark Detection
- Face Expression Recognition
- Tiny Face Detector

## Acknowledgments
- Developed as part of the CodeClause Internship.
- Face recognition powered by [Face-API.js](https://github.com/justadudewhohacks/face-api.js).

⚡ Author: Binoy Krishna Debnath
📧 Contact: LinkedIn Profile
🔗 GitHub Profile: Binoyde12

## License
This project is licensed under the MIT License.

