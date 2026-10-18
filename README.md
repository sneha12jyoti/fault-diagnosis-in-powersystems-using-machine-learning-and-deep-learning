## 🔍 About the Project
Power transmission and distribution networks are prone to various types of faults due to environmental factors, equipment failures, or system overloads. Quick and accurate fault diagnosis is essential for protecting power system assets and ensuring an uninterrupted power supply. 

Under the guidance of mentors at **NIT Jamshedpur**, this repository implements feature extraction, signal processing, and deep learning models (such as CNNs, LSTMs, and hybrid architectures) to automatically identify fault types (e.g., Single Line-to-Ground, Line-to-Line, Three-Phase faults) from electrical waveform data.

---

## ✨ Key Features
* **Automated Fault Detection:** Quickly identifies abnormal operating conditions in power grids.
* **Fault Classification:** Distinguishes between symmetrical and asymmetrical fault types.
* **Signal Processing:** Integrates preprocessing techniques such as Wavelet Transform or Fast Fourier Transform (FFT) for feature extraction from raw voltage and current signals.
* **Modular Pipeline:** Well-structured codebase separating data preprocessing, model training, evaluation, and inference.

---

## 📊 Dataset
* **Source:** Generated using power system simulation tools (such as MATLAB/Simulink IEEE standard bus systems) or standard benchmark datasets.
* **Features Included:** 
  * Three-phase currents ($I_a, I_b, I_c$)
  * Three-phase voltages ($V_a, V_b, V_c$)
  * Target labels indicating fault types and phases involved.
