# Hi there, I'm Sattwik! 👋

Welcome to my portfolio! I am an undergraduate student combining a strong foundation in humanities with modern technical skills.

## 🎓 Education & Certifications
* **Degree:** English Honours (Ongoing) - Egra Sarada Shashi Bhusan College
* **Diploma:** Diploma in Office Management
* **Current Certification:** Google Cybersecurity Professional Certificate (Coursera, Ongoing)
* **Global Event Certifications:** 
  * [Promise of Yoga365 (Ministry of Ayush & Habuild)](IMG-20260614-WA0011.jpg)
  * [Certificate of Strength - World Records Union](IMG-20260617-WA0073.jpg)

## 🤝 Community & Social Work
* **NSS (National Service Scheme):** Active Member (Involved in community service and social welfare activities)
  * [Registration certificate](Registration%20Certificate.pdf).
## 💻 Skills & Interests
* **Humanities & Management:** Advanced Communication, Content Writing, Critical Thinking, Office Administration
* **Cybersecurity:** Network Security, Linux, SQL, Python (Basics), Security Information and Event Management (SIEM)
* **Goal:** Bridging communication and technical security to build a safer digital environment.

## 📬 How to reach me
* Connect with me on GitHub and watch this space grow as I add more projects!

## 🛠️ Projects

### Apply Filters to SQL Queries

**Project Description:**
As a security professional, I performed several SQL queries on organizational datasets (`log_in_attempts` and `employees`) to investigate security incidents. By using filters with logical operators such as `AND`, `OR`, and `NOT`, along with pattern matching using `LIKE`, I was able to identify suspicious activities and isolate target employee groups for system updates.

#### 1. Retrieve After Hours Failed Login Attempts
This query filters the `log_in_attempts` table to return records where login attempts occurred after 18:00 hours (`login_time > '18:00'`) and were unsuccessful (`success = 0`).

```sql
SELECT *
FROM log_in_attempts
WHERE login_time > '18:00' AND success = 0;
'''
#### 2. Retrieve Login Attempts on Specific Dates
This query uses the `OR` operator to filter the `log_in_attempts` table for activity that occurred on either `2022-05-09` or `2022-05-08`.

```sql
SELECT *
FROM log_in_attempts
WHERE login_date = '2022-05-09' OR login_date = '2022-05-08';
'''
