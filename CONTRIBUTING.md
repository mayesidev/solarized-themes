# Contributing

Open a [GitHub Issue](https://github.com/mayesidev/solarized-themes/issues) or
[pull request](https://github.com/mayesidev/solarized-themes/pulls) to report a bug,
suggest an improvement, or contribute a theme.

This collection focuses on applications I use and can verify. Please do not
expect me to support applications I do not use and cannot test. Consider
maintaining your own Solarized port or collection of preferences for those tools,
as I am doing with this repository.

## Theme requirements

- **Provide both light and dark modes.** Use a combined definition with mode
  switching when the application supports it. Otherwise, provide separate,
  clearly named light and dark theme files.
- **Use the original Solarized palette.** Follow the color values and light/dark
  usage guidance in [Ethan Schoonover's original specification](https://ethanschoonover.com/solarized/).
- **Document compatibility and installation.** Identify the application, explain
  how to install the theme and select each mode, and describe known limitations.
  Include version or operating-system details when they affect compatibility.
- **Preserve attribution.** Link to the sources of any theme files you adapt and
  retain their applicable license and copyright notices.

## Issues and pull requests

For bug reports, include the affected mode and steps to reproduce the problem.
Include the application version and operating system when relevant to reproduction.
Screenshots are helpful for visual issues.

Keep pull requests focused. Test theme changes in both modes in the target
application, and describe what you checked and anything you could not verify.

Use [Conventional Commits 1.0.0](https://www.conventionalcommits.org/en/v1.0.0/)
for commit messages and pull request titles. Identify compatibility breaks, such
as dropping support for an application version, and explain any migration steps.
