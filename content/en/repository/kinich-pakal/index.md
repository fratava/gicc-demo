---
title: KINICH PAKAL
summary: Atmósferas estelares en estrellas de tipo solar a longitudes de onda milimétricas y submilimétricas.
tags:
- Astrofísica
- Radioastronomía
- Modelos Numéricos
date: "2016-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: F. Tapia-Vázquez & De la Luz, 2020
  focal_point: Smart

links:
- icon: graduation-cap
  icon_pack: fas
  name: ADS
  url: https://ui.adsabs.harvard.edu/abs/2020ApJS..246....5T/abstract
- icon: github
  icon_pack: fab
  name: Code
  url: https://ui.adsabs.harvard.edu/abs/2011ApJ...737....1D/abstract
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

authors:
- ftapia
- vdelaluz
---

{{< icon name="code-branch" pack="fas" >}} Versión: Release 1

## Descripción

Hemos desarrollado el código KINICH-PAKAL (Tapia-Vázquez, & De la Luz 2020) [^3] que utiliza el algoritmo Levenberg-Marquard como método de ajuste no lineal, PAKAL-MPI como modelo cromosférico de la atmósfera solar y observaciones en longitudes de onda que van desde el infrarrojo al milímetro para generar un modelo más preciso de las cromosferas de las estrellas de tipo solar.
KINICH-PAKAL nos ha permitido estudiar en detalle cómo cambian las condiciones físicas de la atmósfera en función de su temperatura efectiva.
El desarrollo de estos modelos es necesario para estudios de discos de escombros (White et al. 2018) [^4], estudiar las condiciones bajo las cuales se forman las erupciones (MacGregor et al. 2018) [^2] y los posibles mecanismos físicos de variaciones de flujo en el estrellas (Liseau 2019) [^1].

### Referencias

[^1]: Liseau, R. 2019, arXiv:1904.03043.
[^2]: MacGregor, M. A., Weinberger, A. J., Wilner, D. J., Kowalski, A. F., & Cranmer, S. R. 2018, ApJ, 855, L2.
[^3]: Tapia-Vázquez, F., & De la Luz, V. 2020, ApJS, 246, 5.
[^4]: White, J.A., Aufdenberg, J., Boley, A.C., 2018, ApJ,859(2), p.102.
