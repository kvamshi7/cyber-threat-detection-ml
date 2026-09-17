# cyber-threat-detection-ml
Machine learning-based Intrusion Detection System (IDS) for identifying cyber-attacks more effectively than traditional rule-based security methods.

Cybercrime keeps evolving, exploiting new vulnerabilities faster than traditional, rule-based security tools can keep up with. Most conventional Intrusion Detection Systems (IDS) struggle with the dynamic, constantly shifting nature of modern cyber-attacks. This project applies machine learning to intrusion detection — using it to spot patterns in network traffic that indicate an attack, rather than relying on fixed signatures. Several models were evaluated (Logistic Regression, Decision Tree, Random Forest, Neural Network), with Support Vector Machine (SVM) delivering the strongest classification performance. While ML can't fully automate cybersecurity on its own, it significantly reduces the manual burden on security analysts by improving detection rates and lowering false alarms.

# Tech Stack:

* **Language:** Python
* **Backend:** Django
* **ML Library:** scikit-learn
* **Dataset:** NSL-KDD
* **Primary Model:** Support Vector Machine (SVM)
* **Other Models Compared:** Logistic Regression, Decision Tree, Random Forest, Neural Network (MLP)
* **Optimization:** GridSearchCV, RFE/SelectKBest for feature selection
