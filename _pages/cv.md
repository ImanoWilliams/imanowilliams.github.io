---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D. in Computer Science, North Carolina A&T State University, 2020 (expected)
* M.S. in Computer Science, North Carolina A&T State University, 2015
* B.Sc. in Computer Science & Electronics (Double Major), The University of The West Indies – Mona Campus, 2012

Work experience
======
* Summer Graduate Research Intern, IBM Research – Almaden, CA             [05/2019 to 08/2019]
  * Used LSTM to detect ransomware based on time-series meta-data from user file
  * Started a process to synthesize user file activities to model the specific user file meta-data
* Associate Security Consultant, Cigital – Sterling, VA 						      [02/2016 – 05/2016]
  * Performed manual and automated penetration testing on web applications using Burp Suite
  * Triaged defects and removed false positives during static source code analysis
* SOA Developer Summer Intern, Bank of America Merrill Lynch – Jersey City, NJ 		[06/2015 – 08/2015]
  * Evaluated the pros and cons for the developing the Service Oriented Architecture (SOA) using MuleSoft
  * Implemented a reusable Authentication SOA solution using MuleSoft, Web Services and Java
* Junior Software QA Engineer, Transcel Ltd – St. Andrew, Jamaica 				[03/2013 – 07/2014]
  * Excelled in discovering and reporting software defects in a financial mobile application
  * Performed manual testing on Android, Blackberry and J2ME mobile application versions

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
