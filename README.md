<p align="center">
  <img src="https://img.shields.io/badge/quantum-simulator-blueviolet?style=for-the-badge" alt="Quantum Simulator"/>
  <img src="https://img.shields.io/badge/python-3.8+-blue?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/streamlit-app-ff4b4b?style=for-the-badge&logo=streamlit&logoColor=white" alt="Streamlit"/>
  <img src="https://img.shields.io/badge/license-MIT-green?style=for-the-badge" alt="MIT License"/>
</p>

<h1 align="center">Mini Quantum Lab</h1>

<p align="center">
  Quantum computing simulation right in your browser.<br>
  Play with qubits, apply gates, see results in real-time.<br>
  <b>No quantum hardware needed. No complicated setup.</b>
</p>

<p align="center">
  <a href="https://github.com/rasidi3112/quantum-computing-simulation/stargazers">Star this repo if you find it useful!</a>
</p>

---

## What Is This?

Quantum computing is complex. This project lets you **experiment hands-on** without needing to understand all the theory first.

Open browser → pick qubits → apply gates → see probabilities. That simple.

---

## Features

| Feature | Detail |
|---------|--------|
| **Quantum Gates** | Hadamard, Pauli (X/Y/Z), S, T, CNOT |
| **Real-time Simulation** | State vector & probability updates live |
| **Measurement** | 100–10,000 shots, distribution histogram |
| **Matrix Viewer** | Inspect unitary matrix (real & imaginary) |
| **Circuit History** | Logs every gate applied |
| **15 Languages** | 🇬🇧🇮🇩🇪🇸🇨🇳🇸🇦🇫🇷🇯🇵🇰🇷🇩🇪🇧🇷🇷🇺🇮🇳🇹🇷🇮🇹🇻🇳 |

---

## Preview

<p align="center">
  <img src="assets/quantum_state_vector.png" alt="State Vector" width="45%"/>
  &nbsp;&nbsp;
  <img src="assets/quantum_measurement.png" alt="Measurement" width="45%"/>
</p>

---

## Quick Start

```bash
git clone https://github.com/rasidi3112/quantum-computing-simulation.git
cd quantum-computing-simulation
pip install -r requirements.txt
streamlit run main.py
```

Open **http://localhost:8501** — done.

---

## Structure

```
├── main.py              # Main app
├── translations.py      # Multi-language support
├── requirements.txt     # Dependencies
├── assets/              # Screenshots
└── LICENSE
```

---

## Tech Stack

**Python** · **Streamlit** · **NumPy** · **Matplotlib**

---

## Roadmap

- [ ] Drag & drop circuit composer
- [ ] Bloch sphere 3D visualization
- [ ] Cloud quantum backend integration
- [ ] Export circuit to Qiskit/OpenQASM
- [ ] Dark mode

---

## Contributing

Contributions welcome! Fork, create a branch, submit a PR.

```bash
git checkout -b new-feature
# code...
git commit -m "add new feature"
git push origin new-feature
```

Open a Pull Request and describe your changes.

---

## License

MIT — free to use, modify, and distribute.

---

<p align="center">
  Built by <a href="https://github.com/rasidi3112"><b>Rasidi</b></a> 🇮🇩
</p>
