# RGB → CMYK Neural Converter

A neural network model for converting colors from RGB to CMYK color space. The project consists of a training script and a GUI application for visual testing.

## 🎯 How it works

The neural network is trained on random RGB values using:
- **Architecture**: single fully connected layer (3 inputs → 4 outputs)
- **Activation**: sigmoid function
- **Loss function**: MSE (Mean Squared Error)
- **Optimizer**: gradient descent

Target values (ground truth) are calculated using the mathematical RGB → CMYK formula.

## 📁 Project structure

| File | Purpose |
|------|---------|
| `hello.py` | Train the model, save weights |
| `test.py` | GUI for testing the model |
| `cmyk_model_weights.npz` | Weights file (generated automatically) |