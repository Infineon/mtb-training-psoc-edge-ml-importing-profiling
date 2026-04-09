# PSOC™ Edge Training - Importing and profiling a pre-trained machine learning model on PSOC™ Edge

This training introduces why and how to optimize neural network (NN) models for deployment on
PSOC™ Edge devices. It highlights that techniques such as pruning, sparsity, and quantization can
significantly reduce model size and memory footprint while improving computational efficiency and lowering power consumption. The session includes hands-on labs demonstrating the dramatic performance and memory
benefits of enabling machine learning optimizations.

## Device family
- [PSOC™ Edge](https://www.infineon.com/products/microcontroller/32-bit-psoc-arm-cortex/32-bit-psoc-edge-arm)

## How to Use This Training
1. Download the training [content](#content).
2. Watch the video or review the presentation at your own pace.
3. Follow the step-by-step instructions in the training manual during the hands-on sections.

## Training level
- E3: Advanced

## Pre-requisites
### Recommended trainings
- This training does not cover the basic concepts of ModusToolbox™ and PSOC™ Edge.
  - For an introduction to PSOC™ MCUs, including getting started guides to ModusToolbox™, go to the [PSOC™ Developer Journey](https://www.infineon.com/PSOCdeveloper).
  - For PSOC™ Edge trainings, from beginner tutorials to advanced sessions, visit the [PSOC™ Edge E84 Training Collection](https://infineon-academy.csod.com/ui/lms-learner-playlist/PlaylistDetails?playlistId=8f04565f-88f4-4ca7-83b3-22e501656fbd).

### Tools (see [training manual](#content) for versions and installation instructions)
- [ModusToolbox™ with Eclipse IDE](https://softwaretools.infineon.com/tools/com.ifx.tb.tool.modustoolboxsetup)
- [Edge Protect Security Suite](https://softwaretools.infineon.com/tools/com.ifx.tb.tool.modustoolboxsetup)
- [ModusToolbox™ Programming tools](https://softwaretools.infineon.com/tools/com.ifx.tb.tool.modustoolboxsetup)
- Terminal emulator

## Hardware
- [KIT_PSE84_EVAL](https://www.infineon.com/evaluation-board/KIT-PSE84-EVAL)

## Duration
- 60 min, including the video and hands-on labs

## Agenda
1. PSOC™ Edge and ML development ecosystem
2. Machine learning: development workflows
3. Using DEEPCRAFT™ Model Converter to deploy a pre-trained model
4. Lab 1: Deploy a model on PSOC™ Edge using the machine learning DEEPCRAFT™ profiler
5. Lab 2: Performance improvement across CPUs and NPUs
6. Lab 3: Performance improvement with internal memories

## Expected Outcome
- Understand why optimizing neural network models is essential for deployment on resource-constrained edge devices
- Learn key optimization techniques—pruning, sparsity, and particularly quantization—and when to apply them
- Compare performance across different processor cores and memories
- Understand the machine learning deployment workflow, specifically for pre-trained model deployment using DEEPCRAFT™ Model Converter

## Content
- [Training video at Infineon Academy](https://infineon-academy.csod.com/ui/lms-learning-details/app/video/1929a16f-0f00-4339-8f0d-e95194f7b290)
- [Presentation](./Presentation/PSE_ML_Profiling_Pretrained_model.pdf)
- [Training manual](./Manual/PSE_ML_Profiling_Pretrained_model_Training_Manual.pdf)

## References and resources

- [PSOC™ Edge MCUs](https://www.infineon.com/products/microcontroller/32-bit-psoc-arm-cortex/32-bit-psoc-edge-arm)
- [Infineon Edge Protect](https://www.infineon.com/promo/edge-protect)
- [Introduction to PSOC™ MCUs and ModusToolbox™](https://www.infineon.com/PSOCdeveloper)
- [PSOC™ Edge E84 training collection](https://infineon-academy.csod.com/samldefault.aspx?ouid=1&returnURL=%252fDeepLink%252fProcessRedirect.aspx%253fmodule%253dphnxdriver%2526routename%253dAdmin%252fPlayerPageRedirectHandler%2526Route%253d%25252flms-learner-playlist%25252fPlaylistDetails%2526Parameters%253dplaylistId%25253d8f04565f-88f4-4ca7-83b3-22e501656fbd)

## History

| Date | Version | Description |
| ---- | ------- | ----------- |
| 04/09/2026 | ** | First public release |
