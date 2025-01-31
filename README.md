Automated license plate detection and recognition (ANPR) is implemented using YOLO and PaddleOCR. The YOLO model processes video frames from a CCTV feed to detect license plates, extracts text from the detected plates using Optical Character Recognition (OCR), and annotates the video with the recognized license numbers. All detected license plate numbers are stored in a CSV file, and the annotated video is saved for further analysis. The YOLO model ensures accurate license plate detection, while PaddleOCR provides reliable text extraction. Designed for real-time processing, the system includes functionality to avoid duplicate entries for previously detected plates.

🔑 Key Features:
	•	Real-time processing of video streams.
	•	Avoids duplicate entries for previously detected plates.
	•	Stores all license plate data in a CSV file for future analysis.
	•	Generates annotated videos for enhanced visualization and monitoring.

Dataset Link: https://universe.roboflow.com/number-plate-detection-7s12n/number_plates-aqize/dataset/2
