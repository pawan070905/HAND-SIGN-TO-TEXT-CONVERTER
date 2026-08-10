# HAND-SIGN TO TEXT CONVERTER

This project is a Python-based application that converts American Sign Language (ASL) gestures into English text using computer vision and machine learning (Convolutional Neural Network). It leverages a camera to detect hand gestures, recognizes the patterns, and translates them into text.

---

## ✨ Benefits of the Program  
- **Accessibility**: Facilitates communication between people who use ASL and those who don’t understand it.  
- **Real-Time Conversion**: Provides instant translation of ASL to text, making it efficient for interactive use.  
- **Learning Aid**: Helps non-ASL users learn and practice sign language.  
- **Versatile**: Can be adapted for educational, professional, or casual environments.

---

## 🛠️ Tech Stack  
- **Programming Language**: Python 3.9
- **Libraries**:  
  - [Mediapipe](https://google.github.io/mediapipe/)  (version 0.10.18)
  - [CVZone](https://github.com/cvzone/cvzone)  (version 1.5.6)
  - [TensorFlow](https://www.tensorflow.org/)  (version 2.12.1)
  - [opencv-python](https://pypi.org/project/opencv-python/)  (version 4.5.5.64)
  - [protobuf](https://protobuf.dev/)  (version 4.25.6)
 
---

## 🚀 Getting Started  

### 1️⃣ Prerequisites  
Ensure you have Python installed (preferably version 3.9).  

### 2️⃣ Clone the Repository  
```bash  
git clone https://github.com/yourgithubusername/asl-to-text-converter.git  
cd asl-to-text-converter
```

### 3️⃣ Set Up a Virtual Environment

Create the virtual environment
```bash
python -m venv venv  
```

Activate the virtual environment  
- Windows:  
```bash
venv\Scripts\activate
```
- macOS/Linux: 
```bash
source venv/bin/activate  
```

### 4️⃣ Install Dependencies
```bash
pip install mediapipe cvzone tensorflow 
```

### 5️⃣ Run the Program
Simply press the run button.

### 📸 How It Works
The program uses your webcam to capture real-time hand gestures.
Mediapipe detects and tracks hand landmarks.
TensorFlow processes the gestures to classify them into English alphabets.
CVZone overlays the recognized text onto the video feed.

### 📖 Future Improvements
Add support for ASL words and phrases.
Improve model accuracy with more extensive training data.
Develop a GUI for better usability.

### 🙌 Contributions
Feel free to contribute by opening issues or submitting pull requests.

### 📧 Contact
If you have any questions or feedback, please reach out:

Email: jain.nilesh1203@gmail.com | GitHub: [My GitHub Profile](https://github.com/nilesh1434) | Website: [thenileshjain.com](http://thenileshjain.com)<br><br>

Thank you for exploring my project! 🎉

Happy Coding!!!
