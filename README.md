# COmplexVID-19

Source code for the paper:

"Social interaction layers in complex networks for the dynamical epidemic modeling of COVID-19 in Brazil."
Physica A: Statistical Mechanics and its Applications 564 (2021): 125498.
Leonardo F. S. Scabini, Lucas C. Ribas, Mariane B. Neiva, Altamir G. B. Junior, Alex J. F. Farfán, Odemir M. Bruno

contact: scabini@ifsc.usp.br

<p align="center">
    <img src="example.png" height="640px">
</p>

## Usage

The main script to perform an experiment is "run.py"
   * Runs the dynamic network in parallel, where each thread is a different iteration (with a different random seed). The final results are the average between iterations. On this code we set 10 iterations; on the paper, 100 iterations where performed for better statistical results.
   * The script has several parameters that should be manually adjusted according to the society one wants to model. The comments (in portuguese) should guide you.


Libraries used:
See requirements file. 

Python version used:
3.10.8

## Cite

If you use this method, please cite our paper:

Scabini, L. F., Ribas, L. C., Neiva, M. B., Junior, A. G., Farfán, A. J., & Bruno, O. M. (2021). Social interaction layers in complex networks for the dynamical epidemic modeling of COVID-19 in Brazil. Physica A: Statistical Mechanics and its Applications, 564, 125498.

```
@article{scabini2021social,
  title={Social interaction layers in complex networks for the dynamical epidemic modeling of COVID-19 in Brazil},
  author={Scabini, Leonardo FS and Ribas, Lucas C and Neiva, Mariane B and Junior, Altamir GB and Farf{\'a}n, Alex JF and Bruno, Odemir M},
  journal={Physica A: Statistical Mechanics and its Applications},
  volume={564},
  pages={125498},
  year={2021},
  publisher={Elsevier}
}
```
