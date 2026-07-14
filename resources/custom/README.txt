Custom background images
========================

Select the "Custom" color scheme (UI Settings -> Theme color scheme) to use your
own background image per system instead of scraped media.

Drop an image here named after the system's ROMs folder (system.name), e.g.:

    snesna.png
    n64.png
    nds.png
    gba.png

Accepted extensions: .png, .jpg, .webp

Where it applies:
  - Carousel / List variants: used as the background in both the system and
    gamelist views.
  - Grid variant: used in the system view; the grid tiles themselves show
    screenshots.
  - Gallery variants: used in the system view; the gamelist keeps showing the
    selected game's media.

A system with no matching file falls back to its scraped screenshot background.
