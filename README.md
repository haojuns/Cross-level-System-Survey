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

1. AIoT设备资源有限，难以满足深度学习模型对实时推理和低成本训练的高要求，如何在资源受限环境中保持模型高精度和实时性是关键挑战。

2. 模型压缩与系统调度技术虽可降低资源需求，但常需在模型精度与系统复杂性之间妥协，难以在所有场景中保持一致性能。

3. 现有跨层优化多针对特定系统层次，缺乏全面的协同优化框架，难以应对AIoT环境的动态性和多样性。

4. AIoT应用的动态性和异质性使得在不同设备间实现高效数据传输和任务调度，进一步提升系统效率，成为亟待解决的问题。
---

## 3. 动机 🔍


随着AIoT设备的激增，分布式的传感数据在多种模态下迅速增加，这为在设备本地执行DL推理和训练任务提供了新的机会，而不仅仅依赖于传统的云计算中心。通过在本地处理数据，我们可以减少带宽消耗，降低延迟，并且更好地保障用户隐私。其次，现有的深度学习优化技术大多仅在单一层次上进行优化，忽略了跨层次优化的潜力。因此，我们旨在提出一个涵盖算法层、系统层和硬件层的全面跨层优化框架，以充分利用AIoT系统的资源，提高整体计算效率和性能。最后，由于AIoT应用的动态性和复杂性，我们希望通过设计上下文感知的控制器，实现跨设备、跨层次的自适应优化，使AIoT系统能够在不同的应用场景下自动调整以满足多样化的性能需求。这不仅可以推动资源高效AIoT系统的发展，还可以为未来研究提供更广阔的探索空间。
---

## 4. 跨层系统优化空间 🚀

---

## 5. 系统实用性 🔧




