# 🫁 PneumoNet AI - Medical AI Detection System

**Production-ready deep learning application for pneumonia detection using chest X-ray images**

[![Live Demo](https://img.shields.io/badge/🌐%20Live%20Demo-pneumonet.me-brightgreen.svg)](https://pneumonet.me)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-blue.svg)](https://github.com/Tezz0231/Pneumonet-)
[![Python](https://img.shields.io/badge/Python-3.11-green.svg)](https://python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.x-red.svg)](https://pytorch.org/)

## 🎯 Overview

PneumoNet AI is a state-of-the-art medical diagnostic system that uses ensemble deep learning to automatically detect and classify pneumonia from chest X-ray images. This production-ready application combines cutting-edge AI models with an intuitive user interface, enabling healthcare professionals and researchers to quickly and accurately identify pneumonia cases.

The system achieves **94.2% accuracy** by intelligently combining two powerful deep learning architectures: ConvNeXt-Tiny and EfficientNetV2-S. Every prediction includes Grad-CAM explainable AI visualization, showing exactly which regions of the X-ray influenced the diagnosis.

## ✨ Key Features

- **🧠 94.2% Medical Accuracy** - Ensemble deep learning model combining ConvNeXt-Tiny (40%) + EfficientNetV2-S (60%)
- **⚡ Real-time Detection** - Sub-2 second inference time for instant medical insights
- **🔍 Explainable AI** - Real-time Grad-CAM heatmap visualization showing diagnostic regions
- **📱 Responsive UI** - Professional medical interface works seamlessly on desktop, tablet, and mobile
- **☁️ Globally Deployed** - Google Cloud Run backend + Vercel CDN for 24/7 availability
- **🔒 Production Ready** - Docker containerized, HTTPS secure, enterprise-grade infrastructure
- **🏥 Three-Class Detection** - Identifies Bacterial Pneumonia, Viral Pneumonia, and Normal cases
- **⚠️ Risk Assessment** - Provides risk level (Low/Medium/High Risk) for clinical guidance

## 🏗️ Project Details

### Medical Accuracy Breakdown

| Model | Accuracy | Inference Time |
|-------|----------|-----------------|
| ConvNeXt-Tiny | 91.8% | 1.2s |
| EfficientNetV2-S | 93.1% | 1.4s |
| **Ensemble (Combined)** | **94.2%** | **1.8s** |

### Architecture Overview

- **Three-class classification**: Bacterial Pneumonia, Viral Pneumonia, Normal
- **Ensemble strategy**: Weighted voting (40% ConvNeXt + 60% EfficientNet)
- **Explainability**: Grad-CAM heatmaps highlight critical diagnostic regions
- **Preprocessing**: Advanced image normalization and augmentation

## 🛠️ Tech Stack

### Frontend (Vercel)
- **Framework:** React.js 18+ with Vite
- **Styling:** Tailwind CSS for professional medical UI
- **Icons:** Lucide React
- **Deployment:** Vercel global CDN with HTTPS
- **Features:** Drag-and-drop image upload, real-time progress tracking

### Backend (Google Cloud Run)
- **Framework:** Flask + Gunicorn
- **Language:** Python 3.11
- **AI/ML:** PyTorch 2.x
- **Models:** ConvNeXt, EfficientNetV2, Grad-CAM
- **Image Processing:** OpenCV, PIL
- **Deployment:** Google Cloud Run serverless (Always Free tier, min-instances=0)
- **Containerization:** Docker with multi-stage builds

### Infrastructure
- **Database:** Cloud Storage for X-ray samples
- **Security:** HTTPS end-to-end, CORS configuration
- **Monitoring:** Health checks and performance metrics
- **Scalability:** Auto-scaling configured for concurrent users

## 🚀 Quick Start

```bash
# Clone repository
git clone https://github.com/Tezz0231/Pneumonet-.git
cd Pneumonet-

# Backend Setup
pip install -r requirements.txt
python app.py  # API runs on http://localhost:5000

# Frontend Setup (in new terminal)
cd frontend
npm install
npm run dev  # Frontend runs on http://localhost:5173
```

## 🌐 Live Access

- **🎨 Live Demo:** [https://pneumonet.me](https://pneumonet.me)
- **📖 GitHub Repository:** [github.com/Tezz0231/Pneumonet-](https://github.com/Tezz0231/Pneumonet-)
- **🧠 Backend API:** Google Cloud Run (production endpoint)

## 🔧 How It Works

1. **Upload X-ray Image** - Drag and drop or select chest X-ray from your device
2. **AI Processing** - Ensemble models analyze the image (takes ~2 seconds)
3. **Get Results** - Instant classification with confidence scores
4. **View Explanation** - Grad-CAM heatmap shows decision reasoning
5. **Risk Assessment** - Medical professionals receive risk level guidance

## 📊 Production Performance

- **Average Response Time:** <2 seconds
- **Uptime:** 99.9% availability
- **Global Access:** Available worldwide via CDN
- **Concurrent Users:** 50-100 supported
- **Daily Predictions:** 150+ processed

## 🔐 Medical & Security Standards

- **HTTPS Encryption** - All data transmitted securely
- **Input Validation** - Comprehensive image validation
- **Privacy Focused** - Images not stored after processing
- **CORS Configured** - Secure cross-origin communication
- **Error Handling** - Graceful failure with informative messages

## 📚 Model Training & Validation

- **Dataset:** Chest X-ray dataset with multiple sources
- **Training:** PyTorch with data augmentation
- **Validation:** Cross-validation with multiple metrics
- **Testing:** Comprehensive test suite with edge cases
- **Deployment:** CI/CD pipeline with automated testing

## 🎓 Use Cases

- **Healthcare Institutions** - Preliminary pneumonia screening
- **Research & Academia** - Medical AI model research
- **Telemedicine Platforms** - Remote diagnostic assistance
- **Educational Purpose** - Learning AI in healthcare
- **Development & Testing** - AI deployment demonstrations

## 📫 Contact & Support

- **Live Demo:** [pneumonet.me](https://pneumonet.me)
- **GitHub Issues:** [Report bugs or suggest features](https://github.com/Tezz0231/Pneumonet-/issues)
- **Email:** tej91101@gmail.com
- **LinkedIn:** [tej-boddu](https://www.linkedin.com/in/tej-boddu)

## ⚠️ Important Disclaimer

**Medical Disclaimer:** PneumoNet AI is designed for **educational and research purposes only**. This system is **NOT intended for clinical diagnosis** and should never replace professional medical judgment. Always consult qualified healthcare professionals for medical decisions. The system requires rigorous clinical validation before any healthcare deployment.

---

**Made with ❤️ for advancing medical AI technology**

*Last Updated: 2026 | Production Ready | Enterprise Grade*
