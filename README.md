[![](https://img.shields.io/badge/Contribute-Welcome-green)](./CONTRIBUTING.md)

# Edge Vision :eye: | A Practical Guide

A practical guide for real-world computer vision applications for resource-constrained devices with industry standards in mind.

## New to Edge AI? 

- Start with the [Edge AI Engineering](https://github.com/afondiel/edge-ai-engineering): a practical guide covering core concepts of the entire [Edge AI MLOps](https://docs.edgeimpulse.com/docs/concepts/edge-ai-fundamentals/what-is-edge-mlops) stack with industry blueprints.
- Then read this: [The Next AI Frontier is at the Edge](https://afondiel.github.io/posts/the-next-ai-frontier-is-at-the-edge/)
- Related work: [Edge Audio](https://github.com/afondiel/edge-audio)


## Table of Contents
- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Contributing](#contributing)
- [License](#license)
- [Resources](#resources)

## Introduction

The goal of this guide is to provide resources for building, optimizing, and deploying Computer Vision applications at the edge, through hands-on examples including practical notebooks and real-world use cases across key industries.

### Key Concepts

**Industry Blueprints**
- Autonomous Systems
- Healthcare & Medical Imaging*
- Retail & Consumer Analytics
- Security & Surveillance
- Agriculture & Precision Farming
- Manufacturing & Quality Control
- Smart Cities & Urban Planning

**Edge Optimization Lab**: techniques and tools for maximizing performance and efficiency of vision models on edge hardware
- Model Quantization
- Pruning Techniques
- Federated Learning
- Compiler Targets
- Hardware-Specific Optimization

**Production Pipelines**: guides and templates for robust, scalable edge vision AI operations
- CI/CD for Edge
- Monitoring (Drift Detection, Edge Metrics Dashboard)
- OTA Updates
- Edge Security (Secure Boot, Data Encryption, Threat Detection, Privacy-Preserving vision, Adversarial Robustness, Device Hardening, Compliance)

**Reference Architectures**: blueprints for edge vision hardware and system design
- Microphone Array Setups
- Edge Server Specs
- IoT Connectivity
- Edge-Cloud Hybrid Models

**Integration**
- Notebooks (hands-on deep dives)
- Companion Resources
- Industry-Specific Stardards

## Project Structure

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
```bash
git clone https://github.com/afondiel/edge-vision.git
```
2. Navigate to the industry blueprint or topic you're interested in.
3. Follow the step-by-step guides to implement and deploy edge vision solutions.

## Contributing

We welcome contributions! Please see our [CONTRIBUTING.md](CONTRIBUTING.md) file for details on how to submit improvements.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Resources

- [Computer Vision Notes](https://github.com/afondiel/computer-science-notebook/tree/master/core/ai-ml/computer-vision-notes)
- [The Hugging Face Course on Computer Vision](https://github.com/johko/computer-vision-course)

Books:
- [Machine Learning Systems: Principles and Practices of Engineering Artificially Intelligent Systems (Vijay Janapa Reddi)](https://mlsysbook.ai/)

[Back to the Top](#table-of-contents)
