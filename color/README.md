> Jim Carroll |
> 10/25/2020 |
> [GitHub Profile](https://github.com/pulamusic)

---

# a visual color palette

My own way to view a color palette during the dev process.

See if there is some way to create a ui for automatic viewing.

Check out [this site convertingcolors.com](https://convertingcolors.com/).

---

## atom-ui table of colors

#### Text Colors

| less variable | hsl color | rgb/rgba color | hex color |
| :--- | :--- | :--- | :--- |
| @text-color | hsl(0, 0%, 66%) | rgb(168, 168, 168) | #a8a8a8 |
| @text-color-subtle | hsl(0, 0%, 50%) | rgb(128, 128, 128) | #808080 |
| @text-color-highlight | hsl(0, 0%, 94%) | rgb(240, 240, 240) | #F0F0F0 |
| @text-color-selected | hsl(0, 0%, 100%) | rgb(255, 255, 255) | #FFFFFF |
| -- | -- | -- | -- |
| @text-color-info | hsl(219, 79%, 66%) | rgb(100, 148, 237) | #6494ED |
| @text-color-success | hsl(140, 44%, 62%) | rgb(115, 201, 144) | #73C990 |
| @text-color-warning | hsl(36, 60%, 72%) | rgb(226, 192, 141) | #E2C08D |
| @text-color-error | hsl(9, 100%, 64%) | rgb(255, 99, 71) | #FF6347 |

#### Background colors

| less variable | hsl color | rgb/rgba color | hex color | other |
| :--- | :--- | :--- | :--- | :--- |
| @background-color-info | hsl(208, 100%, 50%) | rgb(0, 136, 255) | #0088FF | -- |
| @background-color-success | hsl(160, 70%, 36%) | rgb(28, 156, 113) | #1C9C71 | -- |
| @background-color-warning | hsl(32, 60%, 50%) | rgb(204, 133, 51) | #CC8533 | -- |
| @background-color-error | hsl(0, 70%, 50%) | rgb(217, 38, 38) | #D92626 | -- |
| -- | -- | -- | -- | -- |
| @background-color-highlight | hsl() | rgba(53, 55, 59, 95%) | #____ | lighten(@base-background-color, 5%) |
| @background-color-selected | hsl() | rgba(53, 55, 59, 90%) | #____ | lighten(@base-background-color, 10%) |
| @app-background-color | hsl() | rgba(53, 55, 59, 105%) | #____ | darken(@base-background-color, 5%) |

#### Base colors

| less variable | hsl color | rgb/rgba color | hex color | other |
| :--- | :--- | :--- | :--- | :--- |
| @base-background-color | hsl(222, 6%, 22%) | rgb(53, 55, 59) | #35373B | -- |
| @base-border-color | hsl() | rgba(53, 55, 59, 108%) | #____ | darken(@base-background-color, 8%) |

#### Site colors

| less variable | hsl color | rgb/rgba color | hex color | other |
| :--- | :--- | :--- | :--- | :--- |
| @ui-site-color-1 | hsl(208, 100%, 50%) | rgb(0, 136, 255) | #0088FF | -- |
| @ui-site-color-2 | hsl(160, 70%, 42%) | rgb(32, 182, 132) | #20B684 | -- |
| @ui-site-color-3 | hsl(32, 60%, 50%) | rgb(204, 133, 51) | #CC8533 | -- |
| @ui-site-color-4 | hsl(314, 68%, 52%) | rgb(216, 49, 176) | #D831B0 | -- |
| @ui-site-color-5 | hsl(54, 78%, 64%) | rgb(235, 221, 91) | #EBDD5B | -- |

---
