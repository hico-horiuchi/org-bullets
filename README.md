<h2>org-bullets mode</h2>
Show org-mode bullets as circle characters.

![screenshot](https://github.com/hico-horiuchi/org-bullets/raw/master/screenshot.png)

<h4>Installation</h4>
Copy the file somewhere in your load-path, then add to your .emacs:

    (require 'org-bullets)
    (add-hook 'org-mode-hook (lambda () (org-bullets-mode 1)))

select, do [M-x eval-region]. The *s will be replaced with circle bullets next time you open an org file

<h4>Replace bullets</h4>
When you replace bullets with circle, or circle to bullets:

    M-x org-bullets-replace
