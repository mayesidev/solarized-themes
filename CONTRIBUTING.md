# Contributing

Issues and pull requests are welcome. This repository maintains Solarized themes
for applications I use and can verify myself.

## Scope and maintenance

Use [GitHub Issues](https://github.com/mayesidev/solarized-themes/issues) to report
bugs, suggest improvements, or discuss a theme. You can also open a
[pull request](https://github.com/mayesidev/solarized-themes/pulls) directly; an
issue is not a prerequisite.

There are more applications than I can use or test. Please do not expect me to
support an application I do not use and cannot verify. Opening an issue or pull
request does not create a commitment to maintain that application here.

If your preferred application falls outside that scope, consider maintaining your
own Solarized port or collection of preferences, as I am doing with this
repository.

## Theme requirements

- **Provide both light and dark modes.** Use a combined definition with mode
  switching when the application supports it. Otherwise, provide separate,
  clearly named light and dark theme files.
- **Use the original Solarized palette.** Follow the color values and light/dark
  usage guidance in [Ethan Schoonover's original specification](https://ethanschoonover.com/solarized/).
  Keep theme colors within that palette rather than adding custom colors or
  modified shades.
- **Document compatibility and installation.** Identify the application and
  versions you tested, explain how to install the theme and select each mode,
  and describe any known limitations.
- **Preserve attribution.** Link to the sources of any theme files you adapt and
  retain their applicable license and copyright notices.

## Reporting issues

Include the application version, operating system, affected theme and mode,
steps to reproduce the problem, and the expected and actual behavior. Screenshots
are helpful for visual problems.

For a request involving another application, explain what is missing from its
existing Solarized support. The maintenance limits above still apply.

## Submitting changes

Keep each pull request focused on one concern. Explain what changed, why it is
needed, and how you verified it. Link any related issues.

For theme changes, install or import the files in the target application and check
both light and dark modes. Include the tested application version and operating
system, the steps you checked, and any behavior you could not verify. Add
screenshots when they help demonstrate the result.

Theme formats vary, and there is currently no repository-wide linter or formatter.
Follow the target application's format and any instructions provided alongside
the theme. Use available format or schema checks where applicable; those checks
complement testing in the application.

## Commit messages

Use [Conventional Commits 1.0.0](https://www.conventionalcommits.org/en/v1.0.0/)
for commit messages and pull request titles:

```text
<type>[optional scope][!]: <description>
```

Use `feat` for a new theme or capability, `fix` for a correction, `docs` for
documentation, and `chore` for repository maintenance. Other Conventional Commit
types may be used when appropriate. An optional scope can identify the affected
application or area. Keep the description concise and specific.

Examples:

```text
feat(editor): add Solarized light and dark themes
fix(editor): correct selection colors in dark mode
docs: clarify theme installation instructions
chore: update repository ignore rules
```

Mark breaking changes with `!` before the colon or a `BREAKING CHANGE:` footer.
Dropping a supported application version or changing installation in a way that
requires users to act is a breaking change. Explain the impact and migration
steps in the commit body or footer and in the pull request. Separate an optional
body and any footer from the preceding section with a blank line.
