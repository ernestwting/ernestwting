# Hi there, I'm Ernest!

**Applied Computational Mathematics & Economics @ Caltech**  
Focusing on educational analytics, psychometrics (Item Response Theory & Rasch Modeling), multi-agent LLMs, and computational mathematics.

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white)
[![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white)](https://en.wikipedia.org/wiki/SQL)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)](https://www.r-project.org/)
[![MATLAB](https://img.shields.io/badge/MATLAB-FF6F00?style=flat&logo=mathworks&logoColor=white)](https://www.mathworks.com/products/matlab.html)
[![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat&logo=latex&logoColor=white)](https://www.latex-project.org/)

---
## Featured Research & Projects

### Dual Machine Learning Model: Student Risk & STACK Question Diagnostics

[![GitHub Repository](https://img.shields.io/badge/GitHub-Repository-181717?style=flat&logo=github&logoColor=white)](https://github.com/ernestwting/moodle-local_stackanalytics.git)

*A two-model machine learning system for the Moodle Analytics API: one model predicts student risk of course non-completion from STACK behavioral indicators, the other diagnoses question and Potential Response Tree (PRT) quality across a course's STACK item bank.*

* **Tech Stack:** `PHP`, `Python`, `TensorFlow`, `php-ml`, `Moodle Analytics API`, `Item Response Theory`
* **Key Features:**
  * **Model 1 (student risk):** binary target for course non-completion, built on indicators including grade trajectory, anomalous response latency, frustration/abandonment (Shannon entropy of attempt gaps), help-seeking behavior, and feedback-responsiveness (edit-distance between consecutive attempts).
  * **Model 2 (question/PRT diagnostics):** IRT-based difficulty and discrimination estimation, PRT tree traversal-coverage analysis to flag bloated or dead branches, and seed-bias detection across randomized question variants.
  * Dual ML backends — logistic regression (PHP) and a feedforward neural network (Python/TensorFlow) — run as an A/B comparison per Moodle's multi-model support.
  * Designed against the Moodle Analytics API's actual constraints (binary-only supervised targets, bounded [-1, 1] indicators), with non-ML diagnostics kept in a separate reporting layer rather than forced into the ML pipeline.

---

### Multi-Agent LLMs for STACK Assessment & Curriculum Generation

[![Math 1b Practical](https://img.shields.io/badge/GitHub-Math%201b%20Practical-181717?style=flat&logo=github&logoColor=white)](https://github.com/ernestwting/Math-1b-Practical)
[![Math 1c Practical](https://img.shields.io/badge/GitHub-Math%201c%20Practical-181717?style=flat&logo=github&logoColor=white)](https://github.com/ernestwting/Math-1c-Practical)

*Developing automated agent workflows to generate validated STACK questions and instructional content for Caltech's Math 1b/1c curriculum.*

* **Tech Stack:** `Python`, `LLMs / Multi-Agent Frameworks`, `Maxima CAS`, `LaTeX`
* **Focus:** Algorithmic question generation, PRT structure generation, and real-time validation against computer algebra backends.

---

### Embedded Moodle/STACK Real-Time Analytics Plugin

[![GitHub Repository](https://img.shields.io/badge/GitHub-Repository-181717?style=flat&logo=github&logoColor=white)](https://github.com/ernestwting/quiz-quizanalytics-plugin.git)

*Extending standalone analytics directly into the Moodle LMS ecosystem as an embedded course-level plugin.*

* **Tech Stack:** `TypeScript`, `PHP`, `Moodle API`, `Python`
* **Focus:** Eliminating export/import steps by rendering real-time item statistics, PRT branch diagnostics, and attempt trajectories inside active course modules.

---

### [Moodle/STACK Interactive Quiz Analytics Hub](https://interactive-analytics-stack-data.streamlit.app/)

[![GitHub Repository](https://img.shields.io/badge/GitHub-Repository-181717?style=flat&logo=github&logoColor=white)](https://github.com/ernestwting/Interactive-quiz-analytics/tree/main)

*An interactive web app built to extract actionable teaching insights from raw Moodle/STACK math assessment exports.*

* **Tech Stack:** `Python`, `Streamlit`, `Plotly`, `Pandas`, `SciPy`, `ReportLab`
* **Key Features:**
  * Extracts facility ($F_i$) and discrimination ($D_i$) difficulty indices across student best vs. all-attempt cohorts.
  * Visualizes Potential Response Tree (PRT) failure modes via interactive heatmaps and student-by-question performance matrices.
  * Runs client-side with pseudonymized data processing to preserve student privacy.
  * Generates single-click, full-length PDF reports complete with dynamic analytical commentary and vector charts.

---

### Bioinformatics & Gene Correlation Analysis

* **Focus:** Computational Analysis & Human Genomics
* Conducted computational analysis on the human genome to analyze gene set correlations and extract statistical patterns from large-scale biological datasets.

---

### Combinatorics & Extremal Graph Theory

* **Focus:** Ramsey's Theorem & Schur's Theorem
* Conducted combinatorial research as a Research Assistant at South Dakota State University, investigating monochromatic subgraphs, colorings, and partition regularity within Ramsey theory.

---

## Conference Presentations

* **Poster Presentation:** *"Turning STACK Response Data into Insight"* – International STACK Conference, Nairobi, Kenya (July 2026)
* **Slideshow Presentation:** *"Moodle/STACK Interactive Quiz Analytics"* – International STACK Conference, Nairobi, Kenya (July 2026)
* **Academic Presentation:** *"The Big Lie: Distilling the Truth from Power"* – BHS Literary Conference (April 2025)

---

## Tech Stack & Tools

* **Languages:**  
[![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white)
[![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white)](https://en.wikipedia.org/wiki/SQL)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)](https://www.r-project.org/)
[![MATLAB](https://img.shields.io/badge/MATLAB-FF6F00?style=flat&logo=mathworks&logoColor=white)](https://www.mathworks.com/products/matlab.html)
[![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat&logo=latex&logoColor=white)](https://www.latex-project.org/)

* **Data Science & Visualization:**  
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)](https://numpy.org/)
[![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat&logo=scipy&logoColor=white)](https://scipy.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat)](https://seaborn.pydata.org/)
[![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat&logo=plotly&logoColor=white)](https://plotly.com/)

* **Machine Learning & Psychometrics:**  
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)](https://scikit-learn.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)](https://www.tensorflow.org/)
[![Item Response Theory](https://img.shields.io/badge/Item%20Response%20Theory-6A1B9A?style=flat)](https://en.wikipedia.org/wiki/Item_response_theory)
[![Rasch Modeling](https://img.shields.io/badge/Rasch%20Modeling-00897B?style=flat)](https://en.wikipedia.org/wiki/Rasch_model)

* **Web, APIs & Cloud:**  
[![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)](https://streamlit.io/)
[![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![Moodle API](https://img.shields.io/badge/Moodle%20API-F98012?style=flat&logo=moodle&logoColor=white)](https://moodledev.io/)
[![LTI 1.3](https://img.shields.io/badge/LTI%201.3-005A9C?style=flat)](https://www.imsglobal.org/activity/learning-tools-interoperability)
[![Firebase](https://img.shields.io/badge/Firebase-DD2C00?style=flat&logo=firebase&logoColor=white)](https://firebase.google.com/)
[![discord.py](https://img.shields.io/badge/discord.py-5865F2?style=flat&logo=discord&logoColor=white)](https://discordpy.readthedocs.io/)

* **Automation & Reporting:**  
[![ReportLab](https://img.shields.io/badge/ReportLab-CC0000?style=flat)](https://www.reportlab.com/)
[![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat&logo=playwright&logoColor=white)](https://playwright.dev/)
[![Chromium](https://img.shields.io/badge/Chromium-4285F4?style=flat&logo=googlechrome&logoColor=white)](https://www.chromium.org/)
[![Kaleido](https://img.shields.io/badge/Kaleido-5E35B1?style=flat)](https://github.com/plotly/Kaleido)
[![OpenPyXL](https://img.shields.io/badge/OpenPyXL-217346?style=flat)](https://openpyxl.readthedocs.io/)

* **Computational Math & Tools:**  
[![Maxima CAS](https://img.shields.io/badge/Maxima%20CAS-5C6BC0?style=flat)](https://maxima.sourceforge.io/)
[![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)](https://git-scm.com/)
[![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)](https://www.kernel.org/)
[![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white)](https://www.gnu.org/software/bash/)

---

## Connect with Me

* **Live App:** [interactive-analytics-stack-data.streamlit.app](https://interactive-analytics-stack-data.streamlit.app/)
* **Institution:** California Institute of Technology (Pasadena, CA)
* [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ernestwting/)
[![Outlook](https://img.shields.io/badge/Outlook-eting%40caltech.edu-0078D4?style=flat&logo=microsoftoutlook&logoColor=white)](mailto:eting@caltech.edu)
