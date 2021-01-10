---
layout: page
title: Donate
permalink: /donation/
---

We are a nonprofit open-source project. You can help by buying us a coffee or pizza for contributors or to our budget to pay someone to improve our codebase. Currently, we accept PayPal (BRL/USD).

{% for donation in site.donations %}
<table>
    <thead>
        <tr>
        {% for value in donation[1] %}
            {% if value == 'custom' %}
            <th>Any Value ({{ donation[0] }})</th>
            {% else %}
            <th>{{ value }} {{ donation[0] }}</th>
            {% endif %}
        {% endfor %}
        </tr>
    </thead>

    <tr align="center">
        {% for value in donation[1] %}
        <td>
            <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
                <input type="hidden" name="cmd" value="_donations" />
                <input type="hidden" name="business" value="RUSTZRBUEXK82" />
                <input type="hidden" name="item_name" value="OpenTibiaBR Project" />
                <input type="hidden" name="currency_code" value="{{ donation[0] }}" />
                {% if value != 'custom' %}
                <input type="hidden" name="amount" value="{{ value }}" />
                {% endif %}
                <input type="image" src="https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif" border="0" name="submit" title="PayPal - The safer, easier way to pay online!" alt="Donate with PayPal button" />
                <img alt="" border="0" src="https://www.paypal.com/en_US/i/scr/pixel.gif" width="1" height="1" />
            </form>
        </td>
        {% endfor %}
    </tr>
</table>
{% endfor %}
