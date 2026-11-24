# Decoding (MVPA)

<!--
  CÓMO RELLENAR ESTA PÁGINA
  - Sustituye todo lo que está [ENTRE CORCHETES].
  - Sube las slides en PDF a slides/ y el notebook a code/, con los nombres
    de los enlaces (o cambia los enlaces).
  - En los enlaces de Colab, cambia NOMBRE por tu usuario u organización de GitHub.
  - Si más adelante hay otra sesión de decoding, añade una fila en "Sessions"
    y sube sus archivos con la fecha delante, por ejemplo slides/2027-03_talk.pdf
-->

Decoding is a multivariate pattern analysis consisting of extracting information from the neural data (e.g. EEG decoding uses a model to predict something about a trial, such as which stimulus was shown, from the recorded EEG signal.)


## Sessions

| Date | Session | Format | Presenter | Materials |
|:--|:--|:--|:--|:--|
| 27th November 26 | Introduction to time-resolved decoding | Workshop | Almudena Ramírez Haro | [Slides](slides/decoding_slides.pdf) · [Notebook](https://colab.research.google.com/drive/1KKZ8uMyaxyHcRHa89319xu8AVkMSHBsH?usp=sharing) |

**Useful to know beforehand:** Basic python is recommended but everyone is welcome!

## Code

The workshop notebook runs in Google Colab, so there is nothing to install. Click the badge, then use **File → Save a copy in Drive** to keep your own editable copy.

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1KKZ8uMyaxyHcRHa89319xu8AVkMSHBsH?usp=sharing)

- [Notebook file (.ipynb)](code/decoding_workshop.ipynb)
- Tools: Python, [MNE-Python](https://mne.tools) and scikit-learn
- Data: [where the data comes from, e.g. downloaded inside the notebook from a public dataset]

## Suggested readings

**Start here**

- Carlson, T. A., Grootswagers, T., & Robinson, A. K. (2019). An introduction to time-resolved decoding analysis for M/EEG. *arXiv*. https://arxiv.org/abs/1905.04820

**Go deeper**

- Grootswagers, T., Wardle, S. G., & Carlson, T. A. (2017). Decoding dynamic brain patterns from evoked responses: A tutorial on multivariate pattern analysis applied to time series neuroimaging data. *Journal of Cognitive Neuroscience, 29*(4), 677–697. https://doi.org/10.1162/jocn_a_01068
- King, J.-R., & Dehaene, S. (2014). Characterizing the dynamics of mental representations: The temporal generalization method. *Trends in Cognitive Sciences, 18*(4), 203–210. https://doi.org/10.1016/j.tics.2014.01.002

**Tutorials**

- MNE-Python: [Decoding (MVPA)](https://mne.tools/stable/auto_tutorials/machine-learning/50_decoding.html)

<!-- Enlaza al DOI o a una versión en abierto; no subas los PDF de los artículos. -->

## Notes and questions

[Optional: questions that came up in the sessions, answers, things to try next. Delete this section if you don't need it.]

---

[← All topics](../README.md)
