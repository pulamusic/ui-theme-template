> Jim Carroll |
> 10/25/2020 |
> [GitHub Profile](https://github.com/pulamusic)

---

# notes

Notes on creating `atom-theme-pulamusic-ui`

---

Here is some text from the [Atom Flight Manual pages that describe setting up to create a UI theme](https://flight-manual.atom.io/hacking-atom/sections/creating-a-theme/#creating-a-ui-theme).

#### Creating a UI Theme

To create a UI theme, do the following:

* ~~Fork the `ui-theme-template`~~
* ~~Clone the forked repository to the local filesystem~~
* ~~Open a terminal in the forked theme's directory~~
* Open your new theme in a Dev Mode Atom window run `atom --dev .` in the terminal or use the *View > Developer > Open in Dev Mode* menu
  - I'm not striking this one out just now because it's an action I will have to run every time I work on the project.
* ~~Change the name of the theme in the theme's `package.json` file~~
* ~~Name your theme end with a `-ui`, for example `super-white-ui`~~
* ~~Run `apm link --dev` to symlink your repository to `~/.atom/dev/packages`~~
* ~~Reload Atom using *Alt+Cmd+Ctrl+L*~~
* ~~Enable the theme via the "UI Theme" drop-down in the "Themes" tab of the Settings View~~
* Make changes! Since you opened the theme in a Dev Mode window, changes will be instantly reflected in the editor without having to reload.

> *Tip*: Because we used `apm link --dev` in the above instructions, if you break anything you can always close Atom and launch Atom normally to force Atom to the default theme. This allows you to continue working on your theme even if something goes catastrophically wrong.
