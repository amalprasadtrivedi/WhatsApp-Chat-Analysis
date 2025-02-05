# 📊 WhatsApp Chat Analysis

## 📌 Overview
This project provides a detailed analysis of WhatsApp chat data to extract valuable insights such as message frequency, emoji usage, media sharing statistics, and user activity trends. It leverages Python along with powerful data analysis libraries like pandas, matplotlib, and seaborn.

## ✨ Features
✔ Message count per user 📈  
✔ Word frequency analysis 🔠  
✔ Emoji usage statistics 😀  
✔ Media and link sharing insights 📎  
✔ Activity trends over time (daily, weekly, monthly) 📅  
✔ Sentiment analysis (optional) 💬  
✔ Data visualization through charts and graphs 📊  

## 🛠 Installation
To get started, clone this repository and install the required dependencies:

```sh
# Clone the repository
git clone https://github.com/your-username/whatsapp-chat-analysis.git
cd whatsapp-chat-analysis

# Install dependencies
pip install -r requirements.txt
```

## 🚀 Usage
1. **Export your WhatsApp chat:**
   - Open the WhatsApp chat you want to analyze.
   - Click on "More options" > "Export chat".
   - Choose "Without Media" and save the `.txt` file.

2. **Place the exported chat file in the project directory.**

3. **Run the script:**

```sh
python whatsapp_analysis.py --chat chat.txt
```

4. **View the results:**
   - User activity analysis 📊  
   - Most used words wordcloud ☁  
   - Emoji distribution 📉  
   - Message trends over time ⏳  
   - Media and link sharing statistics 🔗  

## 📦 Dependencies
Ensure you have the following libraries installed:

```sh
pip install pandas matplotlib seaborn emoji nltk wordcloud
```

## 📊 Results & Visualization
The script generates various insights with the help of data visualization. Some key results include:

📌 **User Activity Analysis:** 
   - Bar graphs showing the number of messages sent by each user.

📌 **Word Frequency:** 
   - A word cloud representation of the most commonly used words in the chat.

📌 **Emoji Statistics:** 
   - A breakdown of the most frequently used emojis with counts.

📌 **Trends Over Time:** 
   - Line charts showing message activity on a daily, weekly, and monthly basis.

📌 **Media & Link Sharing:** 
   - Count of shared images, videos, and links in the conversation.

## 🏗 Contribution
We welcome contributions! Feel free to submit pull requests, open issues, or suggest improvements.

## 📜 License
This project is licensed under the MIT License. Enjoy analyzing your WhatsApp chats! 🚀
