# Universe Css Helpers Class
A shortcuts for adding margins like mls = margin left small

## Installation

```sh
meteor add universe:css-helpers
```


## Shortcuts are made according following rules:

- mls = margin left small

- mts = margin top small

- mbm = margin bottom medium

- man = margin none

- mhm = margin horizontal medium

- mvs = margin vertical small

- mrt = margin right tiny

- ma = margin auto

- prl = padding right large

- pbs = padding bottom small

- tac = text align center

- tar = text align right

- tal = text align left

- fl = float left 

- fr = float right

### Customization
You can import it as a mixin and defined own spacing for: tiny, small, medium, large

```
@import "{universe:css-helpers}/shortClassesMixin.import.less";

.ui {
  .shortClasses(0.25rem, 0.5rem, 1rem, 2rem);
}
```