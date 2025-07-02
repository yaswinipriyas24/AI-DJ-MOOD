# 🎧 AI Mood DJ – Music Recommendation Based on Facial Emotion 🎭🎵

AI Mood DJ is an intelligent system that detects a user's **facial emotion from an image or webcam**, and recommends **Telugu songs** based on the predicted mood using **Spotify API**. The model is trained using **facial expression recognition** techniques and implemented with a **CNN**.

---

## 🧠 Project Idea

The goal of this project is to create an AI assistant that can:
1. **Analyze facial expressions**
2. **Detect emotions like Happy, Sad, Angry, etc.**
3. **Recommend music** that matches the emotion using **Spotify**

Whether you're smiling or feeling blue, AI Mood DJ will match your emotion to the perfect Telugu song 🎶

---

## 🚀 Features

- ✅ Emotion Detection using facial expressions
- ✅ Trained on the **FER2013 dataset**
- ✅ Built using **TensorFlow/Keras CNN model**
- ✅ Recommends **Telugu songs** using **Spotify Web API**
- ✅ Supports both **uploaded images** and **live webcam**
- ✅ Clean project structure and modular codebase

---

## 📁 Project Structure
ai-mood-dj/
├── models/ # Saved trained model (CNN .h5 file)
├── src/ # Source code and logic
│ └── ai_mood_dj.py # Main application logic (10 steps)
├── assets/ # Sample images or datasets (optional)
├── README.md # Project documentation
├── requirements.txt # Python dependencies
├── .gitignore # Files/folders to ignore in git

---


---

## 🧩 How It Works (10-Step Breakdown)

1. **Upload an image** (or capture via webcam)
2. **Preprocess the image** – convert to grayscale, resize to 48x48
3. **Load the trained model**
4. **Predict the facial emotion** using the CNN model
5. **Map the predicted emotion** to a specific Telugu song category
6. **Authenticate with Spotify API**
7. **Search for a matching song** using the emotion-based query
8. **Fetch song details** (title, artist, preview URL)
9. **Display the song** and play the 30-second audio preview
10. **(Optional)**: Show song link and emotion detected

---

## 🎓 Technologies Used

- Python 3.x
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib
- Spotipy (Spotify API wrapper)
- Google Colab / Jupyter Notebook

---

## 📦 Installation

```bash
git clone https://github.com/yaswinipriyas24/AI-DJ-MOOD.git
cd AI-DJ-MOOD
pip install -r requirements.txt

# 🧪 Dataset

We use the FER2013 (Facial Expression Recognition) dataset:

Classes: Angry, Disgust, Fear, Happy, Sad, Surprise, Neutral

Format: JPG images (48x48 grayscale)

Source: Kaggle (FER2013 Dataset)

## 🔐 Spotify API Setup
Create a Spotify Developer account

Get your client_id and client_secret from the dashboard

Add these to your code securely for song recommendations


## 🎯 Future Improvements
Support for real-time webcam emotion detection

Multi-language song recommendations (English, Hindi, etc.)

Add GUI for a better user experience

Improve model accuracy with transfer learning

## 🤝 Contributing

Contributions are welcome and appreciated! If you'd like to improve this project, follow these steps:

1. 🍴 Fork the repository
2. 🛠️ Create a new branch (`git checkout -b feature-name`)
3. ✍️ Make your changes
4. ✅ Commit your changes (`git commit -m "Add feature"`)
5. 📤 Push to the branch (`git push origin feature-name`)
6. 📨 Open a pull request

Please make sure your code follows the project's style guidelines and includes proper documentation and comments.


## 📜 License
MIT License – Use freely, credit is appreciated 💖

## 🙋‍♀️ Made by
Yaswini Priya S
## 🎓 AI Enthusiast | Python Developer | Open Source Explorer


