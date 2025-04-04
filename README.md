# 🚀 LinkedIn Post Generator - n8n Workflow  

This n8n workflow automates LinkedIn post generation using structured data, API requests, and AI-powered message generation. It processes messages, converts XML data to JSON, and saves generated posts in Google Sheets.  

## 📌 Features  
✅ Scrapes or receives structured chat messages  
✅ Sends HTTP requests for external data  
✅ Converts XML to JSON format  
✅ Splits and processes multiple items dynamically  
✅ Uses AI to generate LinkedIn posts  
✅ Stores posts in Google Sheets for easy tracking  

## 🛠️ Workflow Breakdown  
1. **Trigger:** Listens for an incoming chat message.  
2. **HTTP Request:** Fetches external data.  
3. **XML to JSON:** Converts XML data into a structured JSON format.  
4. **Data Processing:** Splits, edits, and aggregates data for better structuring.  
5. **Loop Over Items:** Iterates through multiple data entries.  
6. **LinkedIn Post Generator (AI Model):** Generates engaging LinkedIn posts.  
7. **Google Sheets:** Saves the generated posts for tracking.  

## 📥 Installation & Setup  
1. Install [n8n](https://n8n.io/) on your system.  
2. Import the workflow JSON file into n8n.  
3. Configure API keys for LinkedIn (if applicable).  
4. Set up Google Sheets access for saving posts.  
5. Activate the workflow and start generating LinkedIn posts!  

## 📌 Requirements  
- n8n installed locally or on a cloud instance  
- API keys for LinkedIn (if using direct posting)  
- Google Sheets integration enabled  

## 📞 Contact  
For any questions or improvements, feel free to reach out or contribute to this repository. 🚀  

