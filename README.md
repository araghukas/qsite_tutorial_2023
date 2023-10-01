# Covalent Tutorials - QSITE 2023

Covalent x Pennylane tutorial notebook for QSITE 2023 (at University of Toronto).

### Time Series Anomaly Detection with Quantum Variational Rewinding.

- See the original demo for Pennylane: [Quantum detection of time series anomalies](https://pennylane.ai/qml/demos/tutorial_univariate_qvr).

## Setup

Clone this repository and create the `conda` [environment](https://docs.anaconda.com/free/anaconda/install/index.html) from the `environment.yml` file:

```bash
git clone <this-repo>
cd tutorials_variational_rewinding/quantum_variational_rewinding
conda env create -f environment.yml
conda activate QVR
```

Before dispatching to Covalent, make sure covalent is running

```bash
covalent start
```

Once you're finished, simply run

```bash
covalent stop
```

## 🔗 Links

- ⭐️ [Covalent GitHub](https://github.com/AgnostiqHQ/covalent) ⭐️
- 📺 [Covalent Slack Channel](https://join.slack.com/t/covalentworkflows/shared_invite/zt-22kwbb7k6-x88XLf_alvKP2z11viuVng)

- 📚 [Documentation](https://docs.covalent.xyz/docs/)
- 👩‍🏫 [Tutorials](https://docs.covalent.xyz/docs/user-documentation/tutorials/)

## References

- Baker, Jack S., et al. "Quantum Variational Rewinding for Time Series Anomaly Detection." arXiv preprint [arXiv:2210.16438](https://arxiv.org/abs/2210.16438) (2022).
