🩸 HematoVision – AI-Powered Blood Cell Classifier

Project Type: Full-Stack Web Application
Domain: Healthcare, Medical Imaging, Artificial Intelligence

🧠 Objective :

To build an intelligent web-based system that allows medical professionals or researchers to:

Upload blood smear images

Automatically detect and classify white blood cells (WBCs)

Receive instant predictions such as: Monocytes, Neutrophils, Lymphocytes, Eosinophils, etc.

📌 Key Scenarios Covered

🔹 1. Frontend Interface (User Interaction)

Built using: HTML, CSS, JavaScript

Provides:

Home/Landing Page

Upload Page (drag & drop or click-to-upload image)

Result Display Page (shows prediction and image)

Responsive design with clean UI

🔹 2. Backend Logic (AI Inference Layer)

Built using: Python, Flask

Handles:

Receiving uploaded image

Preprocessing image (resizing, normalization)

Predicting using a pre-trained ML model

Returning results to the frontend

🔹 3. Image Processing

Image converted to array using PIL or OpenCV

Resized to model’s input size

Normalized for consistent prediction

🔹 4. Prediction Flow

User uploads an image via UI

Flask backend receives the image

Image is processed and fed to the model

Model returns class name (e.g., Lymphocyte)

Frontend displays image and predicted cell type

🔒 Future Enhancements

Real-time API predictions via REST

Model improvement with larger datasets

Role-based access (doctors vs researchers)

Historical report generation
