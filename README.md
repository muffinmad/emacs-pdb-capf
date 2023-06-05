[![Stand With Ukraine](https://raw.githubusercontent.com/vshymanskyy/StandWithUkraine/main/banner2-direct.svg)](https://stand-with-ukraine.pp.ua)

[![License GPL 3](https://img.shields.io/badge/license-GPL_3-green.svg)](http://www.gnu.org/copyleft/gpl.html)
[![MELPA](http://melpa.org/packages/pdb-capf-badge.svg)](http://melpa.org/#/pdb-capf)
# emacs-pdb-capf
`completion-at-point` function for `pdb` (Python debugger)

## Usage

Enable pdb completions for specific modes by adding `pdb-capf` to `completion-at-point-functions`, e.g. (for GUD):

```elisp
(add-hook 'pdb-mode-hook
          (lambda ()
            (add-hook 'completion-at-point-functions
                      'pdb-capf nil t)))
```

## Screenshot

<p align="center">
  <img src="https://raw.githubusercontent.com/muffinmad/emacs-pdb-capf/master/screenshots/datetime-completions.png" width="640">
</p>
