## org-bullets mode
Show org-mode bullets as circle characters.

![screenshot](https://github.com/hico-horiuchi/org-bullets/raw/master/screenshot.png)

#### Installation
Copy the file somewhere in your load-path, then add to your .emacs:

    (require 'org-bullets)
    (add-hook 'org-mode-hook (lambda () (org-bullets-mode 1)))

select, do [M-x eval-region]. The *s will be replaced with circle bullets next time you open an org file

#### Export file
Replace org-bullets with circle and save file:

    M-x org-bullets-export

#### Import file
Insert file and replace circle with org-bullets:

    M-x org-bullets-import
