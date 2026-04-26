
An OCR enabled Plagiarism Checker
Plagio: An OCR-Enabled Plagiarism Checker
With the rise of the COVID-19 pandemic, the education system has undergone a significant transformation, shifting towards online and cloud-based teaching and evaluation methods. However, this transition has introduced several challenges, one of the major ones being the difficulty in detecting plagiarism in handwritten answer sheets.
To address this issue, we propose a software solution that integrates an Optical Character Recognition (OCR) system capable of extracting text from scanned images of handwritten documents. Once the text is digitized, it is analyzed for plagiarism by comparing it against a vast database of approximately 130 trillion web pages. The system then generates a comprehensive plagiarism report.
Data Flow Overview
The project consists of three primary modules:
OCR Module
Plagiarism Checker Module
Website Interface
The internal data flow between these components is illustrated in the block diagram below.
Published a research paper for the same : 
<a>https://zenodo.org/records/13801226</a>
 
And the internal data flow is depicted by the following block diagram.
<p align="center">
  <img src="https://github.com/SakshiManjrekar162/Academic-Plagiarism-Detection-in-Handwritten-Assignments/blob/main/frontend/src/assets/Plagiarism%20detection%20diagram.jpg" width="600"/>
</p>
The flow of the level wise processing is as follows.
<p align="center">
 <img src="https://github.com/SakshiManjrekar162/Academic-Plagiarism-Detection-in-Handwritten-Assignments/blob/main/frontend/src/assets/Flowchart.jpg" width="600"/>
 </p>

## How to set up

 1. Clone the repository using `https://github.com/SakshiManjrekar162/Academic-Plagiarism-Detection-in-Handwritten-Assignments.git`
 2. Move into the directory using `cd PlagiarismChecker`
 3. Install all dependencies for the backend using `pip install -r requirements.txt`
 4. Move into the frontend folder using `cd frontend`
 5. Install all dependencies for the frontend using `npm install`

## How to run the software
### Backend
1. Move into the backend folder from the root folder using `cd backend`
2. Run the server using `python manage.py runserver 8000`
It is important to start the server at port 8000, otherwise frontend requests might not be served.

### Frontend
1. Move into the backend folder from the root folder using `cd frontend`
2. Run the server using `npm run start`
