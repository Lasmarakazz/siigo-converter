# ☁️ CloudBeds → SIIGO Converter

Automated tool to transform CloudBeds reservation exports into a 
perfectly formatted **Archivo Plano Terceros** file ready to upload 
to SIIGO for billing.

## 🔗 Live App
👉 **[lasmarakazz.github.io/siigo-converter](https://lasmarakazz.github.io/siigo-converter/)**

## ✨ Features
- Accepts any CloudBeds export format (full Spanish or summary English)
- Auto-detects guest country from phone prefix
- Colombian guests → Tipo identificación **13** (DNI)
- Foreign guests → Tipo identificación **41** (Passport)
- Phone numbers automatically cleaned to **max 10 digits** (SIIGO requirement)
- Exact SIIGO formatting:
  - Sheet name: `Hoja1`
  - Font: Calibri 12pt Bold (headers) · Aptos Narrow 11pt (data)
  - Required columns: white background `#FFFFFF`
  - Optional columns: blue background `#00AAFF`
- 100% client-side — **no data is ever uploaded to any server**
- Works on any browser, no installation needed

## 📋 How to Use
1. Go to the [live app](https://lasmarakazz.github.io/siigo-converter/)
2. Upload your CloudBeds `.xlsx` export file
3. Click **"Generate SIIGO File"**
4. Download `ARCHIVO_PLANO_TERCEROS.xlsx`
5. Upload it to SIIGO → Terceros ✅

## 📁 Output Format
The generated file matches the **MODELO Final - ARCHIVO PLANO TERCEROS** 
format required by SIIGO Colombia for third-party (Terceros) registration.

## 🏨 Built for
JALO Rent SAS · Medellín, Colombia

## 🔒 Privacy
All file processing happens entirely in your browser.  
No guest data is ever sent to any external server.
