# Edge Computer Vision: A Practical Guide

## Overview

This repository serves as a comprehensive, practical guide for deploying optimized computer vision models on edge devices across key industries. 

## Motivation

The goal is to bridge the gap between theoretical computer science and real-world applications, with a focus on edge AI engineering.

### Key Features

- Industry-specific blueprints for vision AI deployment
- Edge optimization techniques for various hardware targets
- Production-ready pipelines and best practices
- Practical case studies and hands-on projects

## Table of Contents
- [Edge AI Engineering: Core Concepts](#edge-ai-engineering--core-concepts)
- [Industry Blueprints](#industry-blueprints)
- [Edge Optimization Lab](#edge-optimization-lab)
- [Production Pipelines](#production-pipelines)
- [Reference Architectures](#reference-architectures)
- [Getting Started](#getting-started)
- [Contributing](#contributing)
- [License](#license)

## Edge AI Engineering: Core Concepts

Fundamental concepts and practices for Edge AI:

- Core: [edge AI concepts and resources](https://github.com/afondiel/computer-science-notebook/tree/master/core/systems/edge-computing/edge-ai)
    - [Introduction to Edge AI](edge-ai-engineering/introduction-to-edge-ai.md)
    - [Edge AI Architectures](edge-ai-engineering/edge-ai-architectures.md)
    - [Model Optimization Techniques](edge-ai-engineering/model-optimization-techniques.md)
    - [Hardware Acceleration](edge-ai-engineering/hardware-acceleration.md)
    - [Edge Deployment Strategies](edge-ai-engineering/edge-deployment-strategies.md)
    - [Real-Time Processing](edge-ai-engineering/real-time-processing.md)
    - [Privacy and Security](edge-ai-engineering/privacy-and-security.md)
    - [Edge AI Frameworks](edge-ai-engineering/edge-ai-frameworks.md)
    - [Benchmarking and Performance](edge-ai-engineering/benchmarking-and-performance.md)  
- Blog: [The Next AI Frontier is at the Edge](https://afondiel.github.io/posts/the-next-ai-frontier-is-at-the-edge/)
  
## Industry Blueprints

Practical implementation guides for:
- Autonomous Systems
- Medical Imaging
- Smart Retail
- Manufacturing
- Security & Surveillance

## Edge Optimization Lab

Learn how to optimize models for edge deployment:
- Model Quantization
- Pruning Techniques
- Federated Learning
- Compiler Targets (TVM, ONNX Runtime)

## Production Pipelines

Guides for deploying and maintaining edge AI systems:
- CI/CD for Edge
- Monitoring and Drift Detection
- OTA Updates

## Reference Architectures

Hardware setups and specifications for various edge deployment scenarios.

## Project Structure

A focused resource for deploying optimized vision models on edge devices across key industries.

```
├── edge-ai-engineering/
│   ├── introduction-to-edge-ai.md
│   ├── edge-ai-architectures.md
│   ├── model-optimization-techniques.md
│   ├── hardware-acceleration.md
│   ├── edge-deployment-strategies.md
│   ├── real-time-processing.md
│   ├── privacy-and-security.md
│   ├── edge-ai-frameworks.md
│   └── benchmarking-and-performance.md    
├── industry-blueprints/
│   ├── autonomous-systems/
│   │   ├── traffic-analysis-yolov8-tensorrt.md     
│   │   └── drone-navigation-lite.md
│   ├── medical-imaging/
│   │   ├── xray-classification-tflite.md            
│   │   └── ultrasound-segmentation-ncnn.md
│   ├── smart-retail/
│   │   ├── shelf-analytics-mmdetection.md
│   │   └── checkout-automation.md
│   └── manufacturing/
│       ├── defect-detection-openvino.md             
│       └── robotic-picking-ort.md
├── edge-optimization-lab/                         
│   ├── model-quantization/
│   │   ├── post-training-int8.md
│   │   └── qat-pytorch.md
│   ├── pruning-techniques/
│   │   ├── magnitude-pruning.md
│   │   └── lottery-ticket-hypothesis.md
│   ├── federated-learning
│   │   ├── privacy-preserving-cv.md
│   │   └── distributed-training.md
│   └── compiler-targets/
│       ├── tvm-tutorial.md
│       └ onnx-runtime-guide.md
├── production-pipelines/                           
│   ├── ci-cd-for-edge.md
│   ├── monitoring/
│   │   ├── drift-detection.md
│   │   └── edge-metrics-dashboard.md
│   └── ota-updates.md
├── reference-architectures/
│   ├ :industrial-camera-setups.md
│   ├ edge-server-specs.md
│   └ iot-connectivity.md
└── _integration/
    ├── cs-notebook-redirects.md                   
    └── companion-resources.md
```

## Getting Started

1. Clone this repository:
   ```
   git clone https://github.com/yourusername/computer-vision-practical-guide.git
   ```
2. Navigate to the industry blueprint or topic you're interested in.
3. Follow the step-by-step guides to implement and deploy edge AI vision solutions.

## Contributing

We welcome contributions! Please see our [CONTRIBUTING.md](CONTRIBUTING.md) file for details on how to submit improvements.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## References

Deep Dives: 
- [Computer Vision Notes](https://github.com/afondiel/computer-science-notebook/tree/master/core/ai-ml/computer-vision-notes)
- [Computer Vision Course - HF (@johko)](https://github.com/johko/computer-vision-course)
Books:
- [Machine Learning Systems: Principles and Practices of Engineering Artificially Intelligent Systems (Vijay Janapa Reddi)](https://mlsysbook.ai/)

[Back to the Top](#table-of-contents)
