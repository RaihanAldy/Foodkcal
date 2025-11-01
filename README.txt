
# 🍎 FoodKcal - Food Detection & Calorie Estimation

<div align="center">

![Machine Learning](https://img.shields.io/badge/🤖-Machine%20Learning-FF6B6B?style=for-the-badge)
![Mask R-CNN](https://img.shields.io/badge/🧠-Mask%20R--CNN-8A2BE2?style=for-the-badge)
![Telegram Bot](https://img.shields.io/badge/🤖-Telegram%20Bot-26A5E4?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white)

**Advanced Food Detection & Calorie Estimation System using Mask R-CNN & Telegram Integration**

[![Research Paper](https://img.shields.io/badge/📄-Research_Paper-BD1E2A?style=for-the-badge&logo=googlescholar)](https://jurnal.stkippgritulungagung.ac.id/index.php/jipi/article/view/6972)
[![Demo Video](https://img.shields.io/badge/🎬-Demo_Video-FF0000?style=for-the-badge&logo=youtube)](https://drive.google.com/file/d/178Qp-PEZ_xv9tHlTmofrHXwsauoc7PJI/view)

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
User Upload → Telegram Bot → Image Preprocessing → Mask R-CNN Model 
→ Food Detection → Portion Estimation → Calorie Calculation → Bot Response
```

## 🎯 Model Performance

### 📈 Evaluation Metrics
- **mAP**: 85.7% (Mean Average Precision)
- **Detection Accuracy**: 87.3% 
- **Segmentation IoU**: 82.1%
- **Calorie Estimation Error**: ±12%

## 🚀 Quick Start

### Prerequisites
```bash
Python 3.8+
TensorFlow 2.8+
Telegram Bot Token
```

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

## 📊 Research & Development

### 🔬 Model Development Links

| Component | Link | Description |
|-----------|------|-------------|
| **Model Training** | [Google Colab](https://colab.research.google.com/drive/1M0wQzKp4csT_8AdALjxguuQWsFwiwEd5) | Complete training pipeline |
| **Modified Mask R-CNN** | [Drive Folder](https://drive.google.com/drive/folders/1XDxeZSUcTN2f_LPRuG75htul-dfDo0A8) | Custom architecture |
| **Detection Model** | [Drive Folder](https://drive.google.com/drive/folders/1n7wocurRnNVZ1vsERi6Vi6C46YQ_lsLY) | Trained model weights |
| **Input Dataset** | [Drive Folder](https://drive.google.com/drive/folders/1c8x9ZgkU7kaPnERfAIK2uPLjntAHyROI) | Model input samples |
| **Demo Video** | [Recording](https://drive.google.com/file/d/178Qp-PEZ_xv9tHlTmofrHXwsauoc7PJI/view) | System demonstration |

### 📚 Published Research
- **Journal**: Jurnal Inovasi Pendidikan dan Inovasi (JIPI)
- **Paper**: ["Food Detection and Calorie Estimation using Mask R-CNN with Telegram Integration"](https://jurnal.stkippgritulungagung.ac.id/index.php/jipi/article/view/6972)

## 👨‍💻 Author

**Raihan Aldy**
- 🎓 Researcher & Machine Learning Engineer
- 🐙 [GitHub](https://github.com/RaihanAldy)

---

<div align="center">

**⭐ Star this repository if you find it helpful!**

</div>
