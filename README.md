# NeuroXAI - Explainable AI for Neuro-Diagnosis

## Overview
NeuroXAI is a pioneering medical AI system focused on the early detection and analysis of neurological conditions like Alzheimer's Disease. It combines deep learning for accurate diagnosis with Explainable AI (XAI) techniques to provide clinicians with transparent, interpretable reasoning behind every prediction.

## Features
-   **Early Detection**: High-accuracy identification of early-stage Alzheimer's from MRI scans.
-   **Explainability**: Generates heatmaps (Grad-CAM) to highlight affected brain regions.
-   **Multi-Modal Analysis**: Integrates MRI data with clinical patient history.
-   **Report Generation**: Automated creation of detailed medical reports for doctors.
-   **Secure Processing**: HIPAA-compliant data handling.

## Technology Stack
-   **Deep Learning**: PyTorch / TensorFlow (CNNs, ResNet).
-   **XAI**: Grad-CAM, SHAP values.
-   **Backend**: Python, Flask.
-   **Frontend**: React for the clinician dashboard.
-   **Data Processing**: NumPy, Pandas, Nibabel (for MRI files).

## Usage Flow
1.  **Upload**: Clinician uploads patient MRI scan.
2.  **Preprocess**: Image is normalized and segmented.
3.  **Predict**: AI model analyzes the scan for biomarkers.
4.  **Explain**: XAI engine generates visual justification overlay.
5.  **Review**: Doctor reviews the diagnosis and heatmap.

## Quick Start
```bash
# Clone the repository
git clone https://github.com/Nytrynox/NeuroXAI.git

# Install dependencies
pip install -r requirements.txt

# Run the application
python app.py
```

## License
MIT License

## Author
**Karthik Idikuda**
