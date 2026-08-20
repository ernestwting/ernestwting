<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,50:16213e,100:0f3460&height=220&section=header&text=Ernest%20Ting&fontSize=62&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Applied%20Computational%20Mathematics%20and%20Economics%20@%20Caltech&descAlignY=58&descSize=18&descColor=c9c9d9" width="100%"/>

<a href="https://github.com/ernestwting">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=500&size=20&duration=3000&pause=900&color=9AA3C9&center=true&vCenter=true&width=640&lines=Educational+Analytics+%26+Psychometrics;Item+Response+Theory+%7C+Rasch+Modeling;Multi-Agent+LLMs+for+Curriculum+Generation;Computational+Mathematics+%26+Statistics" alt="Typing SVG" />
</a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ernestwting/)
[![Outlook](https://img.shields.io/badge/Email-eting%40caltech.edu-0078D4?style=flat-square&logo=microsoftoutlook&logoColor=white)](mailto:eting@caltech.edu)
[![Streamlit](https://img.shields.io/badge/Live_App-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)](https://interactive-analytics-stack-data.streamlit.app/)
[![Moodle Marketplace](https://img.shields.io/badge/Live_Plugin-Moodle_Marketplace-F98012?style=flat-square&logo=moodle&logoColor=white)](https://marketplace.moodle.com/plugins/3995/versions#plugin-tab-content)
![Profile Views](https://komarev.com/ghpvc/?username=ernestwting&style=flat-square&color=6272a4&label=PROFILE+VIEWS)

</div>

<br/>

## About Me

- Studying **Applied Computational Mathematics & Economics** at **Caltech**
- Building tools at the intersection of **psychometrics** (IRT, Rasch modeling), **educational analytics**, and **multi-agent LLM systems**
- Currently deep in the **Moodle / STACK (Maxima CAS)** ecosystem — analytics plugins, ML diagnostics, and agentic question generation
- Presented at the **International STACK Conference**, Nairobi, Kenya (July 2026)
- Always tinkering with something new in psychometric modeling or agent workflows
- Reach me at **eting@caltech.edu**

---

## GitHub Stats

<div align="center">

[![GitHub followers](https://img.shields.io/github/followers/ernestwting?style=flat-square&logo=github&label=Followers&color=6272a4)](https://github.com/ernestwting?tab=followers)
[![Public repos](https://img.shields.io/badge/dynamic/json?style=flat-square&logo=github&color=6272a4&label=Public%20Repos&query=%24.public_repos&url=https%3A%2F%2Fapi.github.com%2Fusers%2Fernestwting)](https://github.com/ernestwting?tab=repositories)

<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=ernestwting&theme=tokyo-night&hide_border=true&bg_color=transparent&color=9AA3C9&line=8be9fd&point=c9c17a" width="95%"/>

</div>

<sub>Note: the language breakdown and trophy widgets were pulled — both are hosted on free, shared community services that frequently hit GitHub's API rate limit and throw "error fetching resource." Your languages are already covered in the Tech Stack section below. If the activity graph above also breaks at some point, it's the same underlying issue and can safely be removed too.</sub>

---

## Featured Research & Projects

<sub>Click a project to expand it.</sub>

<br/>

<details>
<summary><b>STACK q-type Analytics for Moodle</b> — unifying Quiz, Question, Model & Diagnostics analytics for STACK quizzes into one Moodle plugin</summary>
<br/>

<p>
<a href="https://github.com/ernestwting/moodle-local_stackquizanalytics.git"><img src="https://img.shields.io/badge/My_Moodle_Plugin-GitHub-181717?style=flat-square&logo=github&logoColor=white"/></a>
<a href="https://marketplace.moodle.com/plugins/3995/versions#plugin-tab-content"><img src="https://img.shields.io/badge/Live_Plugin-Moodle_Marketplace-F98012?style=flat-square&logo=moodle&logoColor=white"/></a>
<img src="https://img.shields.io/github/last-commit/ernestwting/moodle-local_stackquizanalytics?style=flat-square&color=4c9aff&label=last%20commit"/>
<img src="https://img.shields.io/badge/status-alpha-orange?style=flat-square"/>
<img src="https://img.shields.io/badge/type-Moodle%20Plugin-6272a4?style=flat-square"/>
</p>

A single, self-contained Moodle plugin unifying four sections of analytics for STACK (Maxima CAS) quizzes — behind one **"Analytics"** entry point with a section switcher, merging what were previously two separate plugins a teacher had to install and use independently.

<table width="100%">
<tr>
<td width="26%" valign="top">

**Stack**

<img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white"/><br/>
<img src="https://img.shields.io/badge/Moodle%20API-F98012?style=flat-square&logo=moodle&logoColor=white"/><br/>
<img src="https://img.shields.io/badge/Analytics%20API-D2691E?style=flat-square"/><br/>
<img src="https://img.shields.io/badge/Plotly.js-3F4F75?style=flat-square&logo=plotly&logoColor=white"/><br/>
<img src="https://img.shields.io/badge/KaTeX-008080?style=flat-square"/><br/>
<img src="https://img.shields.io/badge/TCPDF-C0392B?style=flat-square"/>

</td>
<td width="74%" valign="top">

**Highlights**
- **Quiz / Question Analytics** — attempts-vs-grades scatter, per-question error drill-down, PRT transition graphs with 3D distance charts
- **Model Analytics** — 2 Analytics API targets: a 5-indicator student-risk model and a 4-indicator question/PRT review model
- **Diagnostics** — seed-bias ANOVA + PRT branch-coverage, computed directly and kept outside the ML pipeline
- **Zero external services** — every computation runs in-process in plain PHP; one-click landscape PDF export on every view

</td>
</tr>
</table>

</details>

<details>
<summary><b>Dual Machine Learning Model: Student Risk & STACK Question Diagnostics</b> — two Analytics API models for student non-completion risk and STACK question/PRT diagnostics</summary>
<br/>

<p>
<a href="https://github.com/ernestwting/moodle-local_stackanalytics.git"><img src="https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github&logoColor=white"/></a>
<img src="https://img.shields.io/github/last-commit/ernestwting/moodle-local_stackanalytics?style=flat-square&color=4c9aff&label=last%20commit"/>
<img src="https://img.shields.io/badge/type-ML%20System-9d4edd?style=flat-square"/>
</p>

A two-model machine learning system for the Moodle Analytics API: one model predicts a student's risk of course non-completion, the other diagnoses question and Potential Response Tree (PRT) quality across a course's STACK item bank.

<table width="100%">
<tr>
<td width="26%" valign="top">

**Stack**

<img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white"/><br/>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/><br/>
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white"/><br/>
<img src="https://img.shields.io/badge/php--ml-787CB5?style=flat-square&logo=php&logoColor=white"/><br/>
<img src="https://img.shields.io/badge/Analytics%20API-D2691E?style=flat-square"/><br/>
<img src="https://img.shields.io/badge/IRT-6A1B9A?style=flat-square"/>

</td>
<td width="74%" valign="top">

**Highlights**
- **Model 1 — Student Risk:** grade trajectory, response-latency anomaly, disengagement entropy, help-seeking gap, feedback-revision distance
- **Model 2 — Question/PRT Diagnostics:** IRT-based difficulty & discrimination, PRT traversal-coverage, seed-bias detection
- **Dual ML backends** — logistic regression (PHP) vs. a feedforward neural net (Python/TensorFlow), run as an A/B comparison
- Built against the Analytics API's real constraints — binary-only targets, bounded [-1, 1] indicators

</td>
</tr>
</table>

</details>

<details>
<summary><b>Multi-Agent LLMs for STACK Assessment & Curriculum Generation</b> — agent workflows generating validated STACK questions & curriculum content for Math 1b/1c</summary>
<br/>

<p>
<a href="https://github.com/ernestwting/Math-1b-Practical"><img src="https://img.shields.io/badge/GitHub-Math_1b_Practical-181717?style=flat-square&logo=github&logoColor=white"/></a>
<a href="https://github.com/ernestwting/Math-1c-Practical"><img src="https://img.shields.io/badge/GitHub-Math_1c_Practical-181717?style=flat-square&logo=github&logoColor=white"/></a>
<img src="https://img.shields.io/badge/type-Agentic%20Workflow-2a9d8f?style=flat-square"/>
</p>

Automated agent workflows that generate validated STACK questions and instructional content for Caltech's Math 1b/1c curriculum.

<table width="100%">
<tr>
<td width="26%" valign="top">

**Stack**

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/><br/>
<img src="https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white"/><br/>
<img src="https://img.shields.io/badge/Multi--Agent%20LLMs-16A085?style=flat-square"/><br/>
<img src="https://img.shields.io/badge/Maxima%20CAS-5C6BC0?style=flat-square"/>

</td>
<td width="74%" valign="top">

**Highlights**
- Algorithmic **question generation** and PRT structure generation, agent-driven end to end
- **Real-time validation** of generated content against a computer algebra (Maxima) backend
- Powers live curriculum material for Caltech's Math 1b/1c courses

</td>
</tr>
</table>

</details>

<details>
<summary><b>Embedded Moodle/STACK Real-Time Analytics Plugin</b> — real-time STACK analytics embedded directly into the Moodle course view</summary>
<br/>

<p>
<a href="https://github.com/ernestwting/quiz-quizanalytics-plugin.git"><img src="https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github&logoColor=white"/></a>
<img src="https://img.shields.io/github/last-commit/ernestwting/quiz-quizanalytics-plugin?style=flat-square&color=4c9aff&label=last%20commit"/>
<img src="https://img.shields.io/badge/type-Moodle%20Plugin-6272a4?style=flat-square"/>
</p>

Extends standalone analytics directly into the Moodle LMS ecosystem as an embedded, course-level plugin — no export/import step required.

<table width="100%">
<tr>
<td width="26%" valign="top">

**Stack**

<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/><br/>
<img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white"/><br/>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/><br/>
<img src="https://img.shields.io/badge/Moodle%20API-F98012?style=flat-square&logo=moodle&logoColor=white"/>

</td>
<td width="74%" valign="top">

**Highlights**
- **Real-time** item statistics rendered directly inside active course modules
- Live **PRT branch diagnostics** and attempt-trajectory views, no CSV round-trip

</td>
</tr>
</table>

</details>

<details>
<summary><b>Moodle/STACK Interactive Quiz Analytics Hub</b> — turns raw Moodle/STACK exports into interactive teaching insights, with one-click PDF reports</summary>
<br/>

<p>
<a href="https://interactive-analytics-stack-data.streamlit.app/"><img src="https://img.shields.io/badge/Live_App-Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white"/></a>
<a href="https://github.com/ernestwting/Interactive-quiz-analytics/tree/main"><img src="https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github&logoColor=white"/></a>
<img src="https://img.shields.io/github/last-commit/ernestwting/Interactive-quiz-analytics?style=flat-square&color=4c9aff&label=last%20commit"/>
</p>

An interactive web app that turns raw Moodle/STACK math assessment exports into actionable teaching insights.

<table width="100%">
<tr>
<td width="26%" valign="top">

**Stack**

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/><br/>
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white"/><br/>
<img src="https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white"/><br/>
<img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white"/><br/>
<img src="https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white"/><br/>
<img src="https://img.shields.io/badge/ReportLab-CC0000?style=flat-square"/>

</td>
<td width="74%" valign="top">

**Highlights**
- Facility ($F_i$) and discrimination ($D_i$) indices across best-attempt vs. all-attempt cohorts
- Interactive **PRT failure-mode heatmaps** and student-by-question performance matrices
- Runs client-side with **pseudonymized** data to preserve student privacy
- One-click, full-length PDF reports with dynamic commentary and vector charts

</td>
</tr>
</table>

</details>

<details>
<summary><b>Bioinformatics & Gene Correlation Analysis</b> — computational analysis of human genome gene-set correlations</summary>
<br/>

<p>
<img src="https://img.shields.io/badge/type-Research-b08968?style=flat-square"/>
<img src="https://img.shields.io/badge/focus-Human%20Genomics-b08968?style=flat-square"/>
</p>

Computational analysis on the human genome to surface gene set correlations and extract statistical patterns from large-scale biological datasets.

</details>

<details>
<summary><b>Combinatorics & Extremal Graph Theory</b> — combinatorial research in Ramsey & Schur's theorem</summary>
<br/>

<p>
<img src="https://img.shields.io/badge/type-Research-b08968?style=flat-square"/>
<img src="https://img.shields.io/badge/focus-Ramsey%20%26%20Schur's%20Theorem-b08968?style=flat-square"/>
</p>

Combinatorial research as a Research Assistant at South Dakota State University, investigating monochromatic subgraphs, colorings, and partition regularity within Ramsey theory.

</details>

---

## Conference Presentations

* **Poster Presentation:** *"Turning STACK Response Data into Insight"* – International STACK Conference, Nairobi, Kenya (July 2026)
* **Slideshow Presentation:** *"Moodle/STACK Interactive Quiz Analytics"* – International STACK Conference, Nairobi, Kenya (July 2026)
* **Academic Presentation:** *"The Big Lie: Distilling the Truth from Power"* – BHS Literary Conference (April 2025)

---

## Tech Stack

<table>
<tr><td><b>Languages</b></td><td>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white"/>
<img src="https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/>
<img src="https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white"/>
<img src="https://img.shields.io/badge/MATLAB-FF6F00?style=flat-square&logo=mathworks&logoColor=white"/>
<img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
</td></tr>
<tr><td><b>Data Science, ML & Psychometrics</b></td><td>
<img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white"/>
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white"/>
<img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white"/>
<img src="https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white"/>
<img src="https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white"/>
<img src="https://img.shields.io/badge/Item%20Response%20Theory-6A1B9A?style=flat-square"/>
<img src="https://img.shields.io/badge/Rasch%20Modeling-00897B?style=flat-square"/>
</td></tr>
<tr><td><b>Web, APIs & Cloud</b></td><td>
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/Firebase-DD2C00?style=flat-square&logo=firebase&logoColor=white"/>
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white"/>
<img src="https://img.shields.io/badge/Moodle%20API-F98012?style=flat-square&logo=moodle&logoColor=white"/>
<img src="https://img.shields.io/badge/LTI%201.3-005A9C?style=flat-square"/>
<img src="https://img.shields.io/badge/discord.py-5865F2?style=flat-square&logo=discord&logoColor=white"/>
</td></tr>
<tr><td><b>Automation, Reporting & Computational Math</b></td><td>
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/>
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black"/>
<img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white"/>
<img src="https://img.shields.io/badge/ReportLab-CC0000?style=flat-square"/>
<img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white"/>
<img src="https://img.shields.io/badge/Maxima%20CAS-5C6BC0?style=flat-square"/>
<img src="https://img.shields.io/badge/OpenPyXL-217346?style=flat-square"/>
</td></tr>
</table>

---

## Connect with Me

<div align="center">

* **Live App:** [interactive-analytics-stack-data.streamlit.app](https://interactive-analytics-stack-data.streamlit.app/)
* **My Moodle Plugin:** [STACK q-type Analytics for Moodle](https://github.com/ernestwting/moodle-local_stackquizanalytics.git) · [Live on Moodle Marketplace](https://marketplace.moodle.com/plugins/3995/versions#plugin-tab-content)
* **Institution:** California Institute of Technology (Pasadena, CA)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ernestwting/)
[![Outlook](https://img.shields.io/badge/Outlook-eting%40caltech.edu-0078D4?style=flat&logo=microsoftoutlook&logoColor=white)](mailto:eting@caltech.edu)

</div>

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f3460,50:16213e,100:1a1a2e&height=100&section=footer" width="100%"/>
