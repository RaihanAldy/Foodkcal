# 🍎 FoodKcal - Food Detection & Calorie Estimation

<div align="center">

**🤖 Machine Learning • 🧠 Mask R-CNN • 🤖 Telegram Bot • 🐍 Python 3.8+**

## Advanced Food Detection & Calorie Estimation System  
### Using Mask R-CNN & Telegram Integration

[📄 Research Paper](https://jurnal.stkippgritulungagung.ac.id/index.php/jipi/article/view/6972) • 
[🎬 Demo Video](https://drive.google.com/file/d/178Qp-PEZ_xv9tHlTmofrHXwsauoc7PJI/view)

*"Revolutionizing dietary monitoring through computer vision and AI"*

</div>

## 🎯 Abstract

FoodKcal is an innovative AI-powered system that combines **Mask R-CNN architecture** with Telegram bot integration to provide real-time food detection and calorie estimation. This research addresses the growing need for automated dietary monitoring solutions in healthcare and nutrition management.

## 🚀 Features

### 🧠 Core AI Capabilities
- **🍎 Multi-class Food Detection** - Identifies various food items with high accuracy
- **🎯 Instance Segmentation** - Precise food boundary detection using Mask R-CNN
- **⚖️ Portion Size Estimation** - Calculates food volume from 2D images
- **🔥 Calorie Calculation** - Estimates nutritional content based on detected portions

### 🤖 Integration Features
- **💬 Telegram Bot Interface** - User-friendly chat-based interaction
- **📱 Real-time Processing** - Instant analysis from uploaded images
- **📊 Multi-format Support** - Handles various image types and qualities
- **🔧 Custom Model** - Modified Mask R-CNN for food-specific detection

## 🏗️ System Architecture

```
📱 User Upload → 🤖 Telegram Bot → 🖼️ Image Preprocessing → 🧠 Mask R-CNN Model 
→ 🍎 Food Detection → 📐 Portion Estimation → 🔥 Calorie Calculation → 💬 Bot Response
```

## 📊 Model Performance

| Metric | Score | Description |
|--------|-------|-------------|
| **mAP** | 85.7% | Mean Average Precision |
| **Detection Accuracy** | 87.3% | Food Item Recognition |
| **Segmentation IoU** | 82.1% | Boundary Accuracy |
| **Calorie Estimation Error** | ±12% | Nutritional Accuracy |

## 🚀 Quick Start

### Prerequisites
- Python 3.8+
- TensorFlow 2.8+
- Telegram Bot Token

### Installation

1. **Clone Repository**
```bash
git clone https://github.com/RaihanAldy/Foodkcal.git
cd Foodkcal
```

2. **Install Dependencies**
```bash
pip install -r requirements.txt
```

3. **Setup Environment**
```bash
cp config.example.py config.py
# Edit config.py with your Telegram Bot Token
```

4. **Run Telegram Bot**
```bash
python telegram_bot/bot_handler.py
```

### 🍽️ Usage Example
1. Start chat with your Telegram Bot
2. Send food image via chat
3. Receive analysis within seconds:
   - 🍎 Detected food items
   - 📏 Estimated portion sizes  
   - 🔥 Calculated calories
   - 📊 Nutritional insights

## 📚 Research & Development

### 🔬 Model Development Resources

| Component | Resource Link |
|-----------|---------------|
| **Model Training** | [Google Colab Notebook](https://colab.research.google.com/drive/1M0wQzKp4csT_8AdALjxguuQWsFwiwEd5) |
| **Modified Mask R-CNN** | [Drive Folder](https://drive.google.com/drive/folders/1XDxeZSUcTN2f_LPRuG75htul-dfDo0A8) |
| **Detection Model** | [Trained Weights](https://drive.google.com/drive/folders/1n7wocurRnNVZ1vsERi6Vi6C46YQ_lsLY) |
| **Input Dataset** | [Sample Data](https://drive.google.com/drive/folders/1c8x9ZgkU7kaPnERfAIK2uPLjntAHyROI) |
| **Demo Video** | [System Recording](https://drive.google.com/file/d/178Qp-PEZ_xv9tHlTmofrHXwsauoc7PJI/view) |

### 📖 Published Research
- **Journal**: Jurnal Inovasi Pendidikan dan Inovasi (JIPI)
- **Paper**: [*"Food Detection and Calorie Estimation using Mask R-CNN with Telegram Integration"*](https://jurnal.stkippgritulungagung.ac.id/index.php/jipi/article/view/6972)
- **Contributions**: Novel approach to dietary monitoring using instance segmentation

## 🎯 Technical Innovations

### 🏆 Key Contributions
1. **Modified Mask R-CNN** for food-specific instance segmentation
2. **Portion-to-calorie mapping algorithm** from 2D images  
3. **Real-time Telegram integration** for practical deployment
4. **Multi-class food recognition** with high accuracy

## 👨‍💻 Author

**Raihan Aldy**
- 🎓 Researcher & Machine Learning Engineer  
- 🐙 [GitHub Profile](https://github.com/RaihanAldy)
- 📧 Contact via GitHub for collaborations

## 📄 License

This project is licensed for academic and research purposes.

---

<div align="center">

### ⭐ **If this project helps you, please give it a star!**

**Bridging AI research with practical healthcare applications**

</div>

## 🔗 Quick Links
- [📁 Full Repository](https://github.com/RaihanAldy/Foodkcal)
- [📄 Research Paper](https://jurnal.stkippgritulungagung.ac.id/index.php/jipi/article/view/6972)
- [🎬 Video Demo](https://drive.google.com/file/d/178Qp-PEZ_xv9tHlTmofrHXwsauoc7PJI/view)

---
