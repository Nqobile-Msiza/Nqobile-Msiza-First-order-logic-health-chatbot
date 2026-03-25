📌 Overview

This project implements a rule-based healthcare chatbot using First-Order Logic (FOL) principles. The chatbot asks users about their symptoms and provides a probable diagnosis along with actionable health advice based on a predefined knowledge base.

The system is designed to demonstrate how logical inference can be used in simple diagnostic applications. It covers five common illnesses:

Flu

Common Cold

Malaria

COVID-19

Strep Throat

🧠 How It Works

Knowledge Base:
Each disease is associated with a set of symptoms using a dictionary.

First-Order Logic Rules:
The chatbot uses rules like:

Disease(flu) ← has_symptom(fever) ∧ has_symptom(cough) ∧ has_symptom(sore_throat)

User Interaction:
The user is prompted to answer yes/no questions for each symptom in the system.

Diagnosis:
The chatbot checks which diseases match all reported symptoms and returns a diagnosis.

Advice:
For each diagnosed disease, a list of recommended actions is provided from the advice base.

🛠️ Proposed Enhancements

The following features are planned for future development:

Severity Assessment

Ask follow-up questions to determine urgency (mild, moderate, severe).

Multilingual Support

Allow users to interact in multiple languages using translation APIs.

Symptom Tracker & History

Log user inputs over time and visualize symptom trends.

📝 Conclusion

This project successfully demonstrates the application of First-Order Logic in a rule-based diagnostic system. It provides a solid foundation for expanding into more intelligent, interactive health tools with enhanced usability and accuracy.



