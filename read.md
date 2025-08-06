# 📧 Phishing Email Analysis Report

## Basic Information

| Item               | Example Value                                    |
|--------------------|--------------------------------------------------|
| Email File/Source  | sample-1037.eml                                  |
| Reviewed On        | 2025-08-06                                       |
| **Source of Sample** | Public repository on GitHub                |

---

## 1. Email Header and Metadata

| Header Information | Value                                                      |
|--------------------|------------------------------------------------------------|
| From               | (not shown, but expected to impersonate Microsoft)         |
| To                 | Not specified                                              |
| Subject            | Unusual sign.in activity                                   |
| Date               | Mon, 31 Jul 2023 22:07:19 +0000                           |
| IP address         | 103.225.77.255                                             |
| Reported Location  | Russia/Moscow                                              |

**Source of Sample Phishing Email:**  
The phishing email used in this analysis was sourced from a public collection for educational and training purposes, specifically from a GitHub repository at:  
`https://github.com/Sridhar-s-12/Sridhar_interntask_elvlab/blob/Task-2/README.md#-source-of-sample-phishing-email`

---

## 2. Email Body Content

> Unusual sign.in activity  
> We detected something unusual about a recent sign-in to the Microsoft account phishing@pot.  
> **Sign-in details**  
> Country/region: Russia/Moscow  
> IP address: 103.225.77.255  
> Date: Mon, 31 Jul 2023 22:07:19 +0000  
> Platform: Windows 10  
> Browser: Firefox  
> A user from Russia/Moscow just logged into your account from a new device, If this wasn't you, please report the user. If this was you, we'll trust similar activity in the future.  
> To opt out or change where you receive security notifications, click here.  
> Thanks,  
> The Microsoft account team  

---

## 3. Key Observations & Phishing Indicators

| Indicator Category      | Finding in Sample Email                                    |
|------------------------|------------------------------------------------------------|
| **Source**             | Taken from GitHub education repository                  |
| Spoofed Brand          | Impersonates Microsoft account team                        |
| Suspicious Language    | Urgent: "report the user" if this wasn't you               |
| Unusual Location/IP    | Claims sign-in from Russia—attempts to alarm recipient     |
| No Personalization     | No name or specific account info used                      |
| Awkward Phrasing       | “Unusual sign.in activity” (spelling/punctuation)          |
| Links (Implied)        | “click here” for changing notifications                   |
| Weak Branding          | No official Microsoft logos, bland formatting              |

---

## 4. Screenshots/Images: 

MAIL : 

<img width="2525" height="1424" alt="Image" src="https://github.com/user-attachments/assets/01dfd816-c31a-4e61-af73-2303907e866a" />

REPORT :

<img width="2521" height="1163" alt="Image" src="https://github.com/user-attachments/assets/3ab72ec2-c044-482b-9bf8-33c7f7caf966" />

---

## 5. Conclusion

This email is a clear phishing attempt. It relies on alarming sign-in events, ambiguous urgent instructions, unverified sources, and lack of proper branding. Always verify sender details and never click unknown links.

---

## Summary Table

| Category         | Finding                                         |
|------------------|------------------------------------------------|
| Source           | Public phishing repository (GitHub)          |
| Brand            | Fakes Microsoft                                |
| Location/IP      | Unusual, foreign, meant to alarm               |
| Language         | Generic, urgent, no personalization            |
| Link/Action      | “Click here”—destination not shown             |
| Branding         | Lacks logo, unprofessional                     |

---

**Reminder:** Only handle sanitized/educational samples from reputable public repositories—never real phishing emails from your inbox.

