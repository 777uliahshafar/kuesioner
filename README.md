This template uses [LaTeX](https://www.latex-project.org/) (and [csvsimple](https://ctan.org/pkg/csvsimple)) for producing questionnaires.

# Items
Items are listed in the order they are presented in the publication source. To adapt the items, just change the `CSV`-file and recompile the `*.tex`. The order can be randomised with using, e.g., `shuf` on Linux or [https://www.random.org/lists/](https://www.random.org/lists/). For convenience, the corresponding factor for each item is given in the last column of the `CSV`-file.

# Examples

## GodSpeed scale (semantic differntial scale)

The [GodSpeed scale](http://www.bartneck.de/2008/03/11/the-godspeed-questionnaire-series/) described by Bartneck et al. (2009) is a semantic differntial scale. The `GodSpeed-items.csv` contains the differential pairs.

Example: [PDF](https://gitlab.com/scheunemann/latex-questionnaire/-/jobs/artifacts/master/raw/GodSpeed/GodSpeed.pdf?job=PDFs)

## RoSA scale (Likert-type scale)
The [RoSAS](https://dl.acm.org/citation.cfm?id=3020208) designed by Carpinella et al. (2017) uses a Likert-scale (It is not defined whether it is a 5, 7 or 9-point Likert-scale). The template was designed according to suggestions by the authors.

Example: [PDF](https://gitlab.com/scheunemann/latex-questionnaire/-/jobs/artifacts/master/raw/RoSAS/RoSAS.pdf?job=PDFs)

# References
- Bartneck, C., Kulić, D., Croft, E. and Zoghbi, S., 2009. Measurement Instruments for the Anthropomorphism, Animacy, Likeability, Perceived Intelligence, and Perceived Safety of Robots. _International journal of social robotics, 1_(1), pp.71-81.

- Carpinella, C.M., Wyman, A.B., Perez, M.A. and Stroessner, S.J., 2017, March. The Robotic Social Attributes Scale (RoSAS): Development and Validation. In _Proceedings of the 2017 ACM/IEEE International Conference on human-robot interaction_ (pp. 254-262). ACM.

