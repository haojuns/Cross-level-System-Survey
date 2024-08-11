# Enabling Resource-efficient AIoT System with Cross-level Optimization: A survey

> 随着深度学习在物联网智能基础设施中的广泛应用，各种AIoT（人工智能物联网）应用成为可能。然而，基础设备有限的资源限制了深度计算任务的执行效率。如何提高这些任务的部署效率，成为一个涉及多层优化的问题，包括上层模型结构、底层系统调度，以及它们之间的相互影响。为扩展物联网中深度学习部署和优化的研究范围，我们深入调研了现有的优化技术，涵盖了本地和分布式计算中的深度学习模型、计算图、运算符、内存调度和硬件指令。我们的研究成果《**[Enabling Resource-efficient AIoT System with Cross-level Optimization: A survey](https://ieeexplore.ieee.org/document/10265028)**》已发表在IEEE Communications Surveys & Tutorials期刊上，为跨层优化提供了更广泛的空间。

---

## 1. 引用格式 📚

```bibtex
@article{liu2023enabling,
  title={Enabling resource-efficient aiot system with cross-level optimization: A survey},
  author={Liu, Sicong and Guo, Bin and Fang, Cheng and Wang, Ziqi and Luo, Shiyan and Zhou, Zimu and Yu, Zhiwen},
  journal={IEEE Communications Surveys \& Tutorials},
  year={2023},
  publisher={IEEE}
}
```

---

## 2. 问题 📚

1. AIoT设备资源有限，难以满足深度学习模型实时推理和低成本训练要求，并在资源受限环境中保持模型高精度和实时性。

2. 模型压缩与系统调度技术虽可降低资源需求，但常需在模型精度与系统复杂性之间妥协，难以在所有场景中保持一致性能。

3. 现有跨层优化多针对特定系统层次，缺乏全面的协同优化框架，难以应对AIoT环境的动态性和多样性。

4. AIoT应用的动态性和异质性使得在不同设备间实现高效数据传输和任务调度，进一步提升系统效率，成为亟待解决的问题。
---

## 3. 动机 🔍

1. AIoT设备激增导致分布式多模态数据增加，本地执行DL推理和训练任务可减少带宽消耗、降低延迟，并提升隐私保护。

2. 现有DL优化技术多在单一层次进行，忽视跨层次潜力。我们旨在提出涵盖算法、系统和硬件的跨层优化框架，以提升AIoT系统资源利用率和整体性能。

3. AIoT应用动态复杂，通过设计上下文感知控制器，实现跨设备、跨层次的自适应优化，以满足不同场景的多样化性能需求。

---

## 4. 跨层系统优化空间 🚀

---

## 5. 系统实用性 🔧




