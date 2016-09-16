# direnv-el

Load [direnv](http://direnv.net) into the environment of an Emacs process.

Usage:

```elisp
(require 'direnv)
(add-hook 'find-file-hook 'direnv-load-environment)
```
