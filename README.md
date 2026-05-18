# PyTorch CNN Image Classification

A CNN-based image classification project built with PyTorch on the Intel Image Classification dataset.

## Dataset
- **Source:** [Intel Image Classification - Kaggle](https://www.kaggle.com/datasets/puneet6060/intel-image-classification)
- **Classes:** Buildings, Forest, Glacier, Mountain, Sea, Street
- **Train:** 11,228 | **Validation:** 2,806 | **Test:** 3,000

## Model
- Custom CNN architecture with PyTorch
- Hyperparameter experiments with controlled methodology
- Best configuration achieves **84% test accuracy**

## Experiments
11 hyperparameters tested:
`conv_kernel_size` | `conv_dropout` | `activation_fn` | `batch_size` | `optimizer_type` | `num_conv_layers` | `fc_hidden_units` | `pool_kernel_size` | `pool_stride` | `fc_dropout` | `num_epochs`

## Interface
Gradio-based web interface for real-time image classification.

## Tools
- Python | PyTorch | Google Colab | Gradio
