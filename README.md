# mg5_aMC_tutorial

The repository contains material for the [MadGraph 5 aMC@NLO](https://launchpad.net/mg5amcnlo) (MG5_aMC) tutorial at the [1st Workshop on New Light Physics and Photon-beam Experiments](https://indico.jlab.org/event/413/). Besides the tutorial PDF, it includes:

1. [DarkPhoton_UFO](./DarkPhoton_UFO) is a Universal FeynRules Output model where a dark photon couples to electrons, muons, or taus.

2. [analysis_LHE_output.ipynb](./analysis_LHE_output.ipynb) is a Jupyter notebook that converts \*.lhe files to \*.npy files. It also contains an example of using Python to analyze events for e+ e- → γ A', A' → e+ e- process at the [BaBar](https://en.wikipedia.org/wiki/BaBar_experiment). 

3. [LHEtoPython](./LHEtoPython) is a script used to convert LHE output from MG5_aMC (please give it permission, i.e., run chmod a+x scriptname). 

4. [unweighted_events.lhe.gz](./unweighted_events.lhe.gz) is an MG5_aMC output example for e+ e- → γ A', A' → e+ e- at the BaBar.

For any questions on the model or the notebook, please contact Yiming Zhong (yiming.zhong@cityu.edu.hk).

### Why is it called MadGraph?

Bill Long, while a student at the University of Wisconsin-Madison, developed a program to generate Feynman diagrams on a computer in the 1990s. The author of [HELAS](https://lib-extopc.kek.jp/preprints/PDF/1991/9124/9124011.pdf) saw this program and suggested combining it with HELAS by replacing the diagrams with the corresponding wave functions or vertices from HELAS. This combination led to the creation of the Mad(ison)Graph.

— Source: Tao Han
