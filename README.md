## 👋 Hi there!

I'm a PhD student at [IRIT](https://www.irit.fr/en/home/) working on **certifiable adversarial robustness** in Deep Neural Networks. My research explores how mathematical constraints — especially Lipschitz bounds — can provide **provable safety guarantees** for machine learning models, even under adversarial or noisy inputs.

---

## 🧠 Research Interests

- 🛡️ **Robustness** of neural networks (certified & empirical)
- ✅ **Conformal Prediction** for reliable uncertainty quantification
- 🔐 **Differential Privacy** and efficient private training

---

## 🔧 Notable Contributions

### [💡 lipdp](https://github.com/deel-ai/lipdp) — *Main Contributor*

A TensorFlow library for **fast, differentially private training** using projected gradient descent on the **Stiefel manifold**. It enables DP-SGD with **up to 92% less runtime overhead** compared to standard TF-Privacy.

📄 [Associated Paper](https://arxiv.org/abs/2305.16202)

---

### [🛡️ lip-rcp](https://github.com/deel-ai-papers/lip-rcp) — *Sole Contributor*

A scalable method for **robust Conformal Prediction** that provides **finite-sample safety guarantees** under adversarial perturbations. Outperforms certified smoothing methods in memory and scalability, offering a **1000x memory improvement**.

📄 [Associated Paper](https://arxiv.org/abs/2506.05434)

---

### [⚙️ jaxlip](https://github.com/massena-t/jaxlip) — *Personal Project (work in progress)*

An experimental JAX library enabling **fast training of Lipschitz-bounded networks** using the **Newton–Schulz iterative projection**. Designed for speed, compilation, and easy experimentation with certified models.

---

