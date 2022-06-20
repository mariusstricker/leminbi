---
layout: page
title: Sammlung und Metadaten
permalink: /collection/
---

Die Sammlung umfasst 20 Glasdia, die in der Ansicht nach Farbkategorie respektive dem Label *Blütenlos* gefiltert werden können. Mit einem Klick auf die Glasdia öffnet sich ein Image Viewer ([OpenSeadragon](https://openseadragon.github.io/)). Unterhalb des Viewers befinden sich die Metadaten und Links zu den IIIF-Manifesten der Glasdias. Für eine vergleichende Bildanalyse mittels Image-API empfiehlt sich der [Mirador Viewer](https://projectmirador.org/), für Annotationen eignet sich [Annonatate](https://annonatate.herokuapp.com/) oder der IIIF-Manifest-Editor von [text&bytes](https://iiif-manifest-editor.textandbytes.com/) und [Bodleian](https://digital.bodleian.ox.ac.uk/manifest-editor). Über diesen Editor können IIIF-Manifeste auch lokal (localhost:3000[http://localhost:3000]) bearbeitet werden, eine Installation dafür befindet sich auf in diesem [GitHub-Repository](https://github.com/bodleian/iiif-manifest-editor/).


{% include collection_gallery.html collection='arumacula' facet_by='object_type' %}
