---
layout: page
title: Registration
registration_state: open
---

{% case page.registration_state %}
{% when 'notyet' %}
<p class="message">Registration will be open soon.</p>

{% when 'closed' %}
<p class="message">Registration is closed.</p>

{% when 'open' %}
<p class="message">Registration is open.</p>

In order to participate in this meeting, please register with us, even if you only
wish to join for parts of the meeting. If you plan to not attend all five days of the whole week, 
simply indicate this in the questions/remarks field of the registration form.

<!--### Talks
We are looking for more talks, so please <a href="mailto:{{site.email}}">contact us via email</a> and let us know if you would like to give a talk about your research! We welcome talks about computational mathematics research, which utilised GAP.
-->

### Talks
We will have some slots for contributed talks. You can indicate through the
registration form whether you would like to give a short talk about your
research on computational mathematics using GAP! 

### Registration form
To register please fill out this [form](https://forms.gle/8DBk6ffBtwPcxK3d7). If you do not want to use the form software please send us an email.
<!-- To be announced. -->


### On funding
<!-- To be announced. -->
We have some limited funding to support travel and accommodation costs (partially or fully). 
If you would like to apply, please use the corresponding part of the registration form.

- Provide an estimate of how much support you expect to need (and for what); and
- Include a brief explanation of the aims you hope to achieve during
  your visit and, if applicable, whether and how your visit would be
  beneficial to the GAP system and community.

Initial decisions on whether we can grant support and how much will be made shortly after <b>31st&nbsp;July&nbsp;2026</b>.
<!-- The funding deadline has now passed. -->
<!-- We may be able to support later applications depending on the amount, so please don't hesitate to ask. -->
Later applications will be decided on a rolling basis if there are funds remaining.

### Questions?

<p>
If you have any questions
regarding registration, or in general, feel free to
<a href="mailto:{{site.email}}">contact us via email</a>.
</p>

{% endcase %}
