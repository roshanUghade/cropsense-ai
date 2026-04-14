# 🌿 CropSense AI

**AI-powered crop detection, disease analysis, and agricultural intelligence platform for Indian farmers.**

Built by [@roshanUghade](https://github.com/roshanUghade) · Powered by Claude AI (Anthropic)

---

## ✨ Features

| Feature | Description |
|---|---|
| 🔬 **Crop Analysis** | Upload any crop photo — AI detects crop type, growth stage, age, diseases, and more |
| 📊 **Crop Insight** | Compare before & after images to track improvement over time |
| 🧪 **Fertilizer Recommendations** | NPK ratios, doses, timing, and organic alternatives |
| 🐛 **Disease & Pest Detection** | Identifies diseases with severity, treatment, and organic remedies |
| 💧 **Irrigation & Soil Advice** | Personalized recommendations based on crop and soil type |
| 💰 **Profit Tips & Market Price** | Estimated yield and current market price per quintal |
| 🧮 **Fertilizer Calculator** | Calculate exact quantities for your field area (acres/hectares/bigha) |
| 📅 **Crop Calendar** | Month-by-month farming schedule for Maharashtra |
| 🌤 **Weather Advisory** | AI-based seasonal crop recommendations |
| 📖 **Field Guide** | Crop-specific knowledge for 12+ crops |
| 🌙 **Dark Mode** | Full dark/light theme support |
| 🌐 **Multilingual** | English, हिंदी, मराठी |
| 📋 **History Tracking** | Saves past analyses locally for comparison |
| ⬇ **PDF Export** | Print/export full analysis report |

---

## 🚀 Quick Start

### Option 1: Use Directly (No Installation)
1. Download or clone this repo
2. Open `index.html` in your browser
3. Enter your [Anthropic API key](https://console.anthropic.com) when prompted
4. Upload a crop photo and start analyzing!

### Option 2: GitHub Pages (Live Website)
After pushing to GitHub, enable **GitHub Pages** in repo Settings → Pages → set source to `main` branch → `/ (root)`.

Your app will be live at: `https://roshanUghade.github.io/cropsense-ai`

---

## 🔑 API Key Setup

1. Go to [console.anthropic.com](https://console.anthropic.com)
2. Create an account and generate an API key
3. Paste it into the app when prompted on first launch
4. The key is stored **only in your browser's localStorage** — never on any server

---

## 📸 How to Use

### Analyze Crop
1. Click **Analyze Crop** in the sidebar
2. Upload or drag-and-drop a crop image
3. Optionally select crop type and soil type
4. Click **Analyze Now**
5. Get full AI report: health score, diseases, fertilizers, yield estimate, profit tips

### Crop Insight (Track Progress)
1. Click **Crop Insight** in the sidebar
2. Upload a **before** image (older photo)
3. Upload an **after** image (recent photo)
4. Select the number of days between photos
5. Click **Compare & Analyze**
6. See exactly what changed: disease progress, treatment effectiveness, next steps

### Fertilizer Calculator
1. Select your crop type
2. Enter field area and unit (acres/hectares/bigha)
3. Select growth stage
4. Get exact fertilizer quantities with cost estimates

---

## 🌾 Supported Crops

Wheat · Rice · Cotton · Sugarcane · Tomato · Onion · Soybean · Corn · Potato · Chili · Groundnut · Banana · and more (auto-detection supports any crop)

---

## 🛠 Tech Stack

- **Frontend**: Pure HTML5 + CSS3 + Vanilla JavaScript (no framework, no build step)
- **AI**: Claude claude-sonnet-4-20250514 via Anthropic API
- **Storage**: Browser localStorage (no backend)
- **Fonts**: Google Fonts (Sora + JetBrains Mono)
- **Deploy**: GitHub Pages (static)

---

## 📁 Project Structure

```
cropsense-ai/
├── index.html       ← Full app (single file)
├── README.md        ← This file
└── LICENSE          ← MIT License
```

---

## 🔒 Privacy

- Your API key is stored **only in your browser** (localStorage)
- Crop images are sent **directly to Anthropic's API** — not to any third-party server
- No user data is collected or stored remotely

---

## 🤝 Contributing

Pull requests are welcome! Ideas for improvement:
- [ ] Camera capture for mobile farmers
- [ ] Offline mode with cached analysis
- [ ] WhatsApp/SMS integration for farmers without smartphones
- [ ] Satellite imagery integration
- [ ] Multi-language voice input

---

## 📄 License

MIT License — free to use, modify, and distribute.

---

## 👨‍💻 Author

**Roshan Ughade**  
GitHub: [@roshanUghade](https://github.com/roshanUghade)

---

*Made with ❤️ for Indian farmers — CropSense AI*
