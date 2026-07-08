Capstone Project: Research Question Framing

Selected Lane:
Enterprise Risk Mitigation / Behavioral Threat Intelligence

Research Question:
How can we find unusual user activity and possible data leaks in company network logs before data is stolen?

Unit of Analysis:
User sessions collected over 24 hours, including login activity, accessed systems, and data transfers.

Output:
A daily list of risky user accounts with a risk score and reasons why they were flagged.

Decision:
SOC and GRC teams can use the results to investigate the user, block access, escalate the issue, or mark it as a false alarm.

Risk of Wrong Decisions:

- False Positive: A normal employee is wrongly flagged, causing unnecessary problems.
- False Negative: A real data breach is missed, causing financial loss and reputation damage.

Why This Project Matters:
This project is not only about building a machine learning model. It focuses on reducing security risks by finding real threats and reducing false alerts.

Why Use Data or Machine Learning:
Rule-based systems only detect known threats. Machine learning can learn normal user behavior and identify unusual patterns that may be difficult for humans to find.
