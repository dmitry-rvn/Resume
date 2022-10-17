### Python projects at work

---

1. **Web-app for working with documents + text classification ML pipeline**
- load Word-document (committee's protocols), parse and extract structured data (including finding linkages between protocols), put data into database, display data in browser
- `Django` backend
- HTML + CSS + JS frontend
- multilabel text classification (`spacy` + `scikit-learn`) pipeline (with automated batch retraining)
- custom logging; logs displayed in a dashboard on Power BI Report Server
- dashboard for ML model performance: metrics, word cloud, tokens importance
- deployed on Windows Server with IIS

---

2. **Robotic process automation (RPA) library**
- wrapper around dozens of libraries
- allows to automate interaction with corporate software (open specific window, find location or check presence of smth on the screen, press key / click mouse / type text, etc.)
- easy to create a new robot or modify existing one

---

3. **Other**:
- CLI-app for everyday data quality checks
- CLI-app for triggering Power BI reports update or script launching on condition (specific DWH tables readiness)
- numerous CLI-apps for data processing tasks (extract - transform - save/load)
- `FastAPI` service to use previously mentioned CLI-apps

---

### Other Python projects:

1. Package for extracting `subject - verb - object` triplets in russian texts: [ru-svo-triplets](https://github.com/dmitry-rvn/ru-svo-triplets)
2. Project example for tasks execution using directed acyclic graphs (DAGs) (when separate orchestrator is an overkill): *to be added soon*
3. Project for staff allocation optimiziation: *to be added soon*
4. Custom PyTorch-like deep learning framework ([Carnegie Mellon University online-course](https://dlsyscourse.org/)): *to be added after completion*
