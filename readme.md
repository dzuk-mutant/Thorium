# Helium

Helium is an experimental, small Stylus framework designed for immersive, responsive web design.

Unlike other CSS frameworks, Helium is mostly just an array of prebuilt pieces to create standardised behaviours to build UI components off of. It doesn't presume or have at hand specific metaphors or UI elements.

To keep compiled CSS sizes down and because flexbox is a given, Helium intentionally doesn't support browsers that need flexbox prefixes or need older flexbox specs. This means it does not support any form of Internet Explorer.

If you want something more backwards compatible, looking for another CSS framework would probably be better for you.

----

## Helium in action

- [Parastat's website](https://parast.at)
- [Mutant Standard's website](https://mutant.tech)
- [My personal website](https://noct.zone)
- [instances.noct.zone](http://instances.noct.zone).


----

## Nice bits

- Lots of cute shortcuts to make prototyping interfaces using Flexbox much quicker and easier to understand.
- Shortcuts and fallbacks to make bidirectional design really simple.
- Tailored for smooth responsive design as opposed to web design focused around a fixed, snapping central column (although that's totally doable too).
- Made to reduce cognitive load when producing layouts by abstracting certain common positioning and sizing methods into single mixins/functions.

----

## How to use

Copy and paste the helium folder where you need it and then just import it in your styles (as one of the first imports). Then you can reference all of it's features in your style sheets!

```
@import 'helium'

```
----

## Docs

I keep Helium pretty well documented!

[You can read all of the documentation here.](docs/docs.md)


----

## Licenses and Credits

[Helium is licensed under the CNPLv4+ license](license.txt).
