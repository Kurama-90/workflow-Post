# LinkedIn Post Generator - Make.com Template

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
