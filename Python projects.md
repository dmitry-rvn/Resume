### Python/DS projects at work

1. **Web-app for working with documents + text classification ML pipeline**
- load Word-document (committee's protocols), parse and extract structured data (including finding linkages between protocols like "*this* paragraph cancels *that* paragraph"), insert data into database, display data in browser (filter, search, export, etc)
- `Django 3` backend
- HTML + CSS + JS frontend
- multilabel text classification (`spacy` + `scikit-learn`) ML-pipeline (with automated batch retraining)
- dashboard for ML model performance: metrics, word cloud, tokens importances
- deployed on Windows Server with IIS

---

2. **Robotic process automation (RPA) library**
- wrapper around dozens of libraries
- allows to automate interaction with corporate software (open specific window, find location or check presence of smth on the screen, press key / click mouse / type text, etc.)
- easy to create a new robot or modify existing one

---

3. **Customer churn prediction**
- extracting features from transactional and deals data of customers
- `CatBoost` model; hyperparameters search
- `MLflow` for experiment tracking, model registry

---

4. **Data quality monitoring app**
- CLI-application for everyday automated data quality checks
- alerting in messenger
- visualization in dashboards on Power BI Report Server
- easy to create a new check case

---

5. **Other**:
- CLI-apps for data processing (extract - transform - save/load)
- `FastAPI` service to trigger CLI-apps
- `prefect orion` for tasks orchestration

---

### Other / non-working Python/DS projects:

1. Package for extracting `subject - verb - object` triplets in russian texts: [ru-svo-triplets](https://github.com/dmitry-rvn/ru-svo-triplets)
2. Project example for tasks execution using directed acyclic graphs (DAGs) (when separate orchestrator is an overkill): [dag-execution-example](https://github.com/dmitry-rvn/dag-execution-example)
3. Simple staff-rooms allocation optimiziation: [staff-allocation-optimization](https://github.com/dmitry-rvn/staff-allocation-optimization)
4. Custom PyTorch-like deep learning framework ([Carnegie Mellon University online-course](https://dlsyscourse.org/))
5. Computer vision DL model for facial landmark detection
6. Computer vision DL model for car license plate segmentation and OCR
7. Transactional data and clickstream data matching
8. Text translation with Seq2Seq, Attention and Transfomer architecures
