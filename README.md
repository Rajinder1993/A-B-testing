# A-B-testing

{% include 'query_string' %} in theme.liquid in <head> tag.
  
Place this condition on page where you want different design:
**Exp: collection page**
  
{% if pageUrl contains 'all-products?q=go' %}
{% section 'collection-template' %}
{% else %}
{% section 'collection-template' %}
{% endif %}
