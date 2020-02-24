+++
# Slider widget.
widget = "slider"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 2  # Order that this section will appear.

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = 3000

# Slide height (optional).
# E.g. `300px` for 500 pixels or `calc(100vh - 70px)` for full screen.
height = "500px"

# Slides.
# Duplicate an `[[item]]` block to add more slides.
[[item]]
  title = "DABIA"
  content = "Somos un centro dedicado al análisis de datos e inteligencia de negocios"
  align = "left"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  overlay_color = "#666"  # An HTML color value.
  overlay_img = "headers/bi.png"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.1  # Darken the image. Value in range 0-1.

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  cta_label = "Más acerca de nosotros"
  cta_url = "/nosotros"
  cta_icon_pack = ""
  cta_icon = ""

[[item]]
  title = "DATA"
  content = "Analizamos y sacamos provecho del nuevo petróleo del siglo XXI"
  align = "right"

  overlay_color = "#555"  # An HTML color value.
  overlay_img = "headers/data.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0  # Darken the image. Value in range 0-1.
  
  cta_label = "Más acerca de nosotros"
  cta_url = "/nosotros"
  cta_icon_pack = ""
  cta_icon = ""

+++
