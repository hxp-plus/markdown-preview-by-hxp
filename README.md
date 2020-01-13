# markdown-preview-by-hxp #
 A markdown preview plugin for Emacs

---
## Installation ##
Put `markdown-preview.el` to your load path (i.e. `~/.emacs.d/lisp/`)

Add these in your `init.el`
```
(add-to-list 'load-path "~/.emacs.d/lisp/")
(require 'markdown-preview-by-hxp')
```
---

## Features ##
  * `C-c p` to preview markdown live in your web browser
  * The Emacs httpd server will be running automatically
  * Javascript and CSS are stored locally, no internet connection is required
  
---

## Precautions: Please Read Before Use ##
* **Does not Support** Mac OS
* **Do not close the web browser.** 
  * If you closed it by accident, re-open your web browser and visit [http://localhost:8080/imp](http://localhost:8080/imp)
