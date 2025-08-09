Chromakit
======
Chromakit is a Python module for modifying colors.

Features
------
- Color object
- Tools for modifying
- Displaying & Printing Tools too!

Availavable Formats
------
- RGB
- RGBA
- HSL

Quickstart
======
Making Colors
::
  import chromakit

  darkpink = chromakit.Color((231, 84, 128), "rgb")
  red = chromakit.PRESET_RED_RGB
Mixing Colors
::
  blue = chromakit.PRESET_BLUE_RGB
  new_color = chromakit.mix([darkpink, red, blue])
Changing Formats
::
  rgba = darkpink.to_rgba()
  hsl = darkpink.to_hsl()
Printing with color
::
  chromakit.colored("dark pink", darkpink, mode = "print")
  print(chromakit.colored("blue", blue))

Installation
======
terminal (Windows)
::
  py -m pip install chromakit
terminal (Linux/Mac)
::
  python3 -m pip install chromakit
