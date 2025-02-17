**Project: RandLA-Net TensorFlow Setup & Inference Pipeline**

**Objective:**
To set up the TensorFlow implementation of RandLA-Net in a streamlined manner that allows inference on **Semantic3D, SemanticKITTI, and later WHU-Rail3D** datasets with minimal code changes. Unnecessary components, particularly those related to **S3DIS (indoor datasets)**, will be removed.

**Scope of Work:**
The project will be executed in **phases**, each with specific goals. The primary expectation is to reach **Phase 3**

---

### **Phases & Deliverables**

#### **Phase 0: Initial Setup & Code Cleanup**

- Install and configure TensorFlow and all necessary dependencies for RandLA-Net.
- Remove all unnecessary code and references related to **S3DIS**.
- Ensure a clean, functional base for running inference.

#### **Phase 1: Semantic3D Inference**

- Adapt the existing code to process **Semantic3D** dataset.
- Generate inference results and verify correctness.

#### **Phase 2: SemanticKITTI Inference**

- Modify the pipeline to support **SemanticKITTI** dataset.
- Run inference and compare outputs with expected results.

#### **Phase 3: WHU-Rail3D Inference & Results Presentation**

- Integrate support for **WHU-Rail3D** dataset.
- Run inference and format results in a meaningful way.

#### **Phase 4: API Endpoint Integration (Assistance Needed, Not Full Responsibility)**

- Help package the inference pipeline so it can be used as an **API endpoint**.
- The goal is to make results easily accessible but not require full backend/API development.

#### **Phase 5: Training on New Data (Optional, Future Work)**

- If the project extends beyond inference, future datasets will be used to fine-tune RandLA-Net.
- I will handle the **MLOps pipeline** to ensure smooth updates and error-free integration of new data.

---
### **Next Steps**

- Let's begin with **Phase 0**: Setup and cleanup.
- Feel free to suggest optimizations or improvements along the way.

---
###**Resources**

- [Download Model Checkpoints](https://drive.google.com/drive/folders/1iU8yviO3TP87-IexBXsu13g6NklwEkXB)
- [Semantic KITTI Dataset](https://semantic-kitti.org/dataset.html#download)
- [Semantic 3D Dataset] - Defined in README.md of RandLA-Net (Tensorflow Version)
- [WHU Rail3D Dataset](https://drive.google.com/drive/folders/1VRVSdApQ_As_A9OqHY7PP5HBKlDw9kcH)

---
**Thank you for your support and collaboration!**



