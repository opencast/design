# Design of Opencast & related apps

This repository collects everything related to design in and around Opencast.


## Logo

The `logo/` folder contains different versions of the Opencast Logo:

- `opencast-logo-text.svg`: the "OPENCAST" text is an actual text object with the font "Segoe UI".
  The text is squished a bit on the x-axis, as the logo uses a slightly more condensed version of the font.
  This logo can be seen as the "source version", to allow for editing, but shouldn't be delivered to users.
  Without having the correct font installed, the logo will look wrong.
- `opencast-logo-paths.svg`: the text was converted to SVG paths, so the font is not needed anymore.
- `opencast-logo-paths-optimized.svg`: like the other `-paths`, but exported as "optimized SVG".


## Fonts

- The Opencast Logo uses "Segoe UI Bold" in a custom condensed form.
- The Admin UI uses "Open Sans".
- Tobira uses "Open Sans" by default, but it can be configured to any font.
- Studio and the Editor use "Roboto".


## Colors

- The Opencast Logo contains two colors: `#24425d` (blue) and `#4bb07b` (green).
- The Admin UI color palette is described [here](https://docs.opencast.org/r/12.x/developer/#modules/admin-ui/style/color-palette/).
- Common colors for Studio, Tobira, Editor are defined in [`appkit`](https://github.com/opencast/appkit).
