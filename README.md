# direnv-el

Load [direnv](http://direnv.net) into the environment of an Emacs process.

Usage:

```elisp
(require 'direnv)
(add-hook 'find-file-hook 'direnv-load-environment)
(add-hook 'buffer-list-update-hook 'direnv-load-environment)
```

Emacs's environment will then be changed every time you enter or leave a
buffer that's inside a direnv-controlled directory.
