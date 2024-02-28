# Standard Themes

Standardized dark and light color themes.

## Preface

This' a specification for standardized light and dark color themes. While the design of the colors themselves is opinionated, the usage of the chosen colors is based in reason and practicality.

opinionated specification for standard light and dark color themes, designed with practical usage of color for enhanced user experience.

## Color Themes

### Dark

| Role                 | R   | G   | B   |
| -------------------- | --- | --- | --- |
| Primary Background   | 31  | 31  | 31  |
| Primary Foreground   | 220 | 220 | 220 |
| Secondary Background | 37  | 37  | 37  |
| Secondary Foreground | 255 | 251 | 255 |

## Usage & Reasoning

The below reasons for the design of the standard themes are reflected in Visual Studio Code's default dark theme which many people already stare at for hours per day.

<img alt="Visual Studio Code's standard dark theme." src="https://raw.githubusercontent.com/keisanng/standard-themes/main/src/Screenshot%202024-02-24%20132144.png" style="border-radius: .7rem">

### Background Scheme

The primary background color is designed for the main content the end user will view. It's darker than the secondary background color, which should be for any content which isn't the main content. The primary color should be darker than the secondary color so that the user can better focus your main content. Think of theatres; most having dimmed or no lighting at all while content is being shown.

### Foreground Scheme

The primary and secondary foreground colors are designed to contrast the primary and secondary background colors comfortably, with a contrast which isn't too heavy or to light. This' done with the user's eyes in concern, because too heavy of contrast will make the foreground hard to read and too light of a contrast will make the foreground hard to see - uncomfortable.

<p style="background-color: rgb(26, 26, 26); padding: 1ch; border-radius: .7rem;">
  <span style="color: white">
    This' hard to read.
  </span>
</p>

<p style="background-color: rgb(26, 26, 26); padding: 1ch; border-radius: .7rem;">
  <span style="color: rgb(220, 220, 220)">
    This' perfect.
  </span>
</p>

<p style="background-color: rgb(26, 26, 26); padding: 1ch; border-radius: .7rem;">
  <span style="color: gray">
    This' hard to see.
  </span>
</p>

## License

<p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/keisanng/standard-themes">Standard Themes</a> by <span property="cc:attributionName">Keisanng</span> is marked with <a href="http://creativecommons.org/publicdomain/zero/1.0?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC0 1.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/zero.svg?ref=chooser-v1"></a></p>
</p>
