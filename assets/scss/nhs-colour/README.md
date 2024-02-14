# NHS Design Colours

Modelled on the Material Design Color library, but using the NHS colour palette
(and UK spellings where possible).

Because this is being grafted onto the Material Design scheme, we are going to
map the nearest NHS base colour to the existing Material colour name, and in the
theme palette will attempt to expose the original NHS name.

In doing so, we hope that every call to a specific Material colour will result
in a value being returned, but one that came from the NHS table, without
requiring us to override the entire style library.

This means that the mapping follows:

| Material Color   | NHS Colour                                                  |
| ---------------- | ----------------------------------------------------------- |
| $clr-red         | nhsRed                                                      |
| $clr-pink        | nhsPink                                                     |
| $clr-purple      | nhsDarkPink                                                 |
| $clr-deep-purple | nhsPurple                                                   |
| $clr-indigo      | nhsDarkBlue                                                 |
| $clr-blue        | nhsBlue                                                     |
| $clr-light-blue  | nhsBrightBlue                                               |
| $clr-cyan        | nhsLightBlue                                                |
| $clr-teal        | nhsAquaBlue                                                 |
| $clr-green       | nhsDarkGreen                                                |
| $clr-light-green | nhsGreen                                                    |
| $clr-lime        | nhsLightGreen                                               |
| $clr-yellow      | nhsYellow                                                   |
| $clr-amber       | nhsWarmYellow                                               |
| $clr-orange      | nhsOrange                                                   |
| $clr-deep-orange | The exception to the rule - there is no NHS near equivalent |
| $clr-brown       | nhsDarkRed                                                  |
| $clr-grey        | nhsMidGrey                                                  |
| $clr-blue-grey   | nhsDarkGrey                                                 |
| $clr-black       | nhsBlack                                                    |
| $clr-white       | nhsWhite                                                    |

In doing this table, we are skipping `nhsPaleGrey` and `nhsAquaGreen` as colour
choices based on least accessible and thus least likely to be used/missed.
