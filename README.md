# Monte Carlo Analysis and Python-based Simulations

Teaching materials for **Seminar** of *Social Science Simulations* (SVUH.00.300) course, Institute of Social Studies, University of Tartu, autumn 2026.
Lecturer: ACHARYA Kishor, PhD.

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ACHARYAkishor/Monte_carlo_Seminar_UniTartu/blob/main/Monte_Carlo_UniTartu_ACHARYA.ipynb)

## What is here

| File | What it is |
|---|---|
| [`Monte_Carlo_UT_ACHARYA.pdf`](Monte_Carlo_UT_ACHARYA.pdf) | The seminar slides, 52 pages. GitHub shows the PDF in the browser; use the download button for a copy |
| [`Monte_Carlo_UniTartu_ACHARYA.ipynb`](Monte_Carlo_UniTartu_ACHARYA.ipynb) | The companion notebook: every experiment from the slides, with the code, sliders and exercises. Click the badge above to open it in Google Colab; nothing to install |

The interactive version of the same six experiments, with sliders and a short guide under each, is the **Monte Carlo tour** on the course website: <https://acharyakishor.com/simulations/monte-carlo>.

## The seminar in one paragraph

Monte Carlo answers a question by generating many random versions of the situation and counting what happens. The seminar climbs a ladder of six stops, each adding one capability of the method: estimating a probability by counting (two dice); measuring a number with randomness (darts and π); feeding uncertainty into a model and reading a distribution out (a referendum); testing a study design on simulated data (statistical power); running an agent-based model many times to reveal a threshold (Schelling's segregation model); and a look at why the spread of an attitude, not its average, can decide a model's outcome (Granovetter's threshold model), which leads into the next seminar on turning qualitative variables into numbers.

No previous knowledge of Python, probability or statistics is assumed.

## How to use the notebook

1. Click the **Open in Colab** badge. Colab opens a copy in your own Google account; the original here is never changed.
2. Run the first (setup) cell. It loads the tools and shows a test slider; if you see the slider, everything works.
3. Work down the notebook. Each stop has a plain-words explanation, a code cell with line-by-line comments, a **▶ Try it** cell with sliders, a box saying where the Monte Carlo is in that experiment, and an **✎ Exercise** for later.
4. To keep your changes, use *File → Save a copy in Drive* inside Colab.

If you run the notebook locally instead of in Colab and the sliders do not appear, install a recent `ipywidgets` (`pip install -U ipywidgets`) and restart the kernel. Every Try it cell also works without sliders: change the number in its first line and run it again.

## Credit and acknowledgements

If you reuse or adapt my original slides, text, figures or code,
please credit:

ACHARYA Kishor, University of Tartu.

Third-party images and materials belong to their respective creators.
Please follow the credits and licence terms provided for those materials.

## References

- Metropolis, N. (1987). The beginning of the Monte Carlo method. *Los Alamos Science*, 15, 125–130.
- Metropolis, N., & Ulam, S. (1949). The Monte Carlo method. *Journal of the American Statistical Association*, 44(247), 335–341.
- Schelling, T. C. (1971). Dynamic models of segregation. *Journal of Mathematical Sociology*, 1(2), 143–186.
- Granovetter, M. (1978). Threshold models of collective behavior. *American Journal of Sociology*, 83(6), 1420–1443.
- Cohen, J. (1988). *Statistical Power Analysis for the Behavioral Sciences* (2nd ed.). Lawrence Erlbaum.
- Efron, B. (1979). Bootstrap methods: Another look at the jackknife. *The Annals of Statistics*, 7(1), 1–26.
- Verschuuren, G. M. (2017). *100 Excel Simulations*. Holy Macro! Books.
