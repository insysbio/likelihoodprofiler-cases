# LikelihoodProfiler Cases
This repo is dedicated to tests and experimental cases for [LikelihoodProfiler.jl](https://github.com/insysbio/LikelihoodProfiler.jl).


Currently the repository includes the following use-case models:

- [SMB2021: Constrained Optimization Approach to Predictability Analysis in Bio-Mathematical Modeling](https://github.com/insysbio/likelihoodprofiler-cases/blob/master/notebook/SMB2021.ipynb). Slides from the [Contributed talk at SMB2021 Conference](http://schedule.smb2021.org/MFBM/MFBM-CT09.html)
- [STAT5 Dimerization Model](https://github.com/insysbio/likelihoodprofiler-cases/blob/master/notebook/STAT5%20Dimerization.ipynb). One of the Benchmark models in [dMod software package](https://github.com/dkaschek/dMod). Another notebook with the same model includes [Confidence bands estimation (experimental)](https://github.com/insysbio/likelihoodprofiler-cases/blob/master/notebook/STAT5%20Dimerization%20Bands.ipynb)
- [PK Saturation Model](https://github.com/insysbio/likelihoodprofiler-cases/blob/master/notebook/pk_saturation.ipynb). A test model for identifiability analysis
- [TGF-β Signaling Pathway Model](https://github.com/insysbio/likelihoodprofiler-cases/blob/master/notebook/TGFb_pathway.ipynb). The model proposed by [Attila Gábor, Alejandro F. Villaverde, Julio R. Banga. Parameter identifiability analysis and visualization in large-scale kinetic models of biosystems](https://bmcsystbiol.biomedcentral.com/articles/10.1186/s12918-017-0428-y)
- [SIR Model](https://github.com/insysbio/likelihoodprofiler-cases/blob/master/notebook/SIR%20Model.ipynb). A simple model used as an exercise in identifiability analysis. [param-estimation-SIR](https://github.com/marisae/param-estimation-SIR)
- [Cancer Taxol Treatment Model](https://github.com/insysbio/likelihoodprofiler-cases/blob/master/notebook/taxol_treatment.ipynb). The model analyzed in the article [Marisa C.Eisenberg, Harsh V.Jain. A confidence building exercise in data and identifiability](https://www.sciencedirect.com/science/article/pii/S0022519317303454). Another notebook with the same model includes [Confidence bands estimation (experimental)](https://github.com/insysbio/likelihoodprofiler-cases/blob/master/notebook/taxol_treatment_bands.ipynb)

## Intallation and run in Julia

```julia
using IJulia

notebook(dir="./notebook")
```