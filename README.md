# Coordinated Spatial Reuse Scheduling with Machine Learning in IEEE 802.11 MAPC Networks

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.15622775.svg)](https://doi.org/10.5281/zenodo.15622775)

This is the homepage for the paper "Coordinated Spatial Reuse Scheduling with Machine Learning in IEEE 802.11 MAPC Networks". 

The paper presents results obtained using the following code:

- [upper bound C-SR model](https://github.com/ml4wifi-devs/mapc-optimal) - a theoretical model of C-SR, which finds the best possible transmission schedule using mixed-integer linear programming,
- [DCF and SR simulator](https://github.com/ml4wifi-devs/mapc-dcf) - a discrete event simulator (built using [SimPy](https://simpy.readthedocs.io/en/latest/)), in which devices use either legacy IEEE 802.11 channel access (DCF) or 802.11ax spatial reuse (SR),
- [C-SR simulator](https://github.com/ml4wifi-devs/mapc-sim) - a Monte Carlo simulator of consecutive C-SR transmission opportunities,
- [H-MAB framework](https://github.com/ml4wifi-devs/mapc-mab) - our hierarchical multi-armed bandit framework to determine C-SR scheduling,
- [scripts and scenarios](https://github.com/ml4wifi-devs/mapc-optimal-research) - the main repository comprising installation instructions and a set of simulation scenarios (including [implementations](https://github.com/ml4wifi-devs/mapc-optimal-research/blob/main/mapc_research/envs/scenario_impl.py) and [definitions](https://github.com/ml4wifi-devs/mapc-optimal-research/blob/main/mapc_research/envs/test_scenarios.py)) to validate IEEE 802.11 performance under the various channel access schemes and scripts to run these simulations.

Other relevant links:

- [figures](https://github.com/ml4wifi-devs/csr/tree/main/figures) - figures illustrating the obtained results,
- [raw simulation results](https://zenodo.org/records/15622775) - associated Zenodo repository,
- [openwifi](https://github.com/open-sdr/openwifi) - openwifi repository used in the experimental testbed.

## How to reference this repository?

```
@article{wojnar2025coordinated,
  author={Wojnar, Maksymilian and Ciężobka, Wojciech and Tomaszewski, Artur and Chołda, Piotr and Rusek, Krzysztof and Kosek-Szott, Katarzyna and Haxhibeqiri, Jetmir and Hoebeke, Jeroen and Bellalta, Boris and Zubow, Anatolij and Dressler, Falko and Szott, Szymon},
  title={{Coordinated Spatial Reuse Scheduling With Machine Learning in IEEE 802.11 MAPC Networks}},
  journal={IEEE Journal on Selected Areas in Communications}, 
  year={2025},
}
```
