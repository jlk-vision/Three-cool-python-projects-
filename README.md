# Three-cool-python-projects-

Here are the **README** files for all three projects. These will help make your GitHub repository look professional and attract employers.  

---

## **Project 1: AI Data Visualization Tool**  
**Description:**  
This AI-powered tool allows users to upload Excel, CSV, or JSON files and automatically generates various types of graphs, helping users analyze data effortlessly.  

### **Features:**  
✅ Supports Excel (.xlsx), CSV (.csv), and JSON (.json) files  
✅ Auto-detects the best graph type based on data  
✅ Allows users to choose graph types (Bar, Pie, Line, Scatter, etc.)  
✅ Interactive UI using **KivyMD**  
✅ Saves graphs for future use  

### **Tech Stack:**  
- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- KivyMD  

### **How to Run:**  
1. Install dependencies:  
   ```bash
   pip install pandas matplotlib seaborn kivy kivymd
   ```
2. Run the main script:  
   ```bash
   python main.py
   ```
3. Select a file and view the visualizations in the UI.  

### **Future Enhancements:**  
- Add AI-based trend predictions  
- Support for more complex visualizations  

---

## **Project 2: AI Motivational Chatbot**  
**Description:**  
This chatbot helps users stay motivated by providing personalized responses based on their goals. It uses AI to generate motivational quotes and even speaks them aloud!  

### **Features:**  
✅ AI-based conversation using **DialoGPT**  
✅ Motivational quotes from famous personalities  
✅ Speech synthesis (text-to-speech)  
✅ Tracks user progress  
✅ UI built with **KivyMD**  

### **Tech Stack:**  
- Python  
- Transformers (DialoGPT)  
- gTTS (Google Text-to-Speech)  
- KivyMD  

### **How to Run:**  
1. Install dependencies:  
   ```bash
   pip install transformers kivy kivymd gTTS
   ```
2. Run the chatbot:  
   ```bash
   python chatbot.py
   ```
3. Start chatting and get motivation!  

### **Future Enhancements:**  
- Support for multiple languages  
- Integration with WhatsApp for daily motivational messages  

---

## **Project 3: SMS & Call Bomber with Location Tracker**  
**Description:**  
This is a fun tool that allows users to send multiple SMS or calls to a number and also track its approximate live location. (For educational purposes only!)  

### **Features:**  
✅ Sends bulk SMS automatically  
✅ Auto-calls a number (requires Twilio setup)  
✅ Tracks approximate location using **IP-based geolocation**  
✅ UI built with **KivyMD**  

### **Tech Stack:**  
- Python  
- Twilio API  
- Requests (for location tracking)  
- KivyMD  

### **How to Run:**  
1. Install dependencies:  
   ```bash
   pip install twilio kivy kivymd requests
   ```
2. Setup **Twilio**:  
   - Create an account on [Twilio](https://www.twilio.com/)  
   - Get your API keys and add them to `config.py`  

3. Run the script:  
   ```bash
   python bomber.py
   ```
4. Enter the phone number, message, and number of times to send message 
