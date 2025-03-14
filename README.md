[![](https://img.shields.io/badge/Contribute-Welcome-green)](./CONTRIBUTING.md)

# Edge Vision: A Practical Guide

## Overview

This repository serves as a comprehensive, practical guide for deploying optimized computer vision models on edge devices across key industries. 

## Motivation

The goal is to bridge the gap between theoretical computer science and real-world applications, with a focus on edge AI engineering.

### Key Features
- Fundamental concepts and practices for Edge AI
- Industry-specific blueprints for vision AI deployment
- Edge optimization techniques for various hardware targets
- Production-ready pipelines and best practices
- Practical case studies and hands-on projects

## Table of Contents
- [Edge AI Engineering](#edge-ai-engineering)
- [Industry Blueprints](#industry-blueprints)
- [Edge Optimization Lab](#edge-optimization-lab)
- [Production Pipelines](#production-pipelines)
- [Reference Architectures](#reference-architectures)
- [Getting Started](#getting-started)
- [Contributing](#contributing)
- [License](#license)

## Edge AI Engineering

Fundamental concepts and practices for Edge AI:
- [Introduction to Edge AI](https://github.com/afondiel/edge-ai-engineering/blob/main/docs/introduction-to-edge-ai.md)
- [Edge AI Architectures](https://github.com/afondiel/edge-ai-engineering/blob/main/docs/edge-ai-architectures.md)
- [Model Optimization Techniques](https://github.com/afondiel/edge-ai-engineering/blob/main/docs/model-optimization-techniques.md)
- [Hardware Acceleration](https://github.com/afondiel/edge-ai-engineering/blob/main/docs/hardware-acceleration.md)
- [Edge Deployment Strategies](https://github.com/afondiel/edge-ai-engineering/blob/main/docs/edge-deployment-strategies.md)
- [Real-Time Processing](https://github.com/afondiel/edge-ai-engineering/blob/main/docs/real-time-processing.md)
- [Privacy and Security](https://github.com/afondiel/edge-ai-engineering/blob/main/docs/privacy-and-security.md)
- [Edge AI Frameworks](https://github.com/afondiel/edge-ai-engineering/blob/main/docs/edge-ai-frameworks.md)
- [Benchmarking and Performance](https://github.com/afondiel/edge-ai-engineering/blob/main/docs/benchmarking-and-performance.md)  
  
## Industry Blueprints

Practical implementation guides for:
- Autonomous Systems
- Medical Imaging
- Smart Retail
- Security & Surveillance
- Agriculture
- Manufacturing
- Smart Cities

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
│   │   ├── drone-navigation-lite.md
│   │   ├── pedestrian-tracking-edgetpu.md
│   │   └── vehicle-defect-detection-openvino.md
│   ├── healthcare-medical-imaging/
│   │   ├── xray-classification-tflite.md            
│   │   ├── ultrasound-segmentation-ncnn.md
│   │   ├── mri-tumor-detection-onnx.md
│   │   └── remote-patient-monitoring-jetson.md
│   ├── retail-consumer-analytics/
│   │   ├── shelf-analytics-mmdetection.md
│   │   ├── checkout-automation.md
│   │   ├── customer-behavior-analysis-openvino.md
│   │   └── inventory-management-edge-tflite.md
│   ├── security-surveillance/
│   │   ├── perimeter-surveillance-yolo.md
│   │   ├── anomaly-detection-autoencoder.md
│   │   ├── facial-recognition-privacy-preserving.md
│   │   └── crowd-behavior-analysis-edge.md
│   ├── agriculture-precision-farming/
│   │   ├── crop-health-monitoring-multispectral.md
│   │   ├── yield-prediction-edge-ml.md
│   │   └── autonomous-harvesting-robotics.md
│   ├── manufacturing-quality-control/
│   │   ├── defect-detection-openvino.md             
│   │   ├── robotic-picking-ort.md
│   │   └── predictive-maintenance-edge-analytics.md
│   └── smart-cities-urban-planning/
│       ├── traffic-flow-optimization-edge.md
│       ├── waste-management-vision-ai.md
│       └── energy-grid-monitoring-federated.md
├── edge-optimization-lab/                         
│   ├── model-quantization/
│   │   ├── post-training-int8.md
│   │   └── qat-pytorch.md
│   ├── pruning-techniques/
│   │   ├── magnitude-pruning.md
│   │   └── lottery-ticket-hypothesis.md
│   ├── federated-learning/
│   │   ├── privacy-preserving-cv.md
│   │   └── distributed-training.md
│   ├── compiler-targets/
│   │   ├── tvm-tutorial.md
│   │   └── onnx-runtime-guide.md
│   └── hardware-specific-optimization/
│       ├── nvidia-jetson-optimization.md
│       ├── intel-openvino-deployment.md
│       ├── raspberry-pi-edge-ai.md
│       └── microcontroller-tinyml.md
├── production-pipelines/                           
│   ├── ci-cd-for-edge.md
│   ├── monitoring/
│   │   ├── drift-detection.md
│   │   └── edge-metrics-dashboard.md
│   ├── ota-updates.md
│   └── edge-security/
│       ├── secure-boot-implementation.md
│       ├── data-encryption-edge.md
│       ├── threat-detection/
│       │   ├── perimeter-surveillance.md
│       │   └── anomaly-detection.md
│       ├── privacy-preserving-cv/
│       │   ├── federated-learning-techniques.md
│       │   └── differential-privacy.md
│       ├── model-security/
│       │   └── adversarial-robustness.md
│       ├── edge-device-hardening/
│       │   ├── secure-deployment.md
│       │   └── secure-communication.md
│       └── industry-compliance/
│           ├── regulatory-standards.md
│           └── ethical-ai-guidelines.md
├── reference-architectures/
│   ├── industrial-camera-setups.md
│   ├── edge-server-specs.md
│   ├── iot-connectivity.md
│   └── edge-cloud-hybrid-models.md
└── _integration/
    ├── cs-notebook-redirects.md                   
    ├── companion-resources.md
    └── industry-specific-regulations.md
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
- Core: [Edge AI concepts and resources](https://github.com/afondiel/computer-science-notebook/tree/master/core/systems/edge-computing/edge-ai)
- Blog: [The Next AI Frontier is at the Edge](https://afondiel.github.io/posts/the-next-ai-frontier-is-at-the-edge/)
- [Computer Vision Notes](https://github.com/afondiel/computer-science-notebook/tree/master/core/ai-ml/computer-vision-notes)
- [Computer Vision Course - HF (@johko)](https://github.com/johko/computer-vision-course)

Books:
- [Machine Learning Systems: Principles and Practices of Engineering Artificially Intelligent Systems (Vijay Janapa Reddi)](https://mlsysbook.ai/)

[Back to the Top](#table-of-contents)
