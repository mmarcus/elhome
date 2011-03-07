# Elhome: an Emacs configuration framework

This is a copy of Dave Abrahams' Elhome emacs configuration
framework. The purpose of this fork is to point at a stable version
that I can use in my 'production' emacs environment. It points to my
[stable version of the el-get project](https://github.com/mmarcus/el-get),
as well. For more details, see
[the original documentation](https://github.com/dabrahams/elhome/blob/master/README.markdown).


## Installation

Evaluate this elisp.  You can copy it (to the clipboard or kill
ring such that ‘C-y’ will insert it) and then ‘M-: C-y RET’

     (url-retrieve
       "https://github.com/mmarcus/elhome/raw/master/elhome-install.el"
       (lambda (s) (end-of-buffer) (eval-print-last-sexp)))

## Congratulations, ELHOME is now installed!

There are several new directories you'll want to work with.  See the
README files in each one for more details:

* `~/.emacs.d/elhome/` - where everything related to this configuration is stored
* `~/.emacs.d/elhome/startup/` - elisp that is unconditionally loaded as
  early in startup as possible.
* `~/.emacs.d/elhome/settings/` - settings for specific modes, including
  the general customization file settings.el
* `~/.emacs.d/elhome/site-lisp/` - elisp files placed here (or in subdirectories) will be 
