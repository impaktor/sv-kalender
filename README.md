# sv-kalender
Swedish calendar in Emacs, fork from Daniel Jensen's official package [repository](http://bigwalter.net/daniel/elisp/sv-kalender.el) (broken link).


# Install

``` emacs-lisp
(use-package sv-kalender
  :ensure t)
```

# History

1.12 - Fixes for MELPA inclusion

1.11 - UTF-8, feature, fix warnings. (Arthur Miller)

1.10 - Fix abbrev names. (Thanks, Arthur Miller!)

1.9  - Update for Emacs 25

1.8  - Emacs 23 support. GPLv3.

1.6  - Lunar phase names, sunrise (månfasernas namn, soluppgång och -nedgång)

1.5  - Cleanup, introduce sv prefix (städning, nytt sv-prefix)

1.4  - Months and days use lower-case initials (månader och dagar med små begynnelsebokstäver)

1.3  - New flag days, Easter bug fixes (nya flaggdagar och en bugg i "mer påsk" fixad) (Alan Campbell)

1.2  - Advent Sundays fixed (adventsdagarna justerade) (Alan Campbell)

1.1  - Fat Tuesday moved back a week (fettisdagen flyttad en vecka bakåt).
