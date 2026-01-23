---
layout: default
title: Nameet Jain | Engineering Manager
---

# Nameet Jain
**Engineering Manager | Backend & Cloud Architect**

📍 Indore, India  
📧 jnameet@gmail.com  
🔗 https://www.linkedin.com/in/nameet-jain  
📞 +91-8109920372  

[Download Resume](/assets/resume/Nameet_Jain_Resume.pdf)

---

## Professional Summary

Engineering Manager with **14+ years of experience** designing, developing,
and scaling enterprise backend systems for **E-commerce, ERP, and Omnichannel
Retail platforms**.

Specialized in **Java (8/11/17)**, **Spring Boot**, **Microservices**, **Apache OFBiz**,
and **AWS Cloud**, with deep experience in **Kubernetes**, system performance
optimization, and third-party integrations.

Proven track record of leading cross-functional teams, delivering SaaS products,
and improving system reliability, performance, and scalability.

---

## Core Skills

{% for category in site.data.skills %}
### {{ category[0] | capitalize }}
<ul>
{% for skill in category[1] %}
  <li>{{ skill }}</li>
{% endfor %}
</ul>
{% endfor %}

---

## Professional Experience

{% for job in site.data.experience %}
### {{ job.role }} — {{ job.company }}
*{{ job.duration }}*

<ul>
{% for item in job.achievements %}
  <li>{{ item }}</li>
{% endfor %}
</ul>

**Technologies:** {{ job.tech | join: ", " }}

{% endfor %}

---

## Key Projects

{% for project in site.data.projects %}
### {{ project.name }}
**Role:** {{ project.role }}  
**Duration:** {{ project.duration }}

{{ project.description }}

<ul>
{% for h in project.highlights %}
  <li>{{ h }}</li>
{% endfor %}
</ul>

{% endfor %}

---

## Education

**Bachelor of Engineering (Computer Science)**  
Patel College of Science & Technology, Indore  
*2007 – 2011*

---

## Open Source & Leadership

- Contributor to the **Apache OFBiz open-source community**
- Mentor for engineers and interview panels
- Organizer of company **Hacktoberfest meetups**
- Exploring **Generative AI tools** (GitHub Copilot, ChatGPT) to improve productivity

---

## Keywords (ATS Optimization)

Engineering Manager, Java Developer, Backend Engineer, Spring Boot,
Microservices Architect, AWS Engineer, Kubernetes, Apache OFBiz,
E-commerce Systems, ERP Systems, Cloud-Native Applications
