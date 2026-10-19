# Monte Carlo Analysis and Python-based Simulations

Teaching materials for **Seminar 6** of *Social Science Simulations* (SVUH.00.300), Institute of Social Studies, University of Tartu, autumn 2026.
Lecturer: Kishor Acharya.

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ACHARYAkishor/Monte_carlo_Seminar_UniTartu/blob/main/Monte_Carlo_UniTartu_ACHARYA.ipynb)

## What is here

| File | What it is |
|---|---|
| `Monte_Carlo_UT_ACHARYA.pdf` | The seminar slides (view in the browser) |
| `Monte_Carlo_UT_ACHARYA.pptx` | The same slides as PowerPoint, with speaker notes |
| `Monte_Carlo_UniTartu_ACHARYA.ipynb` | The companion notebook: every experiment from the slides, with code, sliders and exercises. Click the badge above to open it in Google Colab; nothing to install |

The interactive animations that go with the seminar are on the course page: <https://acharyakishor.com/simulations>.

## The seminar in one paragraph

Monte Carlo answers a question by generating many random versions of the situation and counting what happens. The seminar climbs a ladder of six stops, each adding one capability of the method: estimating a probability by counting (two dice); measuring a number with randomness (darts and π); feeding uncertainty into a model and reading a distribution out (a referendum); testing a study design on simulated data (statistical power); running an agent-based model many times to reveal a threshold (Schelling's segregation model); and a one-page look at bootstrapping, sensitivity analysis and Markov chain Monte Carlo.

No previous knowledge of Python, probability or statistics is assumed.

## How to use the notebook

1. Click the **Open in Colab** badge. Colab opens a copy in your own account; the original here is never changed.
2. Run the first (setup) cell, then work down. Each stop has an explanation, a code cell, a **▶ Try it** cell with sliders, a boxed summary and an exercise.
3. To keep your changes, use *File → Save a copy in Drive* inside Colab.

## Licence

Text, slides and figures: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Code: MIT. Please credit *Kishor Acharya, University of Tartu* when reusing.

## References

Metropolis, N. (1987). The beginning of the Monte Carlo method. *Los Alamos Science*, 15, 125–130.
Metropolis, N., & Ulam, S. (1949). The Monte Carlo method. *JASA*, 44(247), 335–341.
Schelling, T. C. (1971). Dynamic models of segregation. *Journal of Mathematical Sociology*, 1(2), 143–186.
Granovetter, M. (1978). Threshold models of collective behavior. *American Journal of Sociology*, 83(6), 1420–1443.
Efron, B. (1979). Bootstrap methods: Another look at the jackknife. *The Annals of Statistics*, 7(1), 1–26.
Cohen, J. (1988). *Statistical Power Analysis for the Behavioral Sciences* (2nd ed.). Lawrence Erlbaum.
Verschuuren, G. M. (2017). *100 Excel Simulations*. Holy Macro! Books.
