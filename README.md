<h3 align="center">Visual Studio Code Dark+ for Emacs</h3>
<hr/>


<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/08/EmacsIcon.svg/120px-EmacsIcon.svg.png" />
</p>

<p align="center">
<a href="https://github.com/ianpan870102/wilmersdorf-emacs-theme"><img src="https://img.shields.io/badge/Maintained%3F-yes-green.svg" alt="Maintenance"></a>
<a href="https://github.com/ianpan870102/vscode-dark-plus-emacs-theme"><img src="https://img.shields.io/github/release/ianpan870102/vscode-dark-plus-emacs-theme" alt="Version"></a>
<a href="https://www.gnu.org/licenses/gpl-3.0"><img src="https://img.shields.io/badge/License-GPL%20v3-blue.svg" alt="GPL License"></a>
</p>

<br/>

<p align="center">A complete port of the default Visual Studio Code Dark+ theme for Emacs</p>

<br/>

#### Introduction:

This theme aims to be **as identical as possible** to the default Dark+ color scheme used by Visual Studio Code. To see the original Visual Studio Code by Microsoft in action, consider [this YouTube video](https://www.youtube.com/watch?v=fnPhJHN0jTE).

If you find an inconsistency between Visual Studio Code's Dark+ and my port, please **file an issue** and I'll try my best to fix it.

#### Note:

This is the default Visual Studio Code Dark+ theme (the more **colorful** one), if you're looking for the **more minimal Dark** theme, it's [here](https://github.com/ianpan870102/vscode-dark-emacs-theme).


#### Installation Method 1: MELPA

WIP. My package is currently waiting for MELPA maintainers' review.


#### Installation Method 2: manual install

Download `vscode-dark-plus-theme.el` and put it under `~/.emacs.d/themes/` (or `~/.config/emacs/themes/`), then add these lines to your `init.el`:

```
(add-to-list 'custom-theme-load-path "~/.emacs.d/themes/")
# or
(add-to-list 'custom-theme-load-path "~/.config/emacs/themes/")

(load-theme 'vscode-dark-plus t)
```

#### Installation Method 3: `use-package` & `straight`

Requires [use-package](https://github.com/jwiegley/use-package) and [straight.el](https://github.com/raxod502/straight.el)
Add these lines to your 'init.el':
```
(use-package vscode-dark-plus-theme
  :straight (:host github :repo "ianpan870102/vscode-dark-plus-emacs-theme")
  :custom
  (add-to-list 'custom-theme-load-path "~/.emacs.d/straight/repos/vscode-dark-plus-emacs-theme/")
  (load-theme 'vscode-dark-plus t))
```

#### Screenshots of various modes

<!-- ![alt text](./screenshots/solaire.png) -->

<!-- ![alt text](./screenshots/posframe.png) -->

![alt text](./screenshots/jsx1.png)

![alt text](./screenshots/diff.png)

![alt text](./screenshots/cpp.png)

![alt text](./screenshots/html.png)

![alt text](./screenshots/jsx2.png)


Copyright© 2020 Ian Y.E. Pan

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program. If not, see https://www.gnu.org/licenses/.
