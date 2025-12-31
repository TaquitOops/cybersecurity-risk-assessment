# Detailed Risk Assessment Documentation

## 1. Operating Environment Description
The institution is a commercial bank located in a coastal area. Key characteristics include:
* **Personnel:** 100 on-premise employees and 20 remote employees.
* **Customers:** 2,000 individual accounts and 200 commercial accounts.
* **External Factors:** Low local crime rates but high susceptibility to natural disasters (hurricanes) every few years.
* **Regulations:** Strict financial regulations require daily cash availability for Federal Reserve requirements.

## 2. Risk Factor Analysis
Security events are possible due to several factors identified in the bank's current operations:
* **Human Error:** Instances where the bank's safe is left unlocked.
* **Technical Vulnerabilities:** Poor encryption of customer data and publicly accessible backup servers.
* **Social Engineering:** The presence of remote staff increases the likelihood of employees being tricked into sharing confidential data.

## 3. Risk Register (Completed)

| Asset | Risk | Description | Likelihood | Severity | Priority |
| :--- | :--- | :--- | :---: | :---: | :---: |
| Funds | Business Email Compromise | Employee is tricked via email. | 3 | 2 | **6** |
| Funds | Compromised User Database | Customer data is poorly encrypted. | 2 | 3 | **6** |
| Funds | Financial Records Leak | Publicly accessible backup server. | 1 | 3 | **3** |
| Funds | Theft | Safe is left unlocked in a low-crime area. | 1 | 2 | **2** |
| Funds | Supply Chain Disruption | Natural disasters (hurricanes). | 1 | 2 | **2** |

## 4. Priority Justification
* **Priority 6:** Assigned to BEC and Database Compromise because they represent either a high probability of occurrence or a catastrophic impact on customer trust and regulatory compliance.
* **Priority 3 & 2:** These risks are lower because their likelihood is rare, either due to the infrequent nature of hurricanes or the low crime rate of the area.
