# LinkedIn Post Generator - Make.com Template


https://github.com/user-attachments/assets/7b6cd8d1-01e6-4b16-8409-ea83242a98d6


## 📌 Core Features
- Automated LinkedIn post creation from Google Sheets data
- AI-powered content generation via Gemini

## ⚙️ Technical Specifications
| Component           | Service Used       |
|---------------------|--------------------| 
| Data Source         | Google Sheets      |
| AI Engine           | Gemini             |
| Publishing Platform | LinkedIn           |


## 🛠 Implementation Guide
1. **Import Template**:
   - Download `Generate LinkedIn posts-AI (Mohamed)`
   - Import to Make.com scenario editor

2. **Configure Connections**:
   ```makefile
   Connections → Add New:
   - Google: Enable Sheets API
   - Gemini: Enter API Key
   - LinkedIn: OAuth 2.0
   
 3. **Set Parameters**:
 
[google]
spreadsheet_id = YOUR_SHEET_ID
sheet_name = YOUR_SHEET_NAME

[gemini]
model = gemini-2.0-flash
