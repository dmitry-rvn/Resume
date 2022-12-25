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
- `CatBoost` model; hyperparameters search; explanations with `shap`
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
- workflow orchestration with `prefect orion`
- bank balance sheet optimization (maximization of net interest income with respect to complex regulatory and business constraints)

---

### Other / non-working Python/DS projects:

1. Package for extracting `subject - verb - object` triplets in russian texts: [ru-svo-triplets](https://github.com/dmitry-rvn/ru-svo-triplets)
2. Project example for tasks execution using directed acyclic graphs (DAGs) (when separate orchestrator is an overkill): [dag-execution-example](https://github.com/dmitry-rvn/dag-execution-example)
3. Simple staff-rooms allocation optimiziation: [staff-allocation-optimization](https://github.com/dmitry-rvn/staff-allocation-optimization)
4. Custom PyTorch-like deep learning framework ([Carnegie Mellon University online-course](https://dlsyscourse.org/))
5. Employers reviews multilabel classification
6. Computer vision DL model for facial landmark detection
7. Computer vision DL model for car license plate segmentation and OCR
8. Customers matching based on transactional data (from one side) and clickstream data (from the other side)
9. Text translation with RNN Seq2Seq, Attention and Transformer architectures
