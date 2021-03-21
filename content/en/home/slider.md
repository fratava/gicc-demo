---
widget: slider
headless: true  # This file represents a page section.

# ... Put Your Section Options Here (section position etc.) ...
weight: 10

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval: false

# Minimum slide height.
# Specify a height to ensure a consistent height for each slide.
height: 400px


item:
  - title: Modelos Numéricos
    content: 'Conoce los modelos numéricos pre-calculados que desarrollamos en GICC utilizando cómputo de alto rendimiento (HPC/Supercómputo).'
    # Choose `center`, `left`, or `right` alignment.
    align: center
    # Overlay a color or image (optional).
    #   Deactivate an option by commenting out the line, prefixing it with `#`.
    #overlay_color: '#666'  # An HTML color value.
    overlay_img: modelos.jpeg  # Image path relative to your `assets/media/` folder
    overlay_filter: 0.3  # Darken the image. Value in range 0-1.
    # Call to action button (optional).
    #   Activate the button by specifying a URL and button label below.
    #   Deactivate by commenting out parameters, prefixing lines with `#`.
    cta_label: Leer más
    cta_url: '/es/tag/modelos-numericos/'
    cta_icon_pack: fas
    cta_icon: book-open
  - title: Repositorio de Software
    content: 'Comienza a desarrollar y colaborar con nosotros en un click utilizando el protocolo git.'
    # Choose `center`, `left`, or `right` alignment.
    align: center
    # Overlay a color or image (optional).
    #   Deactivate an option by commenting out the line, prefixing it with `#`.
    #overlay_color: '#666'  # An HTML color value.
    overlay_img: repo.jpeg  # Image path relative to your `assets/media/` folder
    overlay_filter: 0.3  # Darken the image. Value in range 0-1.
    # Call to action button (optional).
    #   Activate the button by specifying a URL and button label below.
    #   Deactivate by commenting out parameters, prefixing lines with `#`.
    cta_label: Leer más
    cta_url: '/es/repository/'
    cta_icon_pack: fab
    cta_icon: git-alt
  - title: Seminarios
    content: 'En nuestro seminario quincenal en linea podras encontrar charlas de investigadores, profesores y estudiantes que te ayudaran a introducirte en el área del Cómputo Científico.'
    # Choose `center`, `left`, or `right` alignment.
    align: center
    # Overlay a color or image (optional).
    #   Deactivate an option by commenting out the line, prefixing it with `#`.
    #overlay_color: '#666'  # An HTML color value.
    overlay_img: seminarios.jpeg  # Image path relative to your `assets/media/` folder
    overlay_filter: 0.5  # Darken the image. Value in range 0-1.
    # Call to action button (optional).
    #   Activate the button by specifying a URL and button label below.
    #   Deactivate by commenting out parameters, prefixing lines with `#`.
    cta_label: Leer más
    cta_url: '/es/seminars/'
    cta_icon_pack: fas
    cta_icon: book-open
  #- title: Left
  #  align: left
  #  overlay_color: '#555'
  #  overlay_img: ''
  #  overlay_filter: 0.5
  #- title: Right
  #  align: right
  #  overlay_color: '#333'
  #  overlay_img: ''
  #  overlay_filter: 0.5
---