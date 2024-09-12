---
layout: default.liquid
title: Contributors
permalink: /contributors
---

# Contributors
This is the list of contributors who helped the game better.

Use the heading level 2 to move each category, such as translations and general credits. Use heading level 3 to move to each person or language file

## Translations
Since the game is multilingual, here is a list of languages available in the game. Do you want to help translate in your language? Refer to [this page](https://github.com/harrymkt/endless-battle) for help how to translate.

{%assign tr_author_prefix="Translated by"%}
{%assign tr_available_at_prefix="This translation is added to the game since"%}
{%assign tr_status_prefix="Translation status:"%}
There are {{site.data.langs | size}} approved languages available.

{% for language in site.data.langs %}
### {{language | map: "name"}} ({{language | map: "code"}}) {{language | map: "flag"}}
* {{tr_author_prefix}} {{language | map: "author"}}.
* {{tr_available_at_prefix}} {{language | map: "date"}}.
* {{tr_status_prefix}} {{language | map: "status"}}.
{% endfor %}