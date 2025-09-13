# 👋 Welcome to MLArtisan

**MLArtisan** is a developer-friendly platform to **build, train, and deploy machine learning models** with minimal setup.  
It combines **schema-based data workflows**, **model versioning**, and **flexible deployment** options — all in one place.

---

## 🚀 What You Can Do with MLArtisan
- Define input/output **schemas** to structure your data  
- Upload and manage datasets with ease  
- Train models using multiple algorithms (Neural Networks, RNN, KMeans, ONNX, and more)  
- Track **model versions** and history  
- Deploy models via **REST API** or **self-host with Docker**  

---

## 📦 Quick Start (Self-Hosted)

Run MLArtisan locally with Docker:

```bash
docker run -d -p 80:80 \
  -e ConnectionStrings__DefaultConnection="Host=your-host;Database=your-db;Port=5432;Username=your-user;Password=your-pass;Ssl Mode=Disable" \
  alexeymlartisan/mlartisan-selfhosted
```

👉 See setup and configuration options here: [Docker Hub → MLArtisan Selfhosted](https://hub.docker.com/r/alexeymlartisan/mlartisan-selfhosted#️-configuration-validation)

---

## 🌍 Live Demo

Try the cloud version here: [mlartisan.com](https://mlartisan.com)

---

## 📣 Join Us

We’re looking for **early adopters** 🚀  
If you’d like to test MLArtisan and share feedback:  
- ⭐ Star this org  
- 🐛 Open issues  
- 💬 Share ideas  

---

## 📅 Recent Updates
- **ONNX import support** (map inputs/outputs to schemas, versioning, API/UI predictions)  
- **Initial release**: schema creation, dataset upload, Neural Networks & KMeans training, REST API support  

---

## 📬 Contact
Follow updates here on GitHub or visit [mlartisan.com](https://mlartisan.com).  
For questions or collaboration, feel free to open an issue or reach out on [LinkedIn](https://linkedin.com).  
