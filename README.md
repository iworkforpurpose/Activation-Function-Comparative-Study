# Activation-Function-Comparative-Study

## Overview
This research project provides an in-depth comparative analysis of activation functions across two distinct machine learning datasets: MNIST (handwritten digit recognition) and Titanic (passenger survival prediction).

## 🔬 Research Objectives
- Compare performance of different activation function configurations
- Analyze impact of optimizers on model learning
- Provide insights into activation function selection strategies

## 📊 Experiments Conducted

### Activation Function Configurations
1. ReLU → Sigmoid → Tanh → Sigmoid/Softmax
2. ReLU → ReLU → ReLU → Sigmoid/Softmax
3. Sigmoid → Sigmoid → Sigmoid → Sigmoid/Softmax
4. Tanh → Tanh → Tanh → Sigmoid/Softmax

### Optimizers
- ADAM
- Stochastic Gradient Descent (SGD)
- RMSProp

## 🧠 Datasets
1. **MNIST**: Handwritten digit recognition
   - 28x28 pixel grayscale images
   - 10 classification categories (0-9)

2. **Titanic**: Passenger survival prediction
   - Structured dataset with mixed feature types
   - Binary classification (survived/not survived)

## 📈 Key Findings

### MNIST Dataset
- Best Configuration: ReLU → ReLU → ReLU → Softmax
  - Peak Accuracy: 96.30%
  - Lowest Loss: 0.1300

### Titanic Dataset
- Best Configuration: ADAM with ReLU → Sigmoid → Tanh → Sigmoid
  - Most stable learning curve
  - Lowest final test loss

## 🛠 Prerequisites
- Python 3.8+
- TensorFlow/Keras
- NumPy
- Matplotlib
- Pandas

## 📦 Installation
```bash
git clone https://github.com/yourusername/activation-function-study.git
cd activation-function-study
pip install -r requirements.txt
```

## 🚀 Running Experiments
```bash
python mnist_experiments.py
python titanic_experiments.py
```

## 📊 Visualization
- Epoch-level Training Loss
- Test Accuracy
- Batch Loss Distribution
- Cumulative Batch Losses
- Performance Metrics Heatmap

## 🔍 Key Insights
- ReLU shows superior performance in complex classification tasks
- ADAM optimizer provides fastest and most stable convergence
- Mixed activation functions offer enhanced model flexibility

## 📝 Research Methodology
1. Implement multiple activation function configurations
2. Train models using different optimizers
3. Compare performance metrics
4. Visualize and analyze results

## 🤝 Contributing
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📈 Future Work
- Explore additional activation functions
- Investigate hyperparameter tuning
- Expand to more diverse datasets
