# capstone-notebooks

Capstone notebooks distributed to students' JupyterLab (lab.bytek.tech) via **nbgitpuller** —
clicking "Open Lab" in the app pulls this repo into the student's home and opens the notebook
(auto-merging, so their edits are never lost; teacher pushes here → students get updates on next launch).

## ai-agents
`ai-agents/capstone.ipynb` — **وكيل مدن السعودية**: the student builds a real LangChain agent that
answers questions about Saudi cities by calling a tool that queries `ai-agents/saudi_cities.csv`
(city, region, population). Fill-in `# TODO` cells, run cell-by-cell, with stretch goals
(a compare-cities tool, conversation memory). Students use their own LLM API key.

> `*_solution.ipynb` (teacher key) is kept out of this public repo on purpose.
