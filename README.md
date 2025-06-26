# MultiMMNet: Multi Model Structure-Agnostic Framework for Enhanced Materials Discovery in Engineering Informatics

Multi-Model Material Network (MultiMMNet) is a structure-agnostic deep learning framework designed to accurately predict material properties using only compositional information. The architecture integrates five key components: a Transformer to capture global contextual relationships, a Convolutional Neural Network (CNN) for local pattern extraction, a Pairwise Interaction module to model element-to-element relationships, a Cross Attention mechanism to align and fuse feature representations, and a Gated Linear Unit with Attention Network (GLUAN) for nonlinear feature modulation and interpretability. Together, these modules enable MultiMMNet to learn complex inter-element interactions and adaptively assign importance to elements within a composition. Evaluated on benchmark datasets, the model outperforms existing methods and sets new state-of-the-art performance in structure-agnostic materials property prediction.

---

## 🔑 Key Highlights

- **Structure-Agnostic Framework**: Predicts material properties using only compositional information no crystal structures required.
- **Comprehensive Multi-Module Design**: Integrates Transformer, CNN, Pairwise Interaction, Cross Attention, and GLUAttnNetwork modules to capture complex inter-element dependencies.
- **Fractional Encoding Module**: Enriches representations of element fractions, including ultra-low-concentration dopants.
- **GLUA Attention Mechanism**: Gated Linear Unit with Attention enables refined feature weighting and improved generalization in property prediction.
- **Interpretability**: Provides attention-based heatmaps and element-wise contribution analysis.
- **Scalable and Modular**: Easily extensible to new property types and data sources.

---

## 🧪 Applications

MultiMMNet addresses critical challenges in materials science, with applications in:

- **Accelerated discovery of novel materials** for energy storage, thermoelectrics, catalysis, and semiconductor applications.
- **Advanced composition-driven property prediction** without the need for structural input, enabling efficient exploration of large chemical design spaces.
- **Modeling dopant effects** at ultra-low concentrations (e.g., ppm-level), supporting precision design in electronic and functional materials.
- **Computational guidance for experimental synthesis**, helping prioritize high-potential compositions for lab validation.
- **Interpretability-driven design**, providing insights into element-wise contributions to material properties.

---

## 💻 Code Availability

The code for **MultiMMNet** will be made publicly available following the acceptance of the associated research paper.  
Updates regarding the release will be provided on this repository.

---

## 🙏 Acknowledgment

This research was supported by the **Nano & Material Technology Development Program** through the **National Research Foundation of Korea (NRF)** funded by the **Ministry of Science and ICT**.  
**Project Name**: Data HUB for Solid Electrolyte Materials Based on SyncroLab Data Cloud  
**Grant Number**: RS-2024-00446825

---

## 📜 License

Upon publication, this project will be released under an **open-source license**, ensuring accessibility to the research and development community.

---
