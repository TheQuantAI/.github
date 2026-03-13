<h1 align="center">TheQuantAI</h1>

<p align="center">
  <strong>Making quantum computing accessible to every developer.</strong><br>
  Write once, run anywhere — on simulators today, quantum hardware tomorrow.
</p>

<p align="center">
  <a href="https://thequantai.in">🌐 Website</a> •
  <a href="https://thequantcloud.com">☁️ TheQuantCloud</a> •
  <a href="https://docs.thequantcloud.com">📖 Docs</a> •
  <a href="https://thequantdefense.com">🛡️ TheQuantDefense</a>
</p>

<p align="center">
  <a href="https://github.com/TheQuantAI/quantsdk"><img src="https://img.shields.io/github/stars/TheQuantAI/quantsdk?style=social" alt="GitHub Stars"></a>
  <a href="https://pypi.org/project/quantsdk/"><img src="https://img.shields.io/pypi/v/quantsdk?color=blue&label=PyPI" alt="PyPI Version"></a>
  <a href="https://github.com/TheQuantAI/quantsdk/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-Apache_2.0-green.svg" alt="License"></a>
</p>

---

## 🚀 Our Mission

**TheQuantAI** is building the cloud platform that makes quantum computing practical. We believe quantum advantage shouldn't require a PhD in physics — just `pip install quantsdk`.

We're a Bengaluru-based deep-tech startup operating two verticals:

| Vertical | Description | Status |
|----------|-------------|--------|
| ☁️ **[TheQuantCloud](https://thequantcloud.com)** | Quantum Computing as a Service — SDK, web IDE, multi-backend orchestration, smart routing | 🟢 Active |
| 🛡️ **[TheQuantDefense](https://thequantdefense.com)** | Quantum-safe cryptography & optimization for defense & aerospace | 🔜 Coming Soon |

---

## 📦 Open-Source Projects

### QuantSDK — *Write quantum code once, run anywhere*

```bash
pip install quantsdk
```

```python
import quantsdk as qs

circuit = qs.Circuit(2)
circuit.h(0).cx(0, 1).measure_all()
result = qs.run(circuit, shots=1000)
print(result.counts)  # {'00': 498, '11': 502}
```

**Features**: 50+ gates · QuantRouter smart routing · Qiskit/OpenQASM interop · Local + IBM + Aer backends · Cloud client · Circuit visualization · 330 tests · Full MkDocs documentation · 22 example notebooks

👉 **[Get started →](https://github.com/TheQuantAI/quantsdk)**

---

## 🗺️ Roadmap

| Quarter | Milestone |
|---------|-----------|
| **Q1 2026** | QuantSDK v0.1 open-source launch, QuantRouter v0.1 (rule-based) |
| **Q2 2026** | QuantStudio (web IDE) beta, IonQ + Rigetti adapters, PyPI release |
| **Q3 2026** | TheQuantCloud beta, QuantRouter v0.3 (ML-powered) |
| **Q4 2026** | GA launch, billing, enterprise tier |

---

## 🏗️ Repository Map

| Repository | Description | Status |
|------------|-------------|--------|
| [`quantsdk`](https://github.com/TheQuantAI/quantsdk) | Core quantum SDK — circuits, gates, runners, backends, QuantRouter | ✅ v0.1.0 |
| [`thequantai.in`](https://github.com/TheQuantAI/thequantai.in) | TheQuantAI corporate website | ✅ Live |
| [`thequantcloud.com`](https://github.com/TheQuantAI/thequantcloud.com) | TheQuantCloud product website | ✅ Live |
| [`thequantdefense.com`](https://github.com/TheQuantAI/thequantdefense.com) | TheQuantDefense coming-soon page | ✅ Live |
| [`.github`](https://github.com/TheQuantAI/.github) | Org profile & community health files | ✅ Live |

---

## 🤝 Contributing

We welcome contributions! Every repo has a `CONTRIBUTING.md` with guidelines. Start by:

1. ⭐ Starring [quantsdk](https://github.com/TheQuantAI/quantsdk)
2. 🐛 Filing [issues](https://github.com/TheQuantAI/quantsdk/issues)
3. 🔀 Submitting [pull requests](https://github.com/TheQuantAI/quantsdk/pulls)

---

## 👥 Team

| | Role | GitHub |
|---|---|---|
| **Saket** | Founder, CEO & CTO | [@Saket-TheQuantAI](https://github.com/Saket-TheQuantAI) |

---

## 📬 Contact

| | |
|---|---|
| **General** | [team@thequantai.in](mailto:team@thequantai.in) |
| **Security** | [security@thequantai.in](mailto:security@thequantai.in) |
| **Founder** | [saket@thequantai.in](mailto:saket@thequantai.in) |

---

<p align="center">
  <sub>Built with ❤️ in Bengaluru, India 🇮🇳</sub>
</p>
