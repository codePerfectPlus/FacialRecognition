<p align="center">
  <a href="https://github.com/codePerfectPlus/Face_Recognition_using_encoding"><img src="https://capsule-render.vercel.app/api?type=rect&color=009ACD&height=100&section=header&text=FaceRecognition&fontSize=60%&fontColor=ffffff" alt="website title image"></a>
  <h2 align="center">👉 Face Recongition using face_recognition module and face encoding in Python 👈</h2>
</p>

<p align="center">
<img src="https://img.shields.io/badge/Python-3.8.5-lightgrey?style=for-the-badge" alt="repo language">
<a href="https://github.com/codePerfectPlus/FacailRecognition/stargazers"><img src="https://img.shields.io/github/stars/codePerfectPlus/FacailRecognition?style=for-the-badge" alt="github stars"></a>
<a href="https://github.com/codePerfectPlus/FacailRecognition/network/members"><img src="https://img.shields.io/github/forks/codePerfectPlus/FacailRecognition?style=for-the-badge" alt="github forks"></a>
<img src="https://img.shields.io/github/languages/code-size/codePerfectPlus/FacailRecognition?style=for-the-badge" alt="code size">

## Usgaes

### Add Your Image in `Images` folder. exmaple >> name.jpeg

### Install the requirements file

```bash
# windows 
python -m venv frenv
frenv/Scripts/activate.bat

python -m pip install -r requirements.txt

# Linux/Mac
python -m venv frenv
source frenv/bin/activate

python -m pip install -r requirements.txt
```

### Run the Script

```bash
python FaceRec.py train # to extract encoding
python FaceRec.py run # to run face recognition
```

NOTE:-

```bash
# incase installtation stuck on dlib
python -m pip install dlib -vvv 
```
