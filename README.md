# Spotlight Extension For Quarto `revealjs` format

A plugin for [Reveal.js](https://github.com/hakimel/reveal.js) allowing to highlight the current mouse position with a spotlight.

## Installing

```bash
quarto install extension mcanouil/quarto-spotlight
```

This will install the extension under the `_extensions` subdirectory.
If you're using version control, you will want to check in this directory.

## Usage

Simply add the extension to the list of reveal plugins like:

```yaml
format:
  revealjs: default
  spotlight:
    # set pointer configuration options here
revealjs-plugins:
  - spotlight
```

## Options

You can control the appearance of the pointer by passing some additional options under a `spotlight` key.

| Option                       | Description                                                                                           |
| ---------------------------- | ----------------------------------------------------------------------------------------------------- |
| `size`                       | size of the spotlight. Default is `60`.                                                               |
| `lockPointerInsideCanvas`    | Locks the mouse pointer inside the presentation. Default is `false`.                                  |
| `toggleSpotlightOnMouseDown` | Toggle spotlight by holding down the mouse key. Default is `true`.                                    |
| `spotlightOnKeyPressAndHold` | The key code pressed and held to turn on spotlight, disabled when set to false. Default is `false`.   |
| `spotlightCursor`            | The cursor when spotlight is on. Can be "crosshair". Default is `none`.                               |
| `presentingCursor`           | The cursor when spotlight is off and in presentation mode. Can be "default". Default is `none`.       |
| `initialPresentationMode`    | Enable presentation mode, will also be true if toggleSpotlightOnMouseDown is true. Default is `true`. |
| `disablingUserSelect`        | Disable selecting in presentation mode. Default is `true`.                                            |
| `fadeInAndOut`               | Transition duration in ms to enable fade in and out, disabled when set to false. Default is `100`.    |
| `useAsPointer`               | Enable pointer mode. Default is `false`.                                                              |
| `pointerColor`               | Set pointer colour if pointer mode is enabled. Default is `red`.                                      |

## Example

Here is the source code for a minimal example: [example.qmd](example.qmd).  
View an example presentation at <https://m.canouil.fr/quarto-spotlight>.

---

[Spotlight - Reveal.js Plugin](https://github.com/denniskniep/reveal.js-plugin-spotlight) by Dennis Kniep under Apache License 2.0.
