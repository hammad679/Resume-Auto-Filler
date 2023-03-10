# Resume-Auto-Filler

#Solution
An OCR-based AI model, trained on multiple templates from the internet which can parse resumes and can fill out the information like Name, Email Address and Phone Number.


## How to Execute

1. Install All the requirements :
pip install requirements.txt

2. Retreive model for spacy :
python3 -m spacy download en_core_web_sm

3. Start the Application : 
uvicorn main:app --reload 

## Architectural Flow
![image](https://user-images.githubusercontent.com/83724397/217777731-b9f9a23f-c9a3-4b0d-a935-f3bffce6fe7b.png)

## Technology Used

<div>
  <img name = "Python" src = "https://img.shields.io/badge/python%20-%2314354C.svg?&style=for-the-badge&logo=python&logoColor=white">
  <img name = "FastAPI" src = "https://img.shields.io/badge/FastAPI-FastAPI?style=for-the-badge&logo=fastapi&color=18191a">
  <img name = "OpenCV" src = "https://img.shields.io/badge/OpenCV-OpenCV?style=for-the-badge&logo=opencv&logoColor=fff&color=5C3EE8">
  <img name = "Jupyter" src = "https://img.shields.io/badge/Jupyter%20-%23F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white">
  <img name = "Numpy" src = "https://img.shields.io/badge/numpy%20-%23013243.svg?&style=for-the-badge&logo=numpy&logoColor=white">
  <br>
  <img name = "Jinja" src = "https://img.shields.io/badge/jinja-white.svg?style=for-the-badge&logo=jinja&logoColor=black">
  <img name = "JavaScript" src = "https://img.shields.io/badge/javascript%20-%23323330.svg?&style=for-the-badge&logo=javascript&logoColor=%23F7DF1E"> 
  <img name = "HTML" src = "https://img.shields.io/badge/html5%20-%23E34F26.svg?&style=for-the-badge&logo=html5&logoColor=white">
  <img name = "CSS" src = "https://img.shields.io/badge/css3%20-%231572B6.svg?&style=for-the-badge&logo=css3&logoColor=white">
  <img name = "Bootstrap" src = "https://img.shields.io/badge/bootstrap%20-%23563D7C.svg?&style=for-the-badge&logo=bootstrap&logoColor=white">
  <br>
  <img name = "Docker" src = "https://img.shields.io/badge/Docker-Docker?style=for-the-badge&logo=docker&color=18191a">
  <img name = "Firebase" src = "https://img.shields.io/badge/firebase-%23039BE5.svg?style=for-the-badge&logo=firebase">
</div>

## Dataset Source 
<a href = "https://www.kaggle.com/datasets/aishikai/resume-dataset"><img src = "https://img.shields.io/badge/Kaggle-035a7d?style=for-the-badge&logo=kaggle&logoColor=white"></a>
