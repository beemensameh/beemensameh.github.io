<h1> Portfolio </h1>

## Experience
{% for job in site.jobs %}
<img src="{{ job.logo }}" height='56px'/>

### {{ job.title }}
_{{ job.name }} - {{ job.type }}_
<br>{{ job.from }} - {{ job.to }}

---
{% endfor %}
<br>
<br>

## Education
{% for education in site.educations %}
<img src="{{ education.logo }}" height='56px'/>

### {{ education.title }}
_{{ education.degree }}_
<br>{{ education.study }}
<br>{{ education.from }} - {{ education.to }}

---
{% endfor %}
