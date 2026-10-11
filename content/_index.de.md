---
# Startseite (Deutsch). Leer lassen, um den Website-Titel zu verwenden.
title: ''
date: 2022-10-24
type: landing

design:
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: balanced
      avatar:
        size: medium
        shape: circle
  - block: markdown
    content:
      title: '🔍 Meine Forschung'
      subtitle: ''
      text: |-
        Meine Forschung bewegt sich an der Schnittstelle von politischer Soziologie und (digitaler) Medien- und Kommunikationswissenschaft. Ich arbeite mit Mixed Methods und interessiere mich besonders für Inhaltsanalyse (vor allem Textanalyse) und Netzwerkanalyse.

        Meine Dissertation, *Dynamics of Far-Right Transnationalization*, habe ich an der Scuola Normale Superiore in Florenz abgeschlossen.
    design:
      columns: '1'
  - block: collection
    content:
      title: '📚 Aktuelle Publikationen'
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
---
