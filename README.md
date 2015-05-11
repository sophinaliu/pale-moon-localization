# pale-moon-localization
### Language packs for Pale Moon

This repository holds all of the langage pack files for the Pale Moon web browser.
Pale Moon can be found at http://www.palemoon.org/

This repository serves as the master version control repository for the language packs that are available for the browser.

If you want to contribute, please keep the following guidelines in mind:
* All language code directories (e.g. [en-US]) should contain *only* the files that should go into the language pack XPIs. If you have other files (e.g. reference files) that should be contained in this repo, please create a new directory that starts with the language code but has an extension .extra, e.g. [en-US.extra]
* The main translation system in use currently is Babelzilla (http://www.babelzilla.org) which may have more complete partial translations than present here. If you want to work on a language through this repo, get in touch with me to get an as-much spliced set of language pack files as possible. This has to be done manually at the moment.
* If you want to save splicing work, please check the /partial directory which has partially translated files as taken from Babelzilla, with untranslated strings replaced by their English counterpart. These are only available for previously actively translated languages, though.
* The browser name "Pale Moon" should always remain untranslated, in 2-word capitalized form.
* Other proper names (e.g. Moonchild Productions, Pale Moon Sync) should remain untranslated as well.
* Please always translate from the US-English language, which is the original source language. Do not use an already-translated other language as your source language, to prevent degradation of the translations due to limits in exactly matching vocabulary in different languages.
* Please keep the tone of your translations neutral and professional.
* Please mind the length of your translations. Many of these strings will be used in limited spaces in the browser's user interface.
* Before you create a submission or pull request, please test your translations by loading the language pack into the browser and verifying correctness.
