# PDF-Audio 📖🔊

Convert your PDF documents into audio and listen to them on the go!  
This project reads text from a PDF file and converts it into speech using Python.

---

## 🎯 Features
- Extracts text from any PDF document
- Converts extracted text to audio
- Saves the audio as an MP3 file
- Simple command-line interface (CLI)
- Cross-platform support (Windows, macOS, Linux)

---

## 🛠️ Tech Stack
- Python 3.x
- [PyPDF2](https://pypi.org/project/PyPDF2/) — For reading PDF files
- [gTTS (Google Text-to-Speech)](https://pypi.org/project/gTTS/) — For text-to-speech conversion
- [playsound](https://pypi.org/project/playsound/) — For playing audio (optional)

---

## 🚀 How to Run

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/pdf-audio.git
cd pdf-audio
```
### 2️⃣ Install Dependencies
``` bash
pip install -r requirements.txt
```
### 3️⃣ Run the Script
``` bash
python pdf_to_audio.py
```
## 🧩 Possible Enhancements
- Add GUI support with Tkinter / PyQt
- Support for multiple languages
- Add playback speed control
- Save text summary before audio generation
  
## 🤝 Contributing
Contributions, issues, and feature requests are welcome!
Feel free to check the issues page.

## 📜 License
This project is licensed under the MIT License — see the LICENSE file for details.
