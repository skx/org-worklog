# org-worklog

This repository contains a single file, [template.org](template.org), which can be used to maintain a daily work-log via Emacs [org-mode](https://orgmode.org/).



## Features

The template is pretty minimal, but still useful despite that.  There is
automation in-place such that you can:

* Create a new entry at the start of every day.
  * By running `M-x new-day`.
* Jump to today's entry.
  * By running `M-x today`
* Automatically maintain a simple tag-cloud
  * A table collects all the unique tags seen in the document, and allows yo uto show matching entries.
* Reasonably nice formatting for HTML & PDF export.


## Dependencies

The integrated elisp is well documented, and would require a little effort to evaluate on-load.  That said there are no external dependencies.


## Bug Reports / Feature Requests

Feedback is welcome, just [report an issue](https://github.com/skx/org-worklog/issues).
