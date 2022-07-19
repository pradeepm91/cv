---
permalink: /
# title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Felipe B G Silva (PhD, Cornell University, ’2018) is an assistant professor, teaching the accounting and business strategy analysis capstone course of the School of Accountancy.

His research interests revolve around financial accounting, macroeconomics, banking and financial intermediation, and political economy. His work has been published in academic outlets such as the Journal of Financial and Quantitative Analysis, Journal of International Money, and Finance, Harvard Business Review, California Management Review, Annals of Finance, and Journal of Risk, and has been featured in the Washington Post, Bloomberg, and other media outlets in Chinese, English, Portuguese, German, and Russian.

Prior to his graduate studies, Professor Silva worked for 5 years in the private sector, including a brief career in the aerospace sector (Embraer) and later joining the financial services industry at Itaú Unibanco (Market Risk Division) and Banco Santander (Quantitative Researcher). He was also a founding partner of a start-up enterprise in the telecommunications sector, later sold to a major retailer. He holds a bachelor´s degree in Aeronautical Engineering from Instituto Tecnológico de Aeronáutica (ITA), Brazil, and an M.Eng. degree in Financial Engineering from Cornell´s Operations Research and Information Engineering Department. Outside of academia, Professor Silva enjoys spending time with his wife Anna and kids, Eric and George.

Publications
-======

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Working Papers
-======

{% include base_path %}


{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}


