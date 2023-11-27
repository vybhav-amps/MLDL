# Feature Scaling Methods in Python

This project demonstrates various feature scaling methods using Python's `scikit-learn` library. Feature scaling is a crucial step in preprocessing for many machine learning algorithms, especially those sensitive to the scale of input features.

## Installation

To run the code, you need to have Python installed along with the `scikit-learn` library. You can install `scikit-learn` using pip:

\```bash
pip install scikit-learn
\```

## Feature Scaling Techniques

The following feature scaling methods are implemented:

### 1. Standardization (Z-Score Normalization)
- Rescales features to have a mean of zero and a standard deviation of one.
- Usage: Ideal for algorithms that assume a Gaussian distribution in the input features.

### 2. Min-Max Scaling
- Rescales the data to a fixed range, typically [0, 1].
- Usage: Useful when you need bounded values.

### 3. MaxAbsScaler
- Scales each feature by its maximum absolute value.
- Usage: Suitable for data that is already centered at zero.

### 4. Robust Scaler
- Scales features using statistics that are robust to outliers.
- Usage: Best for data with outliers.

### 5. Normalizer
- Scales individual samples to have unit norm.
- Usage: Often used when the magnitude of data matters more than the raw values.

### 6. Power Transformer
- Applies a power transformation to make data more Gaussian-like.
- Usage: Good for data with a non-Gaussian distribution.

### 7. Quantile Transformer
- Transforms features to follow a uniform or normal distribution.
- Usage: Beneficial for non-linear data.

