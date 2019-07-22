# Sass flexbox grid

super lightweight flexgrid with scss

also available at: https://www.npmjs.com/package/@clarklindeveloper/sass-flexbox-grid

preview: http://bit.ly/clarklindeveloper-sass-flexbox-grid

# Update 1.0.7

- added support for xxl - 1600
- summary of breakpoints <= 576, 577-767, 768-991, 992-1199, 1200-1599, > 1600
- use calling all between range col-xxl-1 col-xxl-12

# Update 1.0.6

- Adding alignment classes:
  - on the container: flex-direction, justify-content-, align-items-, align-content-,
  - on individual flex item: align-self-
  - changed container class default padding to gutter / 2

# Updates 1.0.5

- Tweak demo files and classes
- moved .container class to sass-flexbox-grid

# Updates 1.0.4

- changed package structure, moved sass-flexbox-grid.scss to root
- publishes production ready sass-flexbox-grid to build/sass-flexbox-grid.css
- ignore build/sass-flexbox-grid.css.map
- build/demo.css is only used for demo purposes and not required for production

- offsets do work but you have to reset every size that the offset in the previous media query size set an offset
- example (resetting the offset for the md and lg grid): sm-offset-2 md-offset-0 lg-offset-0
