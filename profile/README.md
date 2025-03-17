# Purpose

This is where all the website code is stored.

If I get round to rewriting / developing a aligner for the Northumberland then I might put it here as well.

# Repositories

- website: [https://github.com/cu-astronomical-society/website](https://github.com/cu-astronomical-society/website)

# Website (how it works)

The website is written on top of the [Astro](https://astro.build/) static site generator. This allows for relativly simple website generation now that it is set up.

Everytime there is a change to the main branch (note make edits to the dev branch, then merge to the main branch once happy), this is built by a [Github Action](https://github.com/withastro/action) into a static site.

The hosting is via [Github Pages](https://pages.github.com/), which serves the built static site.
