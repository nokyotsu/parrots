{%- extends "templates/base.html" -%}

{%- set page = {
  'title': 'Parrots, the Universe and Everything',
  'subtitle': 'Full Transcript',
  'sections': [
      'en/0_intro.md',
      'en/1_ayeaye.md',
      'en/2_komodo.md',
      'en/3_kakapo.md',
      'en/4_yangtze.md',
      'en/5_human.md',
      'en/6_questions.md',
  ]
} -%}

{%- block content -%}
This is one of the last public appearances of [[Douglas Adams]] in which he talks
about his book, [[Last Chance to See]], coauthored with [[Mark Carwardine]].
The talk was given at the University of California, Santa Barbara, and recorded
about a month before his death.

<iframe width="560" height="315" src="https://www.youtube.com/embed/_ZG8HBuDjgc" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Below you can find the full transcript in English---completed with the help of
many anonymous contributors---with links and a few extra notes.

With the help of many volunteers the transcript also has served as base to
create subtitles in English, Greek, Spanish and French. At amara.org you can
watch [the subtitled video][subtitled] and contribute providing translations
to other languages.

[subtitled]: https://amara.org/en/videos/yoedZnaqoAov/info/douglas-adams-parrots-the-universe-and-everything/

## Tanscript

{% for section in page.sections %}
  {% include section %}

{% endfor %}

(c) Copyright 2001. Regents of the University of California. All Rights
Reserved.
{%- endblock -%}
