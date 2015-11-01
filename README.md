# ac-capf.el [![melpa badge][melpa-badge]][melpa-link] [![melpa stable badge][melpa-stable-badge]][melpa-stable-link]

[auto-complete](https://github.com/auto-complete/auto-complete) source for `completion-at-point`.
Most code is taken from [company-mode](https://github.com/company-mode/company-mode).

This auto-complete source is useful in REPL buffer like `inferior-python-mode` etc.


## Screenshot

![ac-capf](image/ac-capf.png)


## Installation

`ac-capf` is available on [MELPA](https://melpa.org/) and [MELPA stable](https://stable.melpa.org/)

You can install `ac-capf` with the following command.

<kbd>M-x package-install [RET] ac-capf [RET]</kbd>


## Command

#### `ac-capf-setup`

Set up the auto-complete source and enable `auto-complete-mode`.


## Sample Configuration

```lisp
(add-hook 'inferior-python-mode-hook 'ac-capf-setup)
```

[melpa-link]: https://melpa.org/#/ac-capf
[melpa-stable-link]: https://stable.melpa.org/#/ac-capf
[melpa-badge]: https://melpa.org/packages/ac-capf-badge.svg
[melpa-stable-badge]: https://stable.melpa.org/packages/ac-capf-badge.svg
