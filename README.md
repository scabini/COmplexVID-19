# COmplexVID-19

Source code for the paper:

Social Interaction Layers in Complex Networks for the Dynamical Epidemic Modeling of COVID-19 in Brazil

Leonardo F. S. Scabini, Lucas C. Ribas, Mariane B. Neiva, Altamir G. B. Junior, Alex J. F. Farfán, Odemir M. Bruno


O script principal para realizar um experimento é o "run.py".
Roda em paralelo usando o número de cores - 2, cada thread é uma iteração, resultados finais são a média das iterações.
Aqui está fixo em 10 iterações, no artigo usamos 100 (ideal, melhores estatísticas porém custoso).

O script tem vários parâmetros que devem ser ajustados manualmente dentro do "run.py", os comentários devem guiá-lo.
Qualquer dúvida entre em contato com: Leonardo Scabini, scabini@ifsc.usp.br

Dependências:
networkx 2.4, matplotlib, pickle




SCABINI, Leonardo FS et al. Social Interaction Layers in Complex Networks for the Dynamical Epidemic Modeling of COVID-19 in Brazil. arXiv preprint arXiv:2005.08125, 2020.
