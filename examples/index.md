---
layout: static
title: SILE Examples
---

<table class="examples">
{% tablerow example in site.data.examples.basic cols:3%}
    <a href="https://raw.githubusercontent.com/sile-typesetter/sile/master/examples/{{example.fn}}.png">
    <img src="https://raw.githubusercontent.com/sile-typesetter/sile/master/examples/{{example.fn}}.png">
    </a>
    <br/>
    <span class="title">{{example.title}}</span><br/>
    (<a href="https://raw.githubusercontent.com/sile-typesetter/sile/master/examples/{{example.source}}">source</a>)
    (<a href="https://raw.githubusercontent.com/sile-typesetter/sile/master/examples/{{example.fn}}.pdf">PDF</a>)
{% endtablerow %}
</table>
