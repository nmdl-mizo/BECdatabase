This repository contains the Born effective charge (BEC) database used in our published papers.

## Database description

- **BaTiO3_PBEsol_database_all.xyz**  
  Complete BaTiO3 BEC database used in Citation [1].

- **BaTiO3_PBEsol_database_solid.xyz**  
  Subset of `BaTiO3_PBEsol_database_all.xyz` containing only solid-phase structures, used in Citation [2].

- **ScAlN_PBE_database.xyz**  
  ScAlN BEC database used in Citation [3] and Citation [4].

- **BaTiO3_LDA_database.xyz**  
  BaTiO3 BEC database used in Citation [5].


## Citation

If you use this database in your research, please cite the corresponding publication.

### Citation [1]
```
@article{chen2026bec_database,
      title={Effect of uniaxial compressive stress on polarization switching and domain wall formation in tetragonal phase BaTiO3 via machine learning potential}, 
      author={Po-Yen Chen and Teruyasu Mizoguchi},
      journal = {Materials & Design},
      volume  = {265},
      pages   = {115851},
      year={2026},
      doi = {10.1016/j.matdes.2026.115851},
      url={https://doi.org/10.1016/j.matdes.2026.115851}
      }
```
### Citation [2]
```
@misc{chen2026bec_database_solid,
      title={Transition from Homogeneous to Domain-Wall-Mediated Polarization Switching in BaTiO3: A Machine-Learning Molecular Dynamics Study}, 
      author={Po-Yen Chen and Teruyasu Mizoguchi},
      year={2026},
      eprint={2605.25485},
      archivePrefix={arXiv},
      primaryClass={cond-mat.mtrl-sci},
      url={https://arxiv.org/abs/2605.25485}
      }
```

### Citation [3]
```
@misc{sahashi2026originreducedcoercivefield,
      title={Origin of Reduced Coercive Field in ScAlN: Synergy of Structural Softening and Dynamic Atomic Correlations},
      author={Ryotaro Sahashi and Po-Yen Chen and Teruyasu Mizoguchi},
      year={2026},
      eprint={2603.18710},
      archivePrefix={arXiv},
      primaryClass={cond-mat.mtrl-sci},
      url={https://arxiv.org/abs/2603.18710},
      }
```

### Citation [4]
```
@article{10.1063/5.0336903,
    author = {Sahashi, Ryotaro and Chen, Po-Yen and Mizoguchi, Teruyasu},
    title = {Decoupling structural and bonding effects on ferroelectric switching in ScAlN via molecular dynamics under an applied electric field},
    journal = {APL Materials},
    volume = {14},
    number = {6},
    pages = {061104},
    year = {2026},
    month = {06},
    abstract = {ScxAl1−xN has emerged as a promising wurtzite-type ferroelectric material, where increasing the Sc concentration reduces both the coercive field (Ec) and remanent polarization (Pr). This concentration-dependent behavior is physically attributed to two simultaneous changes: the increase in the internal structural parameter u (structural effect) and the reduction in the overall average bond strength due to an increased proportion of weaker Sc–N bonds (bonding effect). Because these factors are strongly coupled in experiments, their individual contributions to ferroelectric switching remain unclear. In this study, we systematically decoupled these effects using machine-learning force field-based molecular dynamics (MD) simulations under an applied electric field. By artificially tuning u via in-plane strain at a fixed concentration, we demonstrated that Pr is determined exclusively by the structural effect, exhibiting a universal linear dependence regardless of the concentration. In contrast, Ec deviated from this structural trend, implying an additional compositional contribution. To isolate this, we evaluated configurations with identical u but varying Sc concentrations; Pr remained constant, whereas Ec systematically decreased due to bond weakening. Furthermore, static nudged elastic band calculations revealed that the static switching barrier depends solely on u, failing to explicitly capture the bonding effect on Ec. These results establish that while Pr is governed strictly by the structural effect, Ec is determined by a superposition of structural and bonding effects. Our findings highlight the necessity of dynamic MD simulations for fully understanding ferroelectric switching in compositionally tunable materials.},
    issn = {2166-532X},
    doi = {10.1063/5.0336903},
    url = {https://doi.org/10.1063/5.0336903},
    eprint = {https://pubs.aip.org/aip/apm/article-pdf/doi/10.1063/5.0336903/21028465/061104_1_5.0336903.pdf},
      }
```

### Citation [5]
```
@article{Ryotaro Sahashi202625164,
  title={LDA-based machine learning force field for accurate electric-field-driven ferroelectric response in BaTiO<sub>3</sub>},
  author={Ryotaro Sahashi and Po-Yen Chen and Teruyasu Mizoguchi},
  journal={Journal of the Ceramic Society of Japan},
  volume={134},
  number={7},
  pages={431-438},
  year={2026},
  doi={10.2109/jcersj2.25164}
      }
```
