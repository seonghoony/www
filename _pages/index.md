---
layout: defaults/page
permalink: index.html
narrow: true
show_profile: true
title: Seonghoon Jeong, Ph.D.
---

<img alt="This is me; a moment with my wife, during a Busan trip on Christmas Eve, 2022." src="rsrc/image/2022-12-24-moment-on-busan-trip.jpeg" alt="Drawing" style="margin-left: 20px; width: 50%;" align="right"/>

From September 2024, I work at Division of Artificial Intelligence Engineering, Sookmyung Women's University (SMWU), Seoul, Republic of Korea, as an assistant professor.

# Research goal
I investigate and address cybersecurity challenges in Internet service applications through a data-driven approach that utilizes machine learning and deep learning methodologies. I have experience in analyzing a wide range of valuable datasets obtained from real-world services, including massive online game, root DNS servers, mobile payment transaction data, and car hacking activities.

Recently, my focus has been on in-vehicle anomaly and intrusion detection---a research area that demands urgent attention, given the severe consequences of compromised vehicle systems. Specifically, I have developed a standardized intrusion prevention system for connected vehicles that offers practical solutions to both industry professionals and academic researchers.

Now I'm dealing with an intrusion detection system that automatically interprets conducted attacks on automotive Ethernet.

# Education

* Ph.D., Information Security, Korea University, 2023 (Advisor: Prof. Huy Kang Kim)
* M.S., Information Security, Korea University, 2017 (Advisor: Prof. Huy Kang Kim)
* B.S., Information and Communication Engineering, Chungbuk National University, 2015 (Advisor: Prof. Min Choi)

# Publications
See more on my
[publications](./publications.html) page and
[Google Scholar profile](https://scholar.google.com/citations?user=9SOKjp4AAAAJ).


# Teaching

I have academic experience in teaching practical hacking and defense techniques, such as reverse engineering, system/network hacking, smart car hacking, and attack defense strategies (e.g., machine learning-based intrusion detection systems). I believe that it is essential to have an in-depth understanding of traditional computer science and engineering topics---including data structures, operating system concepts, system programming, data communications, and networking---so as to *really* understand security risks, threats, vulnerabilities, and proper countermeasures.

At SMWU, I previously taught Linux Administration and Security and Algorithms, and I am currently teaching Introduction to Computer Programming and Data-Driven Security.

See more on my [teaching page](./teaching.html).

# Schedule
<iframe src="https://calendar.google.com/calendar/embed?height=600&wkst=1&ctz=Asia%2FSeoul&bgcolor=%23ffffff&title=Schedule&showTitle=0&showPrint=0&mode=WEEK&showCalendars=0&hl=en&src=c2Vvbmdob29uQHNoamVvbmcubmV0&src=a28uc291dGhfa29yZWEjaG9saWRheUBncm91cC52LmNhbGVuZGFyLmdvb2dsZS5jb20&color=%230e61b9&color=%237CB342" style="border:solid 1px #777" width="800" height="600" frameborder="0" scrolling="no"></iframe>

<br>

<br>
# Recent posts

{% for post in site.posts limit:5 %}
{% include components/post-card.html %}
{% endfor %}
