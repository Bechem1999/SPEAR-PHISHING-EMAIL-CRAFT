# 🔐 SQROCK IT Solution — Cybersecurity Internship

# Day 6: Spear Phishing Email Craft — Lab Only

![Kali Linux](https://img.shields.io/badge/Kali_Linux-2026.2-557C94?logo=kalilinux\&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.13.12-3776AB?logo=python\&logoColor=white)
![Cybersecurity](https://img.shields.io/badge/Focus-Cybersecurity-red)
![Social Engineering](https://img.shields.io/badge/Topic-Social%20Engineering-orange)
![Phishing Awareness](https://img.shields.io/badge/Phishing-Awareness-yellow)
![Ethical Hacking](https://img.shields.io/badge/Ethical-Hacking-green)
![Lab Only](https://img.shields.io/badge/Environment-Authorized%20Lab-blue)

---

## 📌 Project Overview

This project was completed as **Day 6 of the SQROCK IT Solution Cybersecurity Internship Program**.

The project focuses on understanding the structure and psychological techniques used in **spear-phishing attacks** and how personalized phishing messages can be identified and defended against.

A Python-based **phishing-awareness email template engine** was developed to generate controlled and fictional training scenarios. The exercise was conducted exclusively within an authorized cybersecurity laboratory environment.

The project also examined defensive email-authentication mechanisms including **SPF, DKIM, and DMARC**.

> ⚠️ **Ethical Notice:** This project is strictly for cybersecurity education and awareness training. No real individuals were targeted, no real credentials were collected, and no phishing emails were sent to external recipients.

---

# 🎯 Objectives

The main objectives of this project were to:

* Understand the concept of spear phishing.
* Understand how attackers personalize phishing messages.
* Identify common social-engineering techniques used in phishing.
* Develop a Python-based awareness email template generator.
* Generate fictional phishing-awareness scenarios.
* Understand the defensive role of SPF, DKIM, and DMARC.
* Practice identifying phishing indicators.
* Develop practical cybersecurity awareness skills.
* Maintain an ethical and controlled laboratory environment.

---

# 🛠️ Tools and Technologies Used

| Tool / Technology    | Purpose                                     |
| -------------------- | ------------------------------------------- |
| 🐉 Kali Linux 2026.2 | Cybersecurity laboratory environment        |
| 🐍 Python 3.13.12    | Email template generation                   |
| 💻 Linux Terminal    | Project execution and testing               |
| 📝 Nano              | Python and Markdown file creation           |
| 📄 Markdown          | Project documentation                       |
| 🛡️ SPF              | Sender authentication                       |
| 🔐 DKIM              | Email message authentication                |
| 🛡️ DMARC            | Email authentication and policy enforcement |
| 🐙 GitHub            | Version control and project documentation   |

---

# 🧠 Skills Demonstrated

Through this project, I demonstrated the following skills:

* Social engineering awareness
* Phishing analysis
* Spear-phishing analysis
* Python scripting
* Python functions and dictionaries
* Automated text generation
* Cybersecurity documentation
* Email security awareness
* SPF/DKIM/DMARC concepts
* Linux command-line usage
* Ethical cybersecurity testing
* Security-awareness training development

---

# 🔬 Methodology

The project was completed through the following stages:

### 1. Understanding Spear Phishing

The first stage involved studying spear phishing and understanding how it differs from generic phishing.

Spear phishing typically uses information about a specific person or organization to make a fraudulent message appear more convincing.

---

### 2. Creating a Controlled Laboratory Environment

The project was performed using Kali Linux in an authorized educational environment.

Only fictional identities and `.test` email addresses were used.

Example:

```text
riya@example.test
daniel@example.test
sarah@example.test
```

No real users were contacted.

---

### 3. Developing the Python Template Engine

A Python script named:

```text
spear_phish_awareness.py
```

was created.

The script uses a Python function to generate personalized awareness-training messages from predefined fictional target information.

The information included:

* Name
* Email address
* Organization
* Location

---

### 4. Generating Training Scenarios

The script generated three fictional awareness scenarios.

Each scenario demonstrated how personalization can make a suspicious message appear more believable.

The generated messages remained inside the laboratory and were not delivered to real recipients.

---

### 5. Saving the Output

The generated scenarios were saved into:

```text
scenario_output.txt
```

This provided a persistent record of the experiment and made it easier to document the results.

---

### 6. Studying Email Authentication

A separate document was created to study:

* SPF
* DKIM
* DMARC

These technologies were examined from a **defensive perspective**.

---

# 💻 Laboratory Environment

The project was performed using:

```text
Operating System : Kali Linux 2026.2
Python           : 3.13.12
Environment      : Authorized Cybersecurity Lab
Project Type     : Security Awareness Simulation
```

The exercise was designed to remain isolated from real-world targets.

---

# ⚙️ Environment Configuration

### Step 1 — Create the project directory

```bash
mkdir -p ~/sqrock-internship/day6-spear-phishing
```

### Step 2 — Navigate to the project

```bash
cd ~/sqrock-internship/day6-spear-phishing
```

### Step 3 — Verify Python

```bash
python3 --version
```

Expected:

```text
Python 3.13.12
```

---

# 🐍 Python Implementation

The main Python file is:

```text
spear_phish_awareness.py
```

The program generates controlled awareness-training messages from fictional data.

Example structure:

```python
def spear_phish_template(target):
    return f"""
=== SPEAR-PHISHING AWARENESS SIMULATION ===

From    : training-it@example.test
To      : {target['email']}

Hi {target['name']},

This is an authorized cybersecurity awareness exercise.

Company  : {target['company']}
Location : {target['location']}

Training Link:
https://localhost/awareness-test

IMPORTANT:
This message is part of a controlled security-awareness
simulation. No credentials should be entered.
"""
```

The program was intentionally designed for **awareness training rather than real-world phishing delivery**.

---

# ▶️ Running the Program

Execute:

```bash
python3 spear_phish_awareness.py
```

The program generates multiple fictional training scenarios.

The output can also be saved using:

```bash
python3 spear_phish_awareness.py > scenario_output.txt
```

The saved output can then be viewed with:

```bash
cat scenario_output.txt
```

---

# 🛡️ Email Security: SPF, DKIM and DMARC

## SPF — Sender Policy Framework

SPF allows domain owners to specify which mail servers are authorized to send email on behalf of their domain.

### Defensive benefit

It helps receiving mail systems identify unauthorized sending infrastructure.

---

## DKIM — DomainKeys Identified Mail

DKIM adds a cryptographic signature to outgoing email.

### Defensive benefit

Receiving systems can use the signature to verify that the message was authorized by the sending domain and that important parts of the message were not modified.

---

## DMARC — Domain-based Message Authentication, Reporting and Conformance

DMARC builds on SPF and DKIM.

It allows domain owners to publish policies describing how receiving systems should handle messages that fail authentication.

### Defensive benefit

DMARC can help organizations detect and reduce unauthorized email impersonation.

---

# 🚩 Phishing Indicators Identified

During the exercise, the following indicators were examined:

* Unexpected security requests
* Urgent account-related messages
* Suspicious links
* Sender impersonation
* Requests for sensitive information
* Unusual login notifications
* Pressure to act quickly
* Personalized information designed to create trust

---

# 📁 Project Structure

```text
day6-spear-phishing/
│
├── spear_phish_awareness.py
│
├── scenario_output.txt
│
├── email-authentication.md
│
└── day6-analysis.md
```

### File Descriptions

| File                       | Description                               |
| -------------------------- | ----------------------------------------- |
| `spear_phish_awareness.py` | Python awareness-email template generator |
| `scenario_output.txt`      | Output generated by the Python program    |
| `email-authentication.md`  | SPF, DKIM and DMARC defensive guide       |
| `day6-analysis.md`         | Analysis and learning outcomes            |

---

# 📊 Results

The Python program successfully generated multiple fictional spear-phishing awareness scenarios.

The experiment demonstrated that personalized information can be incorporated into simulated phishing messages.

The project also reinforced the importance of:

* Email authentication
* User awareness
* MFA
* Verification through trusted channels
* Security monitoring

No real users or external systems were targeted.

---

# 🔐 Security and Ethical Considerations

This project was performed strictly for cybersecurity education.

The following restrictions were observed:

* ✅ Authorized laboratory environment
* ✅ Fictional identities
* ✅ `.test` email addresses
* ✅ No real recipients
* ✅ No credential collection
* ✅ No external phishing campaign
* ✅ No malicious attachments
* ✅ No credential harvesting
* ✅ No unauthorized system access

The purpose of the project was to understand **how phishing works so that it can be detected and prevented**.

---

# 🧩 Challenges Faced and How They Were Overcome

### Challenge 1 — Understanding Spear Phishing

Initially, it was necessary to distinguish spear phishing from ordinary phishing.

**Solution:**
The project examined the role of personalization and targeted information in spear-phishing scenarios.

---

### Challenge 2 — Generating Multiple Training Scenarios

Creating several different messages manually would be repetitive.

**Solution:**
A reusable Python function was developed to generate personalized awareness scenarios from structured data.

---

### Challenge 3 — Understanding Email Authentication

SPF, DKIM and DMARC involve different aspects of email security.

**Solution:**
Each technology was studied separately and documented according to its defensive purpose.

---

### Challenge 4 — Maintaining Ethical Boundaries

Phishing techniques can easily cross from educational simulation into unauthorized activity.

**Solution:**
The project was restricted to fictional data, local testing and authorized cybersecurity training.

---

# 🎓 Learning Outcomes

After completing this project, I gained a better understanding of:

* How spear-phishing attacks are structured.
* How attackers may use personalization to increase credibility.
* How social-engineering techniques influence user behavior.
* How Python can automate security-awareness simulations.
* How SPF contributes to email authentication.
* How DKIM contributes to message integrity and authentication.
* How DMARC provides policy and reporting capabilities.
* Why security awareness is an important layer of defense.
* The importance of conducting cybersecurity experiments ethically.

# 📌 Conclusion

The **Day 6 Spear Phishing Email Craft** project provided practical experience in understanding targeted social-engineering techniques while maintaining a controlled and ethical laboratory environment.

The Python implementation demonstrated how structured data can be used to generate awareness-training scenarios, while the study of SPF, DKIM and DMARC highlighted important defensive mechanisms for reducing email impersonation risks.

This project strengthened my practical knowledge of **social engineering, phishing awareness, Python automation and email security** as part of my cybersecurity training at **SQROCK IT Solution**.
