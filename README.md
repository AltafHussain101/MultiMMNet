# MultiMMNet: Multi Model Structure-Agnostic Framework for Enhanced Materials Discovery in Engineering Informatics

---

## 📄 Abstract

Computational material discovery has become a knowledge-intensive discipline that is revolutionizing energy storage, electronics, chemical engineering, and engineering informatics applications. Traditional computational approaches are often constrained by high costs and time demands, which limit decision-making and scalability. Advanced engineering informatics methods, specifically in Artificial Intelligence (AI), offer a promising pathway for accelerating material discovery, providing a faster and more scalable solution. However, most AI models rely heavily on structural information, limiting their application to well-characterized materials and often overlooking complex inter-element interactions essential for accurate materials property predictions.

Furthermore, existing methods rely on a single network, which limits their ability to effectively learn complex inter-element interactions and accurately predict the properties of complex compositions. To address these challenges, we introduce Multi Model Material Network (MultiMMNet), a structure-agnostic Deep Learning (DL) fusion framework designed to effectively predict material properties. MultiMMNet consists of two main core modules. The first is the **Dual Encoder Fusion Network (DEFN)**, which learns local and global features through the fusion of CNN and Transformer networks, followed by feature interaction and cross-attention mechanisms. It enables independent learning of complex inter-element interactions and dynamically assigns adaptive importance to each element in the composition. The second is a **Gated Linear Unit with Attention Network (GLUAN)**, designed in a residual fashion to capture nonlinear relationships between elements and provide generalization, effectively capturing both individual element contributions and complex inter-element relationships.

The performance of MultiMMNet is evaluated on benchmark datasets and outperforms existing methods, establishing new state-of-the-art results for structure-agnostic property prediction. Our findings indicate that MultiMMNet holds significant potential for accelerating material discovery and synthesis, providing a scalable, high-performance solution applicable across diverse material domains.

---

## 🔑 Key Highlights

- **Structure-Agnostic Framework**: Predicts material properties using only compositional information—no crystal structures required.
- **Multi-Encoder Design**: Combines CNN and Transformer encoders to capture both local and global elemental interactions.
- **Fractional Encoding Module**: Enriches representations of element fractions, including ultra-low-concentration dopants.
- **GLUA Attention Mechanism**: Enables interpretable and nonlinear feature learning.
- **Interpretability**: Provides attention-based heatmaps and element-wise contribution analysis.
- **Scalable and Modular**: Easily extensible to new property types and data sources.

---

## 🧪 Applications

- **Early-stage materials discovery** in fields such as energy storage, semiconductors, and functional coatings.
- **Property prediction** for materials without known crystal structures.
- **Doped system analysis**, capturing complex inter-element dependencies at trace concentrations.
- **Explainable AI** in materials science, enabling better understanding of learned elemental roles.

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

