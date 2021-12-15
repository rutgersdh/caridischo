---
layout: page
title: Open Data
permalink: /data/
---

Access to structured and semi-structured datasets that are well described and documented remains something of a challenge in music. Large-scale analysis of written and recorded music relies upon content-based approaches, and in order for these approaches to work, the music itself must be digital. To give an example, images of notated music need to be processed for pitch, rhythm, and other information using optical music recognition (OMR) technology. And for a variety of reasons, OMR is a more complex and therefore less reliably accurate process than optical character recognition (OCR). Manual correction, which is time consuming, is generally necessary. Another barrier is copyright and intellectual property. Many audio and score collections and databases are locked behind subscriptions and assume their users will approach them in the same way they have print: one item at a time. With the exception of a few public application programming interfaces (APIs), acquiring data from these sources may be costly and difficult, if not impossible.

As we began adding projects to our list, it became apparent that an open data category was critically needed. Here, you will find entries as wide-ranging as the KernScores repository with music encoded in the Humdrum format, the Linked Irish Traditional Music Ontology downloadable in the Web Ontology Language (OWL) format, and _Chant Turcs_ available as MusicXML. We would be remiss not to mention that several projects included in different genres, e.g. `edition` and `collections & exhibits`, also provide music corpora. Try using **Search**  with keywords like MEI, MusicXML, Humdrum, MIDI, RDF, etc., to locate them. Improving the discoverability of musical datasets is an important step for seeding future interdisciplinary research. 

---

In no particular order...

{% include collection_gallery.html  collection='musicdh' facet_by='musicdh_genre' only='data' %}
