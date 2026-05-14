# Case Study: Reducing AI Inference Costs by 98% via Quantization and Serverless CPU Deployment

## Problem: High GPU Costs

Running a large language model on a cloud GPU can be expensive.

Example:
- AWS SageMaker ml.g4dn.xlarge (NVIDIA T4 GPU): $0.7364/hour
- Monthly cost (24/7): $530.21/month

This creates a major cost barrier for startups and independent developers.

## Solution: Quantized CPU Deployment

In this project, I will demonstrate how to:

1. Quantize an AI model to reduce memory usage.
2. Run the model efficiently on CPU-only infrastructure.
3. Deploy it on a free Hugging Face Space.
4. Compare performance and cost savings.

Target result:
- Standard GPU deployment: $530.21/month
- Quantized CPU deployment: $0/month
- Estimated cost reduction: 100%

## Status

- [x] GitHub repository created
- [ ] Quantized model loaded in Google Colab
- [ ] Model tested successfully
- [ ] Hugging Face Space deployed
- [ ] Cost analysis completed
