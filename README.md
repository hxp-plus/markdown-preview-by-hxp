# markdown-preview-by-hxp #
 A markdown preview plugin for Emacs

---
## Installation ##
Put `markdown-preview-by-hxp.el` in your load path (i.e. `~/.emacs.d/lisp/`)

Put `httpd` under `~/.emacs.d/`

Add these in your `init.el`
```
(add-to-list 'load-path "~/.emacs.d/lisp/")
(require 'markdown-preview-by-hxp')
```
---
### Chrome is required to preview###

#### Linux ####
* Make sure your command for chrome is `google-chrome-stable`

#### Windows 10 ####
* Make sure your chrome is installed in the default directory `C:/Program Files(x86)`


## Features ##
  * `C-c p` to preview markdown live in your web browser
  * The Emacs httpd server will be running automatically
  * Javascript and CSS are stored locally, no internet connection is required
  
---

## Precautions: Please Read Before Use ##
* **Does not Support** Mac OS
* **Do not close the web browser.** 
  * If you closed it by accident, re-open your web browser and visit [http://localhost:8080/imp](http://localhost:8080/imp)
