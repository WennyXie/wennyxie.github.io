<h2 id="publications" style="margin: 0; padding: 0;">Publications</h2>

<p style="margin: 0; padding: 0; font-style: italic;">* indicates equal contribution, bold text indicates corresponding authors.</p>

<div class="publications" style="margin: 0; padding: 0;">
<ol class="bibliography" style="margin: 0; padding: 0; list-style-position: inside;">

{% for link in site.data.publications.main %}
<li style="margin: 0; padding: 0;">
<div class="pub-row" style="margin: 0; padding: 0;">
  <div class="col-sm-9" style="margin: 0; padding: 0;">
      <div class="title" style="margin: 0; padding: 0;"><a href="{{ link.pdf }}">{{ link.title }}</a></div>
      <div class="author" style="margin: 0; padding: 0;">{{ link.authors }}</div>
      <div class="periodical" style="margin: 0; padding: 0;"><em>{{ link.conference }}</em></div>
    <div class="links" style="margin: 0; padding: 0;">
      {% if link.pdf %} 
      <a href="{{ link.pdf }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">PDF</a>
      {% endif %}
    </div>
  </div>
</div>
</li>
{% endfor %}

</ol>
</div>
