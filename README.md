# COMS 6998 Final Project
**COMS 6998 Model Compression and Acceleration Analysis of different Models**

Submitted by: Adit Deshmukh (avd2133), Vani Jain (vj2245)

**EfficientNet Optimization**
- Trained an EfficientNet model on CIFAR-100 

- Quantized the model and used the following quantization techniques:
  - Dynamic Range Quantization
  - Full Integer Quantization
  - Float 16 Quantization

- Pruned the model at 0.2, 0.4, 0.6 and 0.8 Sparsity levels

Please refer to EfficientNetOptimization.ipynb for EfficientNet Optimization code.

**MobileNet Optimization**
- Trained an MobileNet model on CIFAR-100 

- Quantized the model and used the following quantization techniques:
  - Dynamic Range Quantization
  - Full Integer Quantization
  - Float 16 Quantization

- Pruned the model at 0.2, 0.4, 0.6 and 0.8 Sparsity levels

Please refer to MobileNetOptimization.ipynb for MobileNet Optimization code.

utils.py provides several functions which can be used to apply different types of quantizations to models and evaluate quantized models using tensorflow lite.
