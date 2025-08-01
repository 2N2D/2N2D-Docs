# Neural Network Development Dashboard (2N2D)

**2N2D** is a web application designed to streamline and simplify the development of Machine Learning models. It empowers users without technical expertise to create high-performance models intuitively, while experienced ML developers can focus on critical decisions without wasting time on debugging, result interpretation, or model tuning.

The primary goal is to democratize access to this innovative technology that plays an increasingly important role in our daily lives.

# Documentation:
(RO) https://drive.google.com/file/d/1ozr5ss6TD7PaJcJHNaqzic1Qh808WX8L/view?usp=sharing
---
https://2n2d.tml-soft.dev/docs
---
-[2N2D API](https://github.com/2N2D/2N2D-API)
-[2N2D WEB interface](https://github.com/2N2D/2N2D-WEB)
-[2N2D Legacy repo](https://github.com/2N2D/2N2D-Legacy)
---

## Features

### ONNX File Analysis and Visualization
- Upload and analyze ONNX machine learning models.
- Automatically detect architecture, operations, and activations.
- Replicate and retrain models for testing and optimization.

### CSV Dataset Processing
- Upload and visualize CSV datasets.
- Automatic detection and conversion of non-numeric columns.
- Customizable preprocessing with memory efficiency considerations.
- Generate descriptive statistics and visual graphs.

### Automatic Machine Learning Model Optimization
Three optimization methods are available:

- **Brute-force**: Retrains the model using multiple configurations, then selects the best-performing one.
- **Genetic**: Uses a genetic algorithm to evolve the model architecture across generations.
- **Neuro-evolutionary**: A more advanced genetic algorithm that modifies the entire neural network topology to generate new, problem-specific architectures.

### Machine Learning Lessons
- Built-in educational modules explaining ML concepts.
- Designed for beginners looking to understand the principles behind neural networks.

### AI Chatbot Assistant
- Intelligent chatbot with access to user models, datasets, and lessons.
- Provides real-time guidance, suggestions, and answers throughout the development process.

---

## Technologies Used

- **PyTorch** – Neural network framework  
- **ONNX** – Standard format for machine learning models  
- **NumPy** – Numerical data processing  
- **Pandas** – Tabular data preprocessing  
- **Scikit-learn** – Data preprocessing and evaluation tools  
- **NEAT** – Neuro-evolutionary optimization algorithm  
- **DEAP** – Genetic algorithm framework  
- **FastAPI** – API backend framework  
- **Next.js** – Web development framework  
- **Tailwind CSS** – UI styling  
- **React Vis** – Interactive node graph visualizations  
- **Plotly** – Data visualizations and plots  
- **Nextra** – Documentation generation framework  
- **Firebase OAuth** – User authentication  
- **PostgreSQL** – Database  
- **Cloudflare R2 Buckets** – File storage  
- **Lingui** – Internationalization  
- **Gemini** – AI chatbot integration  
- **OpenAPI** – API documentation  
- **Docker & Microservices** – Hosting and scalability

---

## Minimal Requirements

- Browser: Any modern web browser  
- Operating System: Any OS  
- RAM: 4 GB  
- CPU: Intel Celeron or equivalent  
- GPU: Intel UHD Graphics or better  
- Stable internet connection

