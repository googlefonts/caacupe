## Setting up your font

### New repositories

1. Hit the green button above ("Use this template") to create your own repository.

2. Clone the repository, and replace the font sources in the `sources` directory with your own font sources. These sources may be either in Glyphs format or UFO/Designspace formats.\
   \
   Unlike many open source distributors, Google Fonts is **curated**. Fonts shipped to the platform have to match the [Google Fonts Specifications](https://github.com/googlefonts/gf-docs/tree/main/Spec). Please read them carefully.\
   \
   _(The sample font provided in this template is [Radio Canada](https://github.com/googlefonts/radiocanadadisplay/) by Charles Daoud, Etienne Aubert Bonn, Alexandre Saumier Demers and contributors.)_

3. Then reference the sources in the file `sources/config.yaml`, as well as making any other changes you would like to make based on the instructions in the [Google Fonts Builder documentation](https://github.com/googlefonts/gftools/blob/main/Lib/gftools/builder/__init__.py).

4. Add yourself to the `AUTHORS.txt` and `CONTRIBUTORS.txt` files.

5. Fill out `documentation/ARTICLE.en_us.html` with a description of your font.

6. Rewrite this Readme file according to the recommendations in the [Google Fonts Guide](https://googlefonts.github.io/gf-guide/readmefile.html).

7. Add and commit these files to git.

8. **At the command line, run `make customize` to ensure that all the paths and URLs in your project are correct**. This will also push your changes to GitHub.

9. **Set up your GitHub pages site**: go to your repository's Settings > Pages and ensure that the Build and deployment "Source" drop-down is set to "GitHub Actions". (Any preexisting Actions jobs can be re-run to publish now, or the deployment triggered also manually from the Actions tab. Subsequent commits will publish the proofs and QA results automatically.)

10. If GitHub Actions has successfully built the family, you will find the font binaries in the Actions tab. The official GitHub Actions documentation provides further [information](https://docs.github.com/en/actions/managing-workflow-runs/downloading-workflow-artifacts).

### Updating a repository

1. To update your font repository to bring in the latest best-practices from the Google Fonts Project Template, run `make update-project-template` from the command line. This requires the `node` Javascript engine to be installed; if you don't have that already, [follow these instructions](https://nodejs.org/en/download/package-manager#macos) to install on your platform.

2. To update the Python build chain which builds your fonts, run `make update` and `git add`/`git commit` the new `requirements.txt`.

## More things to do

- `CustomFilter_GF_Latin_All.plist` in `sources` is practical if you use GlyphsApp, you can remove it otherwise. Placed in the same directory as the your `.glyphs` file, it will allow Glyphs to display a filter list for all GF Latin glyphsets in app. To make sure your font supports the minimal set required by Google Fonts, look at the `GF_Latin_Core` filter list. Find other glyphsets and list formats for different software in [GF Glyphsets repository](https://github.com/googlefonts/glyphsets/tree/main/GF_glyphsets).

- Once you are happy with your font, add promotional assets in the documentation directory. Make it different from the pic you use in this README. You can get inspired by existing @googlefonts posts as: https://x.com/googlefonts/status/1415562928657416192.

- Google Fonts uses GitHub Releases to manage font families. If you feel your font project has hit a milestone, you must create a new release for it. In order to do this, go to the releases page and hit the "Draft a new release" button. You must provide a tag number and title which can only be a decimal number e.g. `0.100`, `1.000` etc. For the body text, mention what has changed since the last release. Once you are done, hit the "Publish release" button. Here is an example which fulfills the requirements, https://github.com/m4rc1e/test-ufr-family/releases/tag/2.019. For more info regarding GitHub release, please see the official GitHub Release [documentation](https://docs.github.com/en/repositories/releasing-projects-on-github/managing-releases-in-a-repository). **Please note that GitHub Actions must be able to build the fonts before you can make a release. Once you have made a release, the fonts and tests assets will be attached to the release automatically. This may take a while since the fonts and tests will be built from scratch so please be patient.**

---

# My Font

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

**29 June 2026**

- First public release of source files

## License

This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is available with a FAQ at https://openfontlicense.org

## Repository Layout

This font repository structure is inspired by [Unified Font Repository v0.3](https://github.com/unified-font-repository/Unified-Font-Repository), modified for the Google Fonts workflow.
