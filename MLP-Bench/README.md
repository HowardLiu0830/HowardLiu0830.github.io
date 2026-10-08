# MLP-Bench Project Website

Project page for **MLP-Bench: Towards End-to-End Formal Research Assistance in Machine Learning Theory**.

Run `python3 -m http.server 4173 --bind 127.0.0.1` and visit `http://127.0.0.1:4173`.

- `index.html`: paper overview, benchmark tasks, results, and analysis.
- `static/css/style.css`: page styles, adapted from the HC-DLM project page template (https://hc-dlm.github.io/) with a light-blue accent.
- `static/images/mlp/`: images converted from the paper's PDF figures.
- `paper/`: extracted LaTeX source used for the page content.

Paper source: `Desktop/Papers/paper_latex/MLP-Bench-arXiv` (arXiv version, synchronized October 2, 2026). The website follows the sections included by `iclr2027_conference.tex`. Figures were re-rendered from the arXiv PDFs (`MLP_Example.drawio.pdf` → `tasks.png`, `drops_by_family_nordic.pdf` → `assumptions.png`).

The top interactive demo lives in `static/animations/mlp_examples.html` and `mlp_examples.js`. It offers three task walkthroughs from the paper figure, with manual Next step/Restart controls and automatic iframe sizing. Steps advance only on a click, including the final output. These are illustrative animations, not a live Lean execution service. The original RecursiveMAS animation file is retained as a reference. Code and dataset links are pending (the paper still uses placeholder URLs).

Layout and styling adapted from the HC-DLM project page (earlier versions used the RecursiveMAS template; its Bulma/`index.css`/`mlp.css` files in `static/` are no longer referenced). The template license is retained below; it does not establish a license for the paper or benchmark data.


## Website License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
