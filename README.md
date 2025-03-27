# Doctor's Prescription Text Extractor

## 📌 Overview
RxVision is a powerful AI-based application that extracts and formats text from handwritten prescriptions. Built using **Streamlit** and **Google Gemini AI**, this tool helps in decoding difficult-to-read prescriptions by recognizing medical terms, correcting spelling errors, and presenting structured outputs.

## 🚀 Features
- 📷 **Image Upload**: Upload prescription images in JPG, JPEG, or PNG format.
- 🧠 **AI-Powered OCR**: Uses Google Gemini AI to extract, correct, and format medical text.
- 📑 **Structured Output**: Presents extracted medicines, dosages, and instructions in a readable format.
- 📥 **Download Extracted Text**: Save the recognized prescription text as a `.txt` file.
- ⚡ **Easy-to-Use Interface**: Built with **Streamlit**, making it interactive and user-friendly.

## 🛠️ Tech Stack
- **Python**
- **Streamlit** (For the Web UI)
- **Google Gemini AI** (For text recognition and processing)
- **Pillow (PIL)** (For image handling)
- **NumPy**

## 📂 Project Structure
```
📦 Prescription-Extractor
├── 📜 app.py          # Main application file
├── 📜 requirements.txt # Dependencies
└── 📜 README.md       # Project documentation
```

## 🎯 How It Works
1. Upload an image of a doctor's prescription.
2. The AI extracts and corrects the text.
3. View the structured output.
4. Download the extracted text if needed.

## 🏗️ Installation & Usage
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/RxVision.git
cd RxVision
```

### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Application
```bash
streamlit run app.py
```

## 🔑 API Key Setup
This project uses Google Gemini API. Replace the API key in `app.py` with your own:
```python
genai.configure(api_key="YOUR_GEMINI_API_KEY")
```

## 📌 Screenshots
<img src="screenshot.png" alt="App Screenshot" width="600px">

## 📜 License
This project is licensed under the MIT License.

## 💡 Future Enhancements
- ✅ Improve accuracy with fine-tuned AI models.
- ✅ Add multilingual support for prescriptions in different languages.
- ✅ Store extracted text in a database for easy retrieval.

## 🤝 Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request.

## 📧 Contact
For queries, reach out to **[Your Name](mailto:your-email@example.com)**.

---
🌟 **Star the repo if you find it useful!** 🚀

