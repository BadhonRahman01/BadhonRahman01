
<!-- Profile README for github.com/BadhonRahman01 ───────────────────────────────────────────── • The banners live in ./assets (dark + light variants; GitHub picks one based on the visitor's theme). • Everything else is plain Markdown/HTML – edit freely. • Things marked TODO are the spots you will most likely want to touch. --> <div align="center"> <picture> <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg"> <source media="(prefers-color-scheme: light)" srcset="assets/header-light.svg"> <img src="assets/header-light.svg" alt="Badhon Rahman — Doctoral Researcher in quantum software security, University of Jyväskylä" width="100%"> </picture> </div> <p align="center"> <a href="https://www.jyu.fi/en/people/badhon-rahman"><img alt="University of Jyväskylä profile" src="https://img.shields.io/badge/JYU-people_page-0e7490?style=flat-square"></a> <a href="https://orcid.org/0009-0004-4431-6442"><img alt="ORCID" src="https://img.shields.io/badge/ORCID-0009--0004--4431--6442-A6CE39?style=flat-square&logo=orcid&logoColor=white"></a> <a href="https://www.linkedin.com/in/badhon-rahman/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-badhon--rahman-0A66C2?style=flat-square"></a> <a href="https://stackoverflow.com/users/21998386/badhon-rahman"><img alt="Stack Overflow" src="https://img.shields.io/badge/Stack_Overflow-badhon--rahman-F58025?style=flat-square&logo=stackoverflow&logoColor=white"></a> <a href="mailto:badhon.b.rahman@jyu.fi"><img alt="Email" src="https://img.shields.io/badge/Email-badhon.b.rahman%40jyu.fi-6d28d9?style=flat-square"></a> <!-- TODO: add Google Scholar when you have a profile: <a href="https://scholar.google.com/citations?user=XXXX"><img alt="Google Scholar" src="https://img.shields.io/badge/Google_Scholar-profile-4285F4?style=flat-square&logo=googlescholar&logoColor=white"></a> --> </p>
About me

I'm a Doctoral Researcher at the Faculty of Information Technology, University of Jyväskylä (Finland), where I have been working on the security of quantum software since 2025 as part of the SeQuSoS project.

Before the PhD I completed an M.Sc. in Software Engineering at LUT University and worked as a Software Engineer, so I tend to look at quantum computing the way an engineer looks at any production system: as a stack of SDKs, compilers, cloud services and hardware that can be attacked, and should be defended.

The question behind my research is simple to state: how can a quantum software stack be breached, and what would it take to make it secure? I study it at two levels — the quantum software ecosystem itself, and the cloud pipelines (Quantum-as-a-Service) that take a circuit from a developer's laptop to real quantum hardware and back.

🎯 Interests: quantum computing · quantum software engineering · software security · threat modelling · security benchmarking

Research focus
<table> <tr> <td width="33%" valign="top"> <h3 align="center">🧨 What can go wrong</h3> <p>Four families of attacks on the quantum software stack — <b>crosstalk</b>, <b>side-channel</b>, <b>fault injection</b> and <b>pulse-level</b> — broken down into 14 attack classes, each with its origin, its consequences and known specimens.</p> <p align="center"><sub><i>Journal of Systems and Software, 2026</i></sub></p> </td> <td width="33%" valign="top"> <h3 align="center">☁️ Where it happens</h3> <p>An end-to-end <b>STRIDE threat model</b> of the six-stage <b>Quantum-as-a-Service pipeline</b>: developer environment, authentication &amp; submission, cloud compilation, shared hardware, result return and the hybrid loop — including everything that sits outside the user's trust boundary.</p> <p align="center"><sub><i>IEEE Quantum Week 2026, poster</i></sub></p> </td> <td width="33%" valign="top"> <h3 align="center">📏 How to measure and fix it</h3> <p><b>Security Figures of Merit</b> (S-FoMs) mapped to ISO/IEC 25010 and to the pipeline stages, plus a benchmarking rubric that normalises them and rolls them up into one <b>Quantum Software Security Posture (QSSP)</b> score — so that, for the first time, security tools and techniques can be compared on a common scale. On the defence side: 30+ mitigations mapped to the attack families.</p> <p align="center"><sub><i>IEEE Quantum Week 2026, workshop paper</i></sub></p> </td> </tr> </table> <p align="center"> <code>4</code> attack families &nbsp;·&nbsp; <code>14</code> attack classes &nbsp;·&nbsp; <code>30+</code> mitigations &nbsp;·&nbsp; <code>6</code> pipeline stages &nbsp;·&nbsp; <code>13</code> S-FoMs &nbsp;·&nbsp; <code>1</code> QSSP score </p> <div align="center"> <picture> <source media="(prefers-color-scheme: dark)" srcset="assets/pipeline-dark.svg"> <source media="(prefers-color-scheme: light)" srcset="assets/pipeline-light.svg"> <img src="assets/pipeline-light.svg" alt="The six-stage Quantum-as-a-Service pipeline with a trust boundary between the client side and the provider side" width="100%"> </picture> </div>
Publications
<!-- Newest first. Each entry has a collapsible BibTeX block. -->

Classification of security challenges and mitigation approaches in the quantum software engineering <br>B. Rahman, M. Haghparast, T. Mikkonen — Journal of Systems and Software, vol. 238, 112884 (2026) · peer-reviewed · JUFO 3 · open access (CC BY 4.0) <br><a href="https://doi.org/10.1016/j.jss.2026.112884"><img alt="DOI" src="https://img.shields.io/badge/DOI-10.1016%2Fj.jss.2026.112884-0e7490?style=flat-square&logo=doi&logoColor=white"></a> <a href="https://urn.fi/URN:NBN:fi:jyu-202604093248"><img alt="Open-access PDF" src="https://img.shields.io/badge/PDF-JYX_open_access-6d28d9?style=flat-square"></a> <a href="https://www.sciencedirect.com/journal/journal-of-systems-and-software"><img alt="Elsevier" src="https://img.shields.io/badge/Journal_of_Systems_and_Software-Elsevier-FF6C00?style=flat-square&logo=elsevier&logoColor=white"></a>

<details> <summary>BibTeX</summary>
bibtex
@article{rahman2026classification,
  title   = {Classification of security challenges and mitigation approaches in the quantum software engineering},
  author  = {Rahman, Badhon and Haghparast, Majid and Mikkonen, Tommi},
  journal = {Journal of Systems and Software},
  volume  = {238},
  pages   = {112884},
  year    = {2026},
  doi     = {10.1016/j.jss.2026.112884}
}
</details>

On the Figures of Merit for Quantum Software Security: Toward a Benchmarking Rubric <br>B. Rahman, M. Haghparast, T. Mikkonen — accepted at IEEE International Conference on Quantum Computing and Engineering (QCE26 / IEEE Quantum Week), workshop paper · JUFO 1 <br><a href="https://arxiv.org/abs/2608.05831"><img alt="arXiv" src="https://img.shields.io/badge/arXiv-2608.05831-B31B1B?style=flat-square&logo=arxiv&logoColor=white"></a> <a href="https://qce.quantum.ieee.org/"><img alt="IEEE Quantum Week" src="https://img.shields.io/badge/IEEE_Quantum_Week-2026-00629B?style=flat-square&logo=ieee&logoColor=white"></a>

<details> <summary>BibTeX</summary>
bibtex
@misc{rahman2026figures,
  title         = {On the Figures of Merit for Quantum Software Security: Toward a Benchmarking Rubric},
  author        = {Rahman, Badhon and Haghparast, Majid and Mikkonen, Tommi},
  year          = {2026},
  eprint        = {2608.05831},
  archivePrefix = {arXiv},
  note          = {Accepted at IEEE International Conference on Quantum Computing and Engineering (QCE), workshop paper}
}
</details>

An End-to-End Threat Model for the Quantum-as-a-Service Pipeline <br>B. Rahman, M. Haghparast, T. Mikkonen — accepted at IEEE International Conference on Quantum Computing and Engineering (QCE26 / IEEE Quantum Week), poster paper <br><a href="https://arxiv.org/abs/2608.05836"><img alt="arXiv" src="https://img.shields.io/badge/arXiv-2608.05836-B31B1B?style=flat-square&logo=arxiv&logoColor=white"></a> <a href="https://qce.quantum.ieee.org/"><img alt="IEEE Quantum Week" src="https://img.shields.io/badge/IEEE_Quantum_Week-2026-00629B?style=flat-square&logo=ieee&logoColor=white"></a>

<details> <summary>BibTeX</summary>
bibtex
@misc{rahman2026threatmodel,
  title         = {An End-to-End Threat Model for the Quantum-as-a-Service Pipeline},
  author        = {Rahman, Badhon and Haghparast, Majid and Mikkonen, Tommi},
  year          = {2026},
  eprint        = {2608.05836},
  archivePrefix = {arXiv},
  note          = {Accepted at IEEE International Conference on Quantum Computing and Engineering (QCE), poster paper}
}
</details> <p><sub>Full list on <a href="https://orcid.org/0009-0004-4431-6442">ORCID</a>.</sub></p>
Toolbox
<!-- TODO: adjust to what you actually use day to day. --> <p> <b>Quantum&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</b> <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"> <img alt="Qiskit" src="https://img.shields.io/badge/Qiskit-6929C4?style=flat-square&logo=qiskit&logoColor=white"> <img alt="Quantum-as-a-Service" src="https://img.shields.io/badge/Quantum--as--a--Service-pipelines-0e7490?style=flat-square"> </p> <p> <b>Engineering</b> <img alt="PHP" src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white"> <img alt="Laravel" src="https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white"> <img alt="Vue.js" src="https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white"> <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"> <img alt="MySQL" src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"> <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"> <img alt="Git" src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"> </p> <p> <b>Research&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</b> <img alt="LaTeX" src="https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white"> <img alt="STRIDE threat modelling" src="https://img.shields.io/badge/Threat_modelling-STRIDE-6d28d9?style=flat-square"> <img alt="ISO/IEC 25010" src="https://img.shields.io/badge/Security_quality-ISO%2FIEC_25010-6d28d9?style=flat-square"> <img alt="Benchmarking" src="https://img.shields.io/badge/Benchmarking-S--FoMs_and_QSSP-6d28d9?style=flat-square"> </p>
The path so far
<div align="center"> <picture> <source media="(prefers-color-scheme: dark)" srcset="assets/timeline-dark.svg"> <source media="(prefers-color-scheme: light)" srcset="assets/timeline-light.svg"> <img src="assets/timeline-light.svg" alt="Career timeline drawn as a one-qubit circuit: M.Sc. at LUT University, Software Engineer, Doctoral Researcher at the University of Jyväskylä since 2025, Ph.D. measurement pending" width="100%"> </picture> </div>
On GitHub
<p align="center"> <picture> <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=BadhonRahman01&show_icons=true&bg_color=0d1117&border_color=30363d&title_color=22d3ee&text_color=c9d1d9&icon_color=a78bfa"> <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api?username=BadhonRahman01&show_icons=true&bg_color=ffffff&border_color=d0d7de&title_color=0e7490&text_color=1f2328&icon_color=6d28d9"> <img alt="GitHub stats" height="170" src="https://github-readme-stats.vercel.app/api?username=BadhonRahman01&show_icons=true&bg_color=ffffff&border_color=d0d7de&title_color=0e7490&text_color=1f2328&icon_color=6d28d9"> </picture> <picture> <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com/?user=BadhonRahman01&background=0D1117&border=30363D&stroke=30363D&ring=22D3EE&fire=A78BFA&currStreakNum=E6EDF3&sideNums=E6EDF3&currStreakLabel=22D3EE&sideLabels=8B949E&dates=8B949E"> <source media="(prefers-color-scheme: light)" srcset="https://streak-stats.demolab.com/?user=BadhonRahman01&background=FFFFFF&border=D0D7DE&stroke=D0D7DE&ring=0E7490&fire=6D28D9&currStreakNum=1F2328&sideNums=1F2328&currStreakLabel=0E7490&sideLabels=656D76&dates=656D76"> <img alt="GitHub streak" height="170" src="https://streak-stats.demolab.com/?user=BadhonRahman01&background=FFFFFF&border=D0D7DE&stroke=D0D7DE&ring=0E7490&fire=6D28D9&currStreakNum=1F2328&sideNums=1F2328&currStreakLabel=0E7490&sideLabels=656D76&dates=656D76"> </picture> </p> <p align="center"> <picture> <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=BadhonRahman01&layout=compact&langs_count=8&hide=c%23,powershell,mathematica,ruby,objective-c,objective-c%2B%2B,cuda&bg_color=0d1117&border_color=30363d&title_color=22d3ee&text_color=c9d1d9"> <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=BadhonRahman01&layout=compact&langs_count=8&hide=c%23,powershell,mathematica,ruby,objective-c,objective-c%2B%2B,cuda&bg_color=ffffff&border_color=d0d7de&title_color=0e7490&text_color=1f2328"> <img alt="Most used languages" width="420" src="https://github-readme-stats.vercel.app/api/top-langs/?username=BadhonRahman01&layout=compact&langs_count=8&hide=c%23,powershell,mathematica,ruby,objective-c,objective-c%2B%2B,cuda&bg_color=ffffff&border_color=d0d7de&title_color=0e7490&text_color=1f2328"> </picture> </p> <p align="center"><sub>Most of my public repositories date from my software-engineering years (Laravel, Vue, PHP). The quantum-security work currently lives mostly in the papers above.</sub></p>
Let's talk

I'm always glad to hear from people working on quantum software security, threat modelling for Quantum-as-a-Service, security benchmarking, or quantum software engineering in general — whether it's about a paper, a tool, or just a question.

📧 badhon.b.rahman@jyu.fi  ·  🎓 University profile  ·  🆔 ORCID  ·  💼 LinkedIn

<br> <p align="center"><code>|ψ⟩ = α|engineer⟩ + β|researcher⟩</code></p>
