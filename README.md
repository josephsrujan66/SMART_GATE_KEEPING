Smart Gate System (Notebook Version)

An AI-based Smart Gate Entry & Exit Management System that detects vehicle license plates from images and automatically logs vehicle movement into an Excel file.
This project runs entirely inside a Jupyter Notebook / Google Colab environment.

Features:
  1. License Plate Detection using Deep Learning (.h5 model)
  2. IN (Entry) Logging
  3. OUT (Exit) Logging
  4. Capture Image from System Camera
  5. Upload Image Option
  6. Automatic Excel Log Generation
  7. Auto-delete Image After Processing
  8. Interactive Dashboard UI

How to Run the Project in Google Colab
  1. Open the provided .ipynb file in Google Colab
  2. Download the classifier 
     (https://github.com/josephsrujan66/SMART_GATE_KEEPING/releases/download/Vehicle_Classifier_Model/vehicle_classifier_model.h5)
  3. Upload the image classifier model in the notebook
  4. Run all cells
  5. The Smart Gate Dashboard will appear
  6. Enter IN/OUT, Name, Reason, Capture the image of vehicle, and Submit.

*No installation required — all dependencies are handled inside the notebook.


Project Structure
Smart-Gate-System/
      Smart_Gate_System.ipynb
      license_plate_model.h5
      vehicle_log.xlsx (generated automatically)
