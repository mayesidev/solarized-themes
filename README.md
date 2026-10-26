# Solarized Themes

Solarized theme variations for the software I use today, based on
[Ethan Schoonover's Solarized](https://ethanschoonover.com/solarized/).

The [original Solarized repository](https://github.com/altercation/solarized) has
not been updated in a long time. I started this repository to maintain and share
versions for applications I use that do not have their own native port, or where
existing ports are incomplete.

## My history with Solarized

Over 12 years ago, around early 2014, I was finishing college and entering the
world of professional software development. I wanted a theme that was easy on the
eyes without being strictly white text on a black background or black text on a
white background.

I had sporadically used [f.lux](https://justgetflux.com/) on my personal machines
and enjoyed the softer yellow tones it applied. But I did not enjoy having to turn
it on and off globally when using my PC for content where color mattered, such as
games and movies.

That search led me to Solarized. The configurations in the original repository
did not support the newer version of Visual Studio I was using for work. Luckily,
[leddt's Visual Studio port](https://github.com/leddt/visualstudio-colors-solarized/),
referenced by the main project, was up to date with newer Visual Studio versions.
I immediately imported it into my editor.

A few years later, I got a license for Visual Studio 2015 for work. Unfortunately,
the Visual Studio 2012 version of the theme did not import correctly because of a
major UI overhaul between Visual Studio 2013 and 2015. I took on the painstaking
task of manually porting the old configuration to the new version while keeping
it compatible with the repository's generator. I contributed that work in
[the pull request adding Visual Studio 2015 settings](https://github.com/leddt/visualstudio-colors-solarized/pull/34)
and contributed a few more times throughout the year to fix bugs I found.

Shortly afterward, I changed jobs and branched out from working in full Visual
Studio. Visual Studio Code was becoming a tool I used for editing other
languages, and it shipped with Solarized as a default theme!

Since then, I have regularly used other tools with built-in or community-maintained
Solarized variations. But as more development tools become available, I keep
finding incomplete theme ports. This repository is my place to track and maintain
variations for the tools I use that do not already have a suitable port.

## Building out this repository

This repository is just getting started. Application-specific themes and their
maintenance approach will be added as I identify the tools and versions to
support.

Applications use a wide range of configuration formats, and theme behavior often
cannot be fully verified outside the application itself. I expect to iterate and
troubleshoot each port in its target application. A single global linter or
formatter is unlikely to cover all of those formats, so validation and tooling
will be revisited as the collection grows.

See the [contribution guide](CONTRIBUTING.md) for theme requirements, commit
conventions, and how to report issues or propose changes.
