# Caacupé

[![][Fontspector]](https://googlefonts.github.io/googlefonts-project-template/fontspector/fontspector-report.html)
[![][OpenType]](https://googlefonts.github.io/googlefonts-project-template/fontspector/fontspector-report.html)
[![][Universal]](https://googlefonts.github.io/googlefonts-project-template/fontspector/fontspector-report.html)
[![][Google Fonts]](https://googlefonts.github.io/googlefonts-project-template/fontspector/fontspector-report.html)
[![][Glyphset]](https://googlefonts.github.io/googlefonts-project-template/fontspector/fontspector-report.html)

[Fontspector]: https://img.shields.io/endpoint?url=https%3A%2F%2Fgooglefonts.github.io%2Fgooglefonts-project-template%2Fbadges%2FFontspectorQA.json
[OpenType]: https://img.shields.io/endpoint?url=https%3A%2F%2Fgooglefonts.github.io%2Fgooglefonts-project-template%2Fbadges%2FOpentypeSpecificationChecks.json
[Universal]: https://img.shields.io/endpoint?url=https%3A%2F%2Fgooglefonts.github.io%2Fgooglefonts-project-template%2Fbadges%2FUniversalProfileChecks.json
[Google Fonts]: https://img.shields.io/endpoint?url=https%3A%2F%2Fgooglefonts.github.io%2Fgooglefonts-project-template%2Fbadges%2FFontFileChecks.json
[Outline Correctness]: https://img.shields.io/endpoint?url=https%3A%2F%2Fgooglefonts.github.io%2Fgooglefonts-project-template%2Fbadges%2FOutlineCorrectnessChecks.json
[Glyphset]: https://img.shields.io/endpoint?url=https%3A%2F%2Fgooglefonts.github.io%2Fgooglefonts-project-template%2Fbadges%2FGlyphsetChecks.json

Caacupe began during my type design postgraduate program, born from observing the visual environment of Villa de Emergencia 21-24, an informal settlement in the Barracas neighborhood of Buenos Aires. It is a condensed, heavy display face, intended for headlines and short texts at large sizes. I wanted to translate two things from the neighborhood into type: the hand-painted, brush-lettered signage of its local shops, and the bold, high-impact graphic language of popular tabloid newspapers. That is why its terminals carry a subtle hint of the brush and its overall color is deliberately heavy.

One aspect is central to the project: Villa 21-24 is home to a large Paraguayan community, for whom Guaraní is a first or second language. I designed the typeface with that reality in mind, paying specific attention to the letters that appear most frequently in Guaraní (such as "y" and "v") and to the language's particular marks, so that text sets harmoniously. It also includes broad Latin coverage: the full Spanish set, extended Latin, currency symbols, fractions, mathematical signs, and ligatures. It was developed in Glyphs.

The typeface is currently complete in a single style that is visually a Bold weight. The project presentation ([Caacupe-Presentacion.pdf](/documentation/Caacupe-Presentacion.pdf)) documents the full process: research, sketches, the character set, the Guaraní development, and examples in use. It is currently in Spanish, but in brief it walks through how the neighborhood's painted street lettering and its Paraguayan and Guaraní community shaped each design decision.

The project vision is something I've seen for twenty years working with and alongside vulnerable communities: a quiet gap in design, communication and even public policy, where we solve problems for people whose context we never actually observe up close. The "from inside" rarely happens.

Caacupé came out of fieldwork, not taste. In 2014 I studied the three newspapers circulating in Villa 21-24. All were made by professionals, set in technically correct typefaces (Helvetica, Century, Zine Sans), and all were, in a way, culturally mute. The neighborhood spoke another visual language: walls painted by brush, letters working as images before they work as text, a logic shaped by readers living under daily urgency. Caacupé was designed from inside that context rather than toward it, and with Guaraní, a living language for tens of thousands of people there, treated as a first-class citizen rather than an afterthought.

That's the vision: not just a display face, but giving a more formal visual voice to expressions that rarely get one. There are very few typefaces born from situated research in an informal settlement, and fewer still available openly. I am very happy to see Caacupé is now one of them, and on Google Fonts licensed under the Open Font License.

Learn more in [Caacupe-Presentacion.pdf](/documentation/Caacupe-Presentacion.pdf)

## About

My name is Magdalena Alonso Rebollo. I'm a designer and art director based in Buenos Aires, Argentina, with fifteen years of experience and a postgraduate specialization in Type Design from the University of Buenos Aires. Much of my work has centered on visual communication for social causes and communities in vulnerable contexts: I currently work as a consultant for UNICEF, and previously led design and visual communication at IOM (UN Migration), alongside years of direct, on-the-ground work in low-income neighborhoods.

## Building

Fonts are built automatically by GitHub Actions — take a look in the "Actions" tab for the latest build.

If you want to build fonts manually on your own computer:

- `make build` will produce font files.
- `make test` will run [Fontspector](https://fonttools.github.io/fontspector/)'s quality assurance tests.
- `make proof` will generate HTML proof files.

The proof files and QA tests are also available automatically via GitHub Actions — look at `https://yourname.github.io/your-font-repository-name`.

## Changelog

When you update your font (new version or new release), please report all notable changes here, with a date.
[Font Versioning](https://github.com/googlefonts/gf-docs/tree/main/Spec#font-versioning) is based on semver.
Changelog example:

**1st July 2026**

- Fonts are now following GF specs

**29 June 2026**

- First public release of source files

## License

This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is available with a FAQ at https://openfontlicense.org

## Repository Layout

This font repository structure is inspired by [Unified Font Repository v0.3](https://github.com/unified-font-repository/Unified-Font-Repository), modified for the Google Fonts workflow.
