Hugo In Action
===============

This code corresponds to section 2.3.3 of Hugo in Action.

You can see this live at https://ch02-4.hugoinaction.com.

Changes for hosting
--------------------

* The `.gitignore` file for this repository contains `resources` and `docs` folder.
  * Ideally the `resources` folder caches the assets preprocessed by Hugo and they belong with the code base. The folder may get large and blot the repository size which is not ideal for sample code.
  * If the desired host is GitHub Pages, then the `docs` folder also needs to pushed with the code. While we do generate it, the hosting for this code does not need that folder.
* `static/robots.txt` is present to disallow bots from tracking the branch. Needless links to subdomains with repeated code harm the search engine rankings of the website.

