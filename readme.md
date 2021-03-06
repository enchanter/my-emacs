<div id="table-of-contents">
<h2>Table of Contents</h2>
<div id="text-table-of-contents">
<ul>
<li><a href="#sec-1">Motivation</a></li>
<li><a href="#sec-2">Requirements</a></li>
<li><a href="#sec-3">Bootstrapping</a>
<ul>
<li><a href="#sec-3-1">emacs entry points</a></li>
</ul>
</li>
<li><a href="#sec-4">Initialization configurations</a>
<ul>
<li><a href="#sec-4-1">Packaging manager configurations</a></li>
<li><a href="#sec-4-2">El-get configurations</a></li>
</ul>
</li>
<li><a href="#sec-5">Emacs encoding</a></li>
<li><a href="#sec-6">Setting key layout</a></li>
<li><a href="#sec-7">Visual appearance</a>
<ul>
<li><a href="#sec-7-1">Default frame</a></li>
<li><a href="#sec-7-2">Frame fixing function</a></li>
<li><a href="#sec-7-3">Set font for all</a></li>
</ul>
</li>
<li><a href="#sec-8">Navigation</a>
<ul>
<li><a href="#sec-8-1">smex</a></li>
<li><a href="#sec-8-2">Bookmarks</a></li>
<li><a href="#sec-8-3">ELScreen</a></li>
<li><a href="#sec-8-4">Window layout navigator</a></li>
<li><a href="#sec-8-5">Trivial modes</a></li>
<li><a href="#sec-8-6">Tramp</a></li>
</ul>
</li>
<li><a href="#sec-9">Editing</a>
<ul>
<li><a href="#sec-9-1">Killring modifications.</a></li>
<li><a href="#sec-9-2">yasnippet</a></li>
<li><a href="#sec-9-3">Custom tools</a>
<ul>
<li><a href="#sec-9-3-1">Count words</a></li>
<li><a href="#sec-9-3-2">wc</a></li>
<li><a href="#sec-9-3-3">buffer to PDF</a></li>
</ul>
</li>
</ul>
</li>
<li><a href="#sec-10">Buffers</a>
<ul>
<li><a href="#sec-10-1">iBuffer filters and grouping</a>
<ul>
<li><a href="#sec-10-1-1">Filters</a></li>
<li><a href="#sec-10-1-2">Filter Views</a></li>
</ul>
</li>
<li><a href="#sec-10-2">Save</a></li>
<li><a href="#sec-10-3">Automatic Cleaning</a></li>
<li><a href="#sec-10-4">IDO mode</a></li>
<li><a href="#sec-10-5">Buffer renaming</a></li>
</ul>
</li>
<li><a href="#sec-11">Org-mode</a>
<ul>
<li><a href="#sec-11-1">el-get recipe definition</a></li>
<li><a href="#sec-11-2">Agenda</a>
<ul>
<li><a href="#sec-11-2-1">To do flow in tasks</a></li>
<li><a href="#sec-11-2-2">Time and date</a></li>
<li><a href="#sec-11-2-3">Icalendar Exporting</a></li>
</ul>
</li>
<li><a href="#sec-11-3">Babel</a></li>
<li><a href="#sec-11-4">Block Wrapping function</a></li>
<li><a href="#sec-11-5">Buffer Encryptions</a></li>
<li><a href="#sec-11-6">Column mode</a>
<ul>
<li><a href="#sec-11-6-1">Font change prevention</a></li>
</ul>
</li>
<li><a href="#sec-11-7">Exporting</a>
<ul>
<li><a href="#sec-11-7-1">Latex</a></li>
</ul>
</li>
<li><a href="#sec-11-8">Global keybindings</a></li>
<li><a href="#sec-11-9">Headline Editing</a>
<ul>
<li><a href="#sec-11-9-1">Remember and capture</a></li>
</ul>
</li>
<li><a href="#sec-11-10">Hooks</a></li>
<li><a href="#sec-11-11">Images in Buffers</a></li>
<li><a href="#sec-11-12">Linking</a></li>
<li><a href="#sec-11-13">Mobile-org</a></li>
<li><a href="#sec-11-14">Tags</a></li>
</ul>
</li>
<li><a href="#sec-12">ERC-client</a>
<ul>
<li><a href="#sec-12-1">Bouncer and Identification</a>
<ul>
<li><a href="#sec-12-1-1">Login proxies</a></li>
</ul>
</li>
<li><a href="#sec-12-2">IRC custom commands</a></li>
</ul>
</li>
<li><a href="#sec-13">Programming</a>
<ul>
<li><a href="#sec-13-1">Compilation shell output</a></li>
<li><a href="#sec-13-2">Folding mode</a></li>
<li><a href="#sec-13-3">C</a></li>
<li><a href="#sec-13-4">Fortran F90</a></li>
<li><a href="#sec-13-5">XREF</a></li>
<li><a href="#sec-13-6">JDEE</a></li>
<li><a href="#sec-13-7">Maven</a></li>
<li><a href="#sec-13-8">Sage</a></li>
<li><a href="#sec-13-9">Ruby</a></li>
<li><a href="#sec-13-10">Php</a></li>
<li><a href="#sec-13-11">IDL</a></li>
<li><a href="#sec-13-12">Groovy</a></li>
<li><a href="#sec-13-13">Promela</a></li>
<li><a href="#sec-13-14">javascript</a></li>
<li><a href="#sec-13-15">Slime</a></li>
</ul>
</li>
<li><a href="#sec-14">Browsers</a>
<ul>
<li><a href="#sec-14-1">The custom search URLs</a></li>
</ul>
</li>
<li><a href="#sec-15">ElNode</a>
<ul>
<li><a href="#sec-15-1">Utility tools</a></li>
<li><a href="#sec-15-2">Services</a>
<ul>
<li><a href="#sec-15-2-1">Simple Example service</a></li>
<li><a href="#sec-15-2-2">Complex Example service</a></li>
</ul>
</li>
</ul>
</li>
<li><a href="#sec-16">Consoles</a>
<ul>
<li><a href="#sec-16-1">SQL</a>
<ul>
<li><a href="#sec-16-1-1">Keybinding</a></li>
<li><a href="#sec-16-1-2">Hooks</a></li>
</ul>
</li>
<li><a href="#sec-16-2">Multiterm</a></li>
<li><a href="#sec-16-3">eshell</a></li>
<li><a href="#sec-16-4">git</a>
<ul>
<li><a href="#sec-16-4-1">magit Configuration</a></li>
<li><a href="#sec-16-4-2">git-gutter</a></li>
</ul>
</li>
<li><a href="#sec-16-5">Bash-shell</a>
<ul>
<li><a href="#sec-16-5-1">Keybinding</a></li>
<li><a href="#sec-16-5-2">Other</a></li>
</ul>
</li>
</ul>
</li>
<li><a href="#sec-17">Emacs customization</a></li>
<li><a href="#sec-18">Loading of different aspects</a>
<ul>
<li><a href="#sec-18-1">syncing el-get packages</a></li>
</ul>
</li>
<li><a href="#sec-19">License</a></li>
</ul>
</div>
</div>

# Motivation

Tired to have to copy and reinitialize my emacs environment
everywhere. Therefore I figured that it might be fun exercise to
bootstrap my emacs(-configuration) so that it manages itself all
related packages and dependencies.

For this purpose I use org-mode format to store and organize my
configuration code and el-get to manage actual fetching, loading and
updating of my packages.

# Requirements

Currently this is running in ubuntu 12.04, GNU Emacs 24.1.1
(x86<sub>64</sub>-pc-linux-gnu, GTK+ Version 2.24.10) of 2012-07-17 on
lawrencium, modified by Debian and Org-mode version 7.8.02. I have
had some org-mode related problems with newer org-mode version such
as 7.9.1 and 7.8.11.

# Bootstrapping

Here are utility scripts that help initialize emacs to vanilla
environment. Currently I'm only interested in ubuntu environments
(currently about 12.04).

    echo "bootstarpping emacs 24.1 repositories and installing packages ..."
    sudo add-apt-repository ppa:cassou/emacs 
    sudo apt-get update
    sudo apt-get purge emacs-snapshot-common emacs-snapshot-bin-common emacs-snapshot emacs-snapshot-el emacs-snapshot-gtk emacs23 emacs23-bin-common emacs23-common emacs23-el emacs23-nox emacs23-lucid auctex emacs24 emacs24-bin-common emacs24-common
    sudo apt-get install emacs24 emacs24-el
    
    echo "installing auxialiry debian packages (currently not using el-get to do this)..."
    sudo apt-get install bzr ess r-base git-svn

Here is a little script that helps you to set the repo to be your
.emacs.d.

    echo "replacing emacs configuration points in your system, backuping originals..."
    ln -svb $PWD ~/.emacs.d
    ln -svb ~/.emacs.d/personal/.emacs-custom.el ~/.emacs-custom.el

## emacs entry points

Environmental file to be sourced so that emacs can be accessed as painlessly as
possible from terminal.

    # -*- mode: shell-script; -*-
    echo "setting emacs environments..."
    
    VISUAL="emacsclient -c"
    EDITOR="emacsclient -c"
    export VISUAL;
    export EDITOR;
    
    alias mt="emacsclient -t"
    alias m="emacsclient -c"

# Initialization configurations

[All begans here.](init.el) This approach was inspired from documentation of
org-mode babel library. I use demonized version of the emacs so that
it only does source tangling and loading of this configuration once.

    (defvar personal-directory)
    (setq personal-directory "~/.emacs.d/personal/")
    
    (defun personal-place (suffix)
      (concat personal-directory suffix))
    
    (setq user-full-name "Sami Airaksinen"
          user-email "samiaira@gmail.com")
    
    (add-to-list 'load-path "~/.emacs.d/lib")
    (add-to-list 'load-path "~/.emacs.d/personal")

## Packaging manager configurations

I would like have stuff from MELPA

    (require 'package)
    (setq package-archives '(
                              ("melpa" . "http://melpa.milkbox.net/packages/")
                              ("marmalade" . "http://marmalade-repo.org/packages/")))
    (package-initialize)

## El-get configurations

Bootstrapping el-get to my emacs initialization file. Actual
recipes and el-get lisp files are located in separate git repo as
sub repo (they are not a same context in my opinion).

    (add-to-list 'load-path "~/.emacs.d/el-get/el-get")
    
    (unless (require 'el-get nil 'noerror)
      (with-current-buffer
          (url-retrieve-synchronously
           "https://raw.github.com/dimitri/el-get/master/el-get-install.el")
        (goto-char (point-max))
        (eval-print-last-sexp)))
    
    (add-to-list 'el-get-recipe-path "~/.emacs.d/el-get-user/recipes")
    
    (defmacro add-to-el-sources(name type after-progn &rest additional)
      `(add-to-list
          'el-get-sources
          (append '(:name ,name :type ,type :after ,after-progn) ',additional)))

# Emacs encoding


Setting emacs encoding to get correct characters *(reason: maybe some old
char bug&#x2026;)*.

    (load-library "iso-transl")
    
    (setq
     current-language-environment "UTF-8"
     default-input-method "rfc1345")    

# Setting key layout


Load ErgoEmacs keybinding and turn the minor mode to be always
on. This is a sub module in my emacs configrations, see more details
about this mode from, <https://code.google.com/p/ergoemacs/>

    (add-to-list
     'el-get-sources
     '(:name ergoemacs-keybindings
             :before ;;this is here because keybindings doesn't require log-edit itself
             (progn
               (require 'log-edit))
             :after 
             (progn
               (setq ergoemacs-variant nil)
               (ergoemacs-mode 1)
               (global-set-key (kbd "C-<f5>") 'toggle-truncate-lines)
               (global-set-key (kbd "M-<f5>") 'revert-buffer)
               (global-set-key (kbd "C-S-o") 'dired)
               )))

# Visual appearance


    ;;; appearance.el --- Visual customization and fixes for bugs
    (setq 
     inhibit-startup-screen t
     initial-buffer-choice t
     use-file-dialog nil
     frame-title-format '(buffer-file-name "Emacs: %b (%f)" "Emacs: %b"))
    
    (set-face-attribute 'default nil :height 100 :family "Liberation Mono")
    (show-paren-mode t)
    (column-number-mode t)
    (tool-bar-mode -1)
    
    (add-to-list 'custom-theme-load-path "~/.emacs.d/themes/ujelly")
    (load-theme 'ujelly t)
    
    ;; fixing tool-bar-mode bug in daemon...
    (add-hook 'before-make-frame-hook '(lambda () (tool-bar-mode -1)))

## Default frame


This is the configuration creates 80x50 frame in the current
desktop. It sets colors of cursor, background and foreground. Also
font is redefined here. Fixes some of the daemon issues.

    (setq default-frame-alist
        '((width . 80) (height . 50)
          (cursor-color . "red")
          (foreground-color . "AntiqueWhite2")
          (background-color . "black")
          (vertical-scroll-bars)
          (font . "-raster-Liberation Mono-medium-r-normal-*-*-100-*-*-*-*-*-1")))

## Frame fixing function


Function to reset frame to prefixed size.

    (global-set-key (kbd "C-x W") 'fix-horizontal-size)
    
    (defun fix-frame-horizontal-size (width)
      "Set the frame's size to 80 (or prefix arg WIDTH) columns wide."
      (interactive "P")
      (if window-system
          (set-frame-width (selected-frame) (or width 80))
        (error "Cannot resize frame horizontally: is a text terminal")))
    
    ;; functions to fix buffer window to fixed size
    (defun fix-window-horizontal-size (width)
      "Set the window's size to 80 (or prefix arg WIDTH) columns wide."
      (interactive "P")
      (enlarge-window (- (or width 80) (window-width)) 'horizontal))
    
    ;; actual function to be called
    (defun fix-horizontal-size (width)
      "Set the window's or frame's width to 80 (or prefix arg WIDTH)."
      (interactive "P")
      (condition-case nil
          (fix-window-horizontal-size width)
        (error 
         (condition-case nil
             (fix-frame-horizontal-size width)
           (error
            (error "Cannot resize window or frame horizontally"))))))
    
    ;; modularize this to loadable module
    (provide 'appearance)

## Set font for all

# Navigation


Defining navigation preferences. I want easy navigation between
screens and my mouse cursor to follow wheel motions.

    ;;; navigation.el --- navigation modes and customization for them
    
    ;;moving between windows easily
    (when (fboundp 'windmove-default-keybindings)
      (windmove-default-keybindings))
    
    (setq mouse-wheel-follow-mouse t)
    
    (add-to-list
     'el-get-sources
     '(:name saveplace :type builtin :features saveplace 
            :after 
            (progn
              (setq-default save-place t)
              )))

## smex

Smex is ido for M-x.

    (add-to-el-sources 
     smex 
     elpa 
     (progn
       (require 'smex)
       (smex-initialize)
       (setq smex-save-file (personal-place "smex.save"))
       (global-set-key (kbd "M-C-a") 'smex) ;;todo to M-a, replace ergoemacs keybinding
       (global-set-key (kbd "M-C-S-a") 'smex-major-mode-commands)
       ))

## Bookmarks

Keeping my personal information in one location. 

    (setq 
     bookmark-default-file (concat personal-directory "bookmarks")
     bookmark-save-flag 1)

## ELScreen


Elscreen is like screen for emacs. Installed via system tool
apt-get, so you need sudo rights. It can be passed as $pass env
variable, but might be little bit unreliable.

    (add-to-list
     'el-get-sources
     '(:name elscreen :type apt-get
             :after (progn
                      (global-set-key (kbd "<s-prior>") 'elscreen-previous)
                      (global-set-key (kbd "<s-next>")  'elscreen-next)
                      )))

## Window layout navigator

Configuring winner mode. With this you can search through your
previous window layouts.

    (add-to-list
     'el-get-sources
     '(:name winner :type builtin :features winner
             :after (progn
                      (setq winner-dont-bind-my-keys t) 
                      (global-set-key (kbd "<C-s-left>") 'winner-undo)
                      (global-set-key (kbd "<C-s-right>") 'winner-redo)
                      (winner-mode t)
                      )))

## Trivial modes

Function to define new trivial modes. This means that buffer is
opened by external program.

    (defun define-trivial-mode(mode-prefix file-regexp &optional command)
      (or command (setq command mode-prefix))
      (let ((mode-command (intern (concat mode-prefix "-mode"))))
        (fset mode-command
              `(lambda ()
                 (interactive)
                 (toggle-read-only t)
                 (start-process ,mode-prefix nil
                                ,command (buffer-file-name))
                 (kill-buffer (current-buffer))))
        (add-to-list 'auto-mode-alist (cons file-regexp mode-command))))

These define programs that will launch file when opened

    (define-trivial-mode "ooffice" "\\.ods$")
    (define-trivial-mode "evince" "\\.pdf$")

## Tramp

My own configuration to tramp. tramp auto-save should be located to
my personal folder. Also 'tramping' sudo rights are declared trough
proxy configuration.

    (add-to-el-sources 
     tramp 
     builtin 
     (progn
       (setq tramp-auto-save-directory (personal-place "tramp-auto-save/")
             tramp-persistency-file-name (personal-place "tramp"))
       (set-default 'tramp-default-proxies-alist (quote ((".*" "\\`root\\'" "/ssh:%h:"))))
       ))
    
    (provide 'navigation)

# Editing


Configuration relating to actual text editing.

    ;;; editing.el --- global edit configurations
    (global-set-key [f4] 'orgstruct-mode)

## Killring modifications.

New features for copy and cut functions. Non selection applys
current method to whole line. Also fixes clipboard disconnection
between X and emacs.

    (setq x-select-enable-clipboard t 
          interprogram-paste-function 'x-cut-buffer-or-selection-value)
    
    ;;New kill ring features
    (defadvice kill-ring-save (before slick-copy activate compile)
      "When called interactively with no active region, copy a single
      line instead."
      (interactive 
       (if mark-active (list (region-beginning) (region-end))
         (message  "Copied line") 
         (list (line-beginning-position) 
               (line-beginning-position 2)))))
    
    (defadvice kill-region (before slick-cut activate compile)
      "When called interactively with no active region, kill a single line instead."
      (interactive
       (if mark-active (list (region-beginning) (region-end))
         (list (line-beginning-position)
               (line-beginning-position 2)))))

## yasnippet

Works, but not with r-autoyas functionality. Could it be some kind
of version incompatibility.

    (add-to-el-sources yasnippet elpa 
                       '(progn
                          (require yasnippet)
                          ;;(yas-minor-mode-on) this triggers some symbol loop error...
                          ))

## Custom tools

Tools to edit, analyse and manipulate buffer content.

### Count words

Count words in the region.

    (defun count-words (start end)
      "Print number of words in the region."
      (interactive "r")
      (save-excursion
        (save-restriction
          (narrow-to-region start end)
          (goto-char (point-min))
          (count-matches "\\sw+"))))

### wc

wc like function in the emacs.

    (defun wc (&optional start end)
      "Prints number of lines, words and characters in region or whole buffer."
      (interactive)
      (let ((n 0)
            (start (if mark-active (region-beginning) (point-min)))
            (end (if mark-active (region-end) (point-max))))
        (save-excursion
          (goto-char start)
          (while (< (point) end) (if (forward-word 1) (setq n (1+ n)))))
        (message "%3d %3d %3d" (count-lines start end) n (- end start))))

### buffer to PDF

Copies buffer content to pdf file.

    (defun print-to-pdf ()
      (interactive)
      (ps-spool-buffer-with-faces)
      (switch-to-buffer "*PostScript*")
      (write-file "/tmp/tmp.ps")
      (kill-buffer "tmp.ps")
      (setq cmd (concat "ps2pdf14 /tmp/tmp.ps " (buffer-name) ".pdf"))
      (shell-command cmd)
      (shell-command "rm /tmp/tmp.ps")
      (message (concat "Saved to:  " (buffer-name) ".pdf")))
    
    (provide 'editing)

# Buffers


Modes and configuration for buffer management.

    ;;; buffers.el --- Buffer management customization

## iBuffer filters and grouping

iBuffer makes buffer browsing prettier and more interactive. You
can filter buffers to groups by predefined filters. 

    (defun ibuffer-create-group-filter (name filters)
      "Utility function to create wanted filter-group."
      (let ((group-filter `(,name)))
        (mapc
         (lambda(element)
           (add-to-list 'group-filter (cdr (assoc element ibuffer-filters)) t))
         filters)
        group-filter))

### TODO Filters

-   needs filter refactoring, remove school, add thesis and work filters

Here is defined basic filters that can be used to construct filter
view by `ibuffer-create-group-filter` function.

    (setq ibuffer-filters 
          '(
            ;;mail buffers
            (mail . ("Mail"
                     (or
                      (mode . message-mode)
                      (mode . mail-mode)
                      (mode . wl))))
            ;; Opened manuals
            (woman . ("WoMan"
                      (or
                       (mode . woman-mode)
                       (mode . info-mode))))
            ;; ESS related buffers
            (ess . ("ESS"
                    (or
                     (mode . inferior-ess-mode)
                     (mode . ess-help-mode)
                     (name . "\\*S objects\\*"))))
            ;; My unsorted Latex buffers
            (latex . ("LaTeX" 
                      (mode . latex-mode)))
            ;; IRC Channels 
            (erc . ("ERC"
                    (mode . erc-mode)))
            ;; Unsorted shells
            (shells . ("Shells"
                       (or
                        (mode . shell-mode)
                        (mode . term-mode)
                        (mode . eshell-mode))))
            ;; all unsorted dired buffers goes here 
            (dired . ("Dired"
                      (mode . dired-mode)))
            ;; all org-related buffers
            (org . ("Org" 
                    (or 
                     (name . "\\*Org *")
                     (mode . org-mode))))
            ;; magit buffers
            (git . ("magit"
                    (name . "\\*magit")))
            ;; school related filters
            (dp . ("DP"
                   (or
                    (filename . "parallel.distributed.org")
                    (filename . "/wrk/spin/"))))
            (dip . ("DIP"
                    (or
                     (filename . "digital.image.prosessing.org")
                     (filename . "/wrk/dip/"))))
            ;;rest of the school buffers
            (school . ("School Courses"
                        (mode . org-mode)
                        (filename . "/org/courses/")))
            (emacs-conf . ("Emacs configuration"
                           (or
                            (filename . "/emacs.seed/")
                            (filename . ".emacs.d/")
                            (filename . "~/.erc-bouncers.el"))))
            ;; Here are the buffers that are not in projectXYZ gategory
            (programming . ("Programming" 
                            (or
                             (mode . groovy-mode)
                             (mode . php-mode)
                             (mode . sgml-mode)
                             (mode . sh-mode)
                             (mode . c-mode)
                             (mode . perl-mode)
                             (mode . python-mode)
                             (mode . emacs-lisp-mode))))))

### TODO Filter Views

-   create work filter group

Here is the configuration of ibuffer views. First the views are
defined and with hook the default view is set.

    (setq ibuffer-saved-filter-groups
          `(,(ibuffer-create-group-filter "default" '(emacs-conf mail erc shells git school org dired))
            ,(ibuffer-create-group-filter "communication" '(shells mail erc dired))
            ,(ibuffer-create-group-filter "development" '(git woman shells programming dired))
            ,(ibuffer-create-group-filter "documentation" '(org latex dired))
            ,(ibuffer-create-group-filter "statistics" '(org ess dired))
            ,(ibuffer-create-group-filter "school" '(erc shells dp dip school org dired))))
    
    (add-hook 'ibuffer-mode-hook
              (lambda ()
                (ibuffer-switch-to-saved-filter-groups "default")))

## Save

Using .backups folder as a base folder where to place emacs
buffers autosave files. Here we also configure my desktop
recording, which reopens my last buffers when I close and reopen
my emacs.

    (add-to-el-sources
     desktop
     builtin
     (progn
        (desktop-save-mode)))
    
    (add-to-el-sources
     savehist
     builtin
     (progn
        (savehist-mode)
        (setq savehist-file (personal-place "savehist-history"))
        ))
    
    (setq
     make-backup-files t
     backup-directory-alist (quote ((".*" . "~/.backups/emacs.buffers/"))))

## Automatic Cleaning

Keeps my buffer listing reasonable by removing unused buffers. Run
weekly, because once a day is too often.

    (add-to-list
     'el-get-sources
     '(:name midnight :type builtin :features midnight
             :after
             (progn
               (setq
                clean-buffer-list-kill-never-regexps '("\\.org$" "^#" "^!"))
               (run-at-time "23:00" (timer-duration "1 week") 'clean-buffer-list)
               )))

## IDO mode

Library to enhance usability with buffer and directory
listings. Works mostly in minibuffer area.

    (add-to-list
     'el-get-sources
     '(:name ido :type builtin :features ido
             :after
             (progn
               (ido-mode t)
               (setq 
                ido-ignore-buffers               ; ignore these guys
                '("\\` " "^\*Mess" "^\*Back" ".*Completion" "^\*Ido")
                ido-work-directory-list '("~" "~/Documents")
                ido-case-fold  t                 ; be case-insensitive
                ido-enable-flex-matching t       ; be flexible
                ido-max-prospects 6              ; don't spam my minibuffer
                ido-confirm-unique-completion t) ; wait for RET, even with unique completion
               )
             ))

## Buffer renaming

When opening a buffer which has same name, this configuration will
keep buffers unique. It will reorganize names if one the buffers
has been killed. It will also ignore "system" buffers (starting
with \*-symbol).

    (add-to-list
     'el-get-sources
     '(:name uniquify :type builtin :features uniquify
             :after 
             (progn
               (setq 
                uniquify-buffer-name-style 'post-forward
                uniquify-separator "::"
                uniquify-after-kill-buffer-p t
                uniquify-ignore-buffers-re "^\\*")
               )))
    
    (provide 'buffers)

# Org-mode


Org-mode, God mode, devils-advocate, nicknames are many. This is
probably most usefull mode I have ever met. This has converted me to
be full emacs fanatic and still keeps me amazed. This configuration
file is powered by org-babel, so you can see its power.

    ;;; org-personal.el --- personalization to my org
    (setq org-directory "~/org")

## el-get recipe definition


This will hook org mode to el-get package manager and trigger
loading of personal customization.

[This will added via noweb syntax to emacs.el.](../../.emacs.d/emacs.html)

    (add-to-el-sources
     org
     elpa
     (progn
       (require 'org-personal)
       (require 'org-crypt)))

## Agenda

Agenda is tool for scheduling your events in selected org-buffers,
so called agenda-files.

    (setq 
     org-agenda-start-on-weekday 0 
     org-agenda-show-all-dates t
     org-agenda-tags-column -102
     org-agenda-files (concat org-directory "/agenda.files.txt")
     org-agenda-text-search-extra-files '(agenda-archives)
     org-agenda-time-grid '((daily require-timed)
                            "--------------------"
                            (800 1000 1200 1400 1600 1800 2000 2200))
     org-agenda-todo-ignore-with-date t
     org-agenda-skip-deadline-if-done t
     org-agenda-skip-scheduled-if-done t
     org-agenda-skip-timestamp-if-done t
     org-agenda-repeating-timestamp-show-all t)
    
    (add-hook 'org-agenda-mode-hook '(lambda () (hl-line-mode 1)))

### To do flow in tasks

Here is described how todo keywords are flowd when task is
progressed. Clocking is triggered to change the tasks
status. Logging of different state changes are defined in last
configuration.

    (setq 
     org-clock-in-switch-to-state '(lambda (state) 
                                     (cond
                                      ((string= state "TODO") "STARTED")
                                      ((string= state "ISSUE") "OPEN")
                                      (t "STARTED")))
     org-clock-out-switch-to-state '(lambda (state) 
                                     (cond
                                      ((string= state "STARTED") "WAITING")
                                      ((string= state "OPEN") "ISSUE")
                                      (t "WAITING")))
     ;; org-stuck-projects '("LEVEL=2-REFILE-WAITING|LEVEL=1+REFILE/!-DONE-CANCELLED-OPEN" nil ("NEXT") "")
     org-enforce-todo-dependencies t
     org-todo-keywords '((sequence "TODO(t)" "STARTED(s!)" "|" "DONE(d!/!)")
                         (sequence "WAITING(w/!)" "SOMEDAY(S@/!)" "|" "CANCELLED(c@/!)")
                         (sequence "ISSUE(i!)" "OPEN(O@/!)" "|" "DUBLICATE(D@!)" "WONTFIX(W@!)" "CLOSED(C@!)" "REJECTED(R@!)")))

-   Show TODO children of the headline

    Define function that lists TODOs in current subtree.
    
        (defun org-show-todo-children ()
          (interactive)
          (org-narrow-to-subtree)
          (org-show-todo-tree nil)
          (widen))

### Time and date


Here I set custom properties for my clocking efforts and customize
my time and date options.

    (setq 
     org-deadline-warning-days 15
     org-drawers '("PROPERTIES" "LOGBOOK" "CLOCK")
     org-clock-into-drawer "CLOCK"
     org-clock-out-remove-zero-time-clocks t
     org-clock-persist 'history
     org-global-properties '(("Effort_ALL" . "0:10 0:30 1:00 2:00 3:00 4:00 5:00 6:00 7:00 8:00 10:00 20:00 50:00"))
     org-log-into-drawer t
     ;; org-clock-sound "/usr/local/lib/alert1.wav"
     org-log-done 'time)

### Icalendar Exporting


This configurations defines region and user specific properties to
potential exports in .ics format of the agenda view.

    (setq
     org-icalendar-categories '(all-tags)
     org-icalendar-combined-name "Sami Airaksinen"
     org-icalendar-include-body 500
     org-icalendar-include-todo t
     org-icalendar-store-UID t
     org-icalendar-timezone "Europe/Helsinki"
     org-icalendar-use-deadline '(todo-due event-if-todo event-if-not-todo)
     org-icalendar-use-scheduled '(todo-due event-if-todo event-if-not-todo))

## Babel

Babel enables source code evaluation of many different languages
inside the org mode buffer. Evolution is fast and current version
enables at least following features:

-   interactive code editing inside the org-mode buffer

-   source code evaluation with I/O redirection

    (org-babel-do-load-languages 
     'org-babel-load-languages
     '(
       (octave . t)
       (R . t) 
       (sh . t)))

## Block Wrapping function

Inserts marked region between org-mode custom block, interactive.

    (defun org-block-wrap-region(start end)
      "Wraps current region between predefined prefix-endfix strings. by: Sami Airaksinen"
      (interactive "r")
      (let ((markup (read-string "define markup: " nil nil '("SRC" "EXAMPLE" "LaTeX" "CENTER" "QUOTE" "VERSE"))) 
            (start-region-char (if (eq (char-after start) ?\n) nil "\n"))
            (end-region-char (if (eq (char-before end) ?\n) nil "\n")))
        (let ((start-mark (concat "#+BEGIN_" markup start-region-char)) (end-mark (concat end-region-char "#+END_" markup)))
          ;; adding to end
          (goto-char end)
          (insert end-mark)
          ;; adding to start
          (goto-char start)
          (insert start-mark))))

## Buffer Encryptions

Forcing encryption for headlines that have encrypt tag. 

**UPDATE** : <span class="timestamp-wrapper"><span class="timestamp">&lt;2012-09-15 Sat&gt;</span></span> 

Currently require of org-crypt is moved outside of this module, see
here.

    (add-hook 'org-save-all-org-buffers '(lambda() org-encrypt-entries))

## Column mode

Org modes column face. Layouts headline at its childs to fixed
table where you can edit easily its properties. 

    (setq
     org-columns-default-format "%50ITEM(Task) %7TODO(ToDo) %10TAGS(Context) %10Effort(Effort){:} %10CLOCKSUM")
    ; org-columns-modify-value-for-display-function '(lambda (column-title value)
    ;                                                  nil))

### DONE Font change prevention

Make sure that a fixed-width face is used when we have a column
table. This occurs if emacs daemon is used.

    (when (and (fboundp 'daemonp) (daemonp))
      (add-hook 
       'org-mode-hook 
       '(lambda ()
          (when (fboundp 'set-face-attribute)
            (set-face-attribute 
             'org-column nil
             :height (face-attribute 'default :height)
             :family (face-attribute 'default :family))))))

## Exporting

Org-mode enables exports to different common formats. 

### Latex

Latex exports needs header templates and conversion rules for
headlines.

    (setq 
     org-export-latex-Image-default-option "width=hsize"
     org-export-latex-classes '(
                                ("article" "\\documentclass[12pt,a4paper]{article}
    \\usepackage[utf8]{inputenc}
    \\usepackage[T1]{fontenc}
    \\usepackage{graphicx}
    \\usepackage[pdftex]{hyperref}"
                                 ("\\section{%s}" . "\\section*{%s}") 
                                 ("\\subsection{%s}" . "\\subsection*{%s}") 
                                 ("\\subsubsection{%s}" . "\\subsubsection*{%s}") 
                                 ("\\paragraph{%s}" . "\\paragraph*{%s}") 
                                 ("\\subparagraph{%s}" . "\\subparagraph*{%s}")) 
                                ("report" "\\documentclass[12pt,a4paper]{report}
    \\usepackage[utf8]{inputenc}
    \\usepackage[T1]{fontenc}
    \\usepackage{graphicx}
    \\usepackage{hyperref}" 
                                 ("\\part{%s}" . "\\part*{%s}") 
                                 ("\\chapter{%s}" . "\\chapter*{%s}") 
                                 ("\\section{%s}" . "\\section*{%s}") 
                                 ("\\subsection{%s}" . "\\subsection*{%s}") 
                                 ("\\subsubsection{%s}" . "\\subsubsection*{%s}")) 
                                ("book" "\\documentclass[12pt,a4paper]{book}
    \\usepackage[utf8]{inputenc}
    \\usepackage[T1]{fontenc}
    \\usepackage{graphicx}
    \\usepackage{hyperref}" 
                                 ("\\part{%s}" . "\\part*{%s}") 
                                 ("\\chapter{%s}" . "\\chapter*{%s}") 
                                 ("\\section{%s}" . "\\section*{%s}")
                                 ("\\subsection{%s}" . "\\subsection*{%s}") 
                                 ("\\subsubsection{%s}" . "\\subsubsection*{%s}")) 
                                ("aa" "\\documentclass[structabstract]{aa}
    \\usepackage{txfonts}
    \\usepackage{graphicx}
    \\usepackage{longtable}
    \\usepackage{hyperref}
    \\usepackage{natbib} 
    \\bibpunct{(}{)}{;}{a}{}{,}" 
                                 ("\\section{%s}" . "\\section*{%s}") 
                                 ("\\subsection{%s}" . "\\subsection*{%s}") 
                                 ("\\subsubsection{%s}" . "\\subsubsection*{%s}") 
                                 ("\\paragraph{%s}" . "\\paragraph*{%s}") 
                                 ("\\subparagraph{%s}" . "\\subparagraph*{%s}")))
     org-format-latex-header "\\documentclass[a4paper]{article}
    \\usepackage{amssymb}
    \\usepackage{amsmath}
    \\usepackage{latexsym}
    \\usepackage{fullpage}
    \\pagestyle{empty}
    \\usepackage[mathscr]{eucal}
    \\usepackage[usenames]{color}")

## Global keybindings

The following key strokes are highly used and we want them to be
accessible from whole system.

    (global-set-key (kbd "C-c a") 'org-agenda)
    (global-set-key (kbd "C-c l") 'org-store-link)

## Headline Editing

Here will be configurations relating to Task refiling and archiving.

    (setq
     org-archive-location "archive/%s_archive::"
     org-refile-targets '((org-agenda-files . (:maxlevel . 2))))

### Remember and capture

Org-remember enables fast note taking. With a key stroke I can
start taking complex note with different instant configuration
options.



    (setq 
     org-default-notes-file (concat org-directory "/notes.org")
     org-reverse-note-order t
     org-remember-templates '(("Task" ?t "* TODO %^{task} %^G\n (creation: %u @ %a)\n\n %i%?" "refile.org" "Tasks")
                                ("Capture" ?c "* %?\n\tcreation: %u @ %a\n\n %i" "notes.org" "Capture")
                                ("Meeting" ?m "* %^{occasion}\n %^{at time}T @ %^{where} \n (creation: %u @ %a) \n\n %i \n %a" "refile.org" "Meetings")
                                ("Note" ?n "* %?\n (creation: %u @ %a)\n %i%!%&" "refile.org" "Ideas")))
    
    (org-remember-insinuate)
    
    (global-set-key (kbd "C-c r") 'org-remember)

## Hooks

Defines org general mode hook that is applied when mode is
started. Here you can configure your environment even further.

    (add-hook 'org-mode-hook '(lambda ()
       (flyspell-mode 1)
       (local-set-key (kbd "<f5>") 'org-agenda)
       (local-set-key (kbd "C-c b") 'org-iswitchb)
       (local-set-key (kbd "C-c W") 'org-block-wrap-region)))

## Images in Buffers

Minor mode that shows images directly in the org-buffer.

    ;; enable image mode first
    (iimage-mode)
    
    ;; add the org file link format to the iimage mode regex
    (add-to-list 'iimage-mode-image-regex-alist
      (cons (concat "\\[\\[file:\\(~?" iimage-mode-image-filename-regex "\\)\\]")  1))
    
    ;; function to setup images for display on load
    (defun org-turn-on-iimage-in-org ()
      "display images in your org file"
      (interactive)
      (turn-on-iimage-mode)
      (set-face-underline-p 'org-link nil))
    
    ;; function to toggle images in a org bugger
    (defun org-toggle-iimage-in-org ()
      "display images in your org file"
      (interactive)
      (if (face-underline-p 'org-link)
          (set-face-underline-p 'org-link nil)
          (set-face-underline-p 'org-link t))
      (call-interactively 'iimage-mode))
    
    ;;  add a hook so we can display images on load
    (add-hook 'org-mode-hook '(lambda () (org-turn-on-iimage-in-org)))

## Linking

Linking is essential part of usefulness of org-mode. Buffers can
form effective data structure for your daily organizational
information. Here is configuration how links can be used.

    (setq org-link-abbrev-alist
          '(("google" . "http://www.google.com/search?q=")
            ("wiki" . "http://en.wikipedia.org/wiki/")))

## Mobile-org

Configure Mobile org using Ubuntu One.

    (setq 
     org-mobile-directory "~/org/mobile"
     ;; Set to the name of the file where new notes will be stored
     org-mobile-inbox-for-pull "~/org/mobile/mobile-flagged.org")     

## Tags

Most frequently tags. I have couple of exclusive tag groups so if I
change the tag it will remove other group tag automatically.

    (setq 
     org-tag-alist 
     '(
       (:startgroup) ("@errand" . ?e) ("@tkk" . ?t) ("@home" . ?h) ("@work" . ?w) (:endgroup)
       (:startgroup) ("RESEARCH" . ?r) ("PLAN" . ?p) ("DESIGN" . ?d) ("IMPLEMENT" . ?i) (:endgroup)
       (:startgroup) ("TASK" . ?t) ("STORY" . ?s) (:endgroup)
       (:startgroup) ("BUG" . ?b) ("FEATURE" . ?f) ("IMPROVEMENT" . ?I) (:endgroup)
    
       ("ASSIGMENT" . ?a)
       ("APPOINTMENT" . ?A)
       ("PHONE" . ?P)
       ("BUY" . ?B)
       ("EMAIL" . ?E)))
    
    ;; modularize this personalization
    (provide 'org-personal)

# ERC-client


ERC is emacs mode for IRC communications.

    ;;; erc-customs.el --- Personal customization for ERC package
    (add-to-el-sources
     erc
     builtin
     (progn
       (setq 
        erc-max-buffer-size 30000
        erc-truncate-buffer-on-save t
        erc-notice-highlight-type (quote all)
        erc-notice-prefix ">>>> "
        erc-prompt "WRITE HERE> "
        erc-auto-query 'window-noselect)
    
       ;;enable autojoin
       (erc-autojoin-mode t)
    
       ;;define some custom hook to truncate erc buffers correctly
       (defvar erc-insert-post-hook)
       (add-hook 'erc-insert-post-hook 'erc-truncate-buffer))
     :features erc)

## Bouncer and Identification


Define macro for creating Bouncer connection function.  

    ;;define bouncer connection tool
    (defmacro asf-erc-bouncer-connect (command server port nick ssl pass)
      "Create interactive command `command', for connecting to an IRC server. The
       command uses interactive mode if passed an argument."
      (fset command
            `(lambda (arg)
               (interactive "p")
               (if (not (= 1 arg))
                   (call-interactively 'erc)
                 (let ((erc-connect-function ',(if ssl 
                                                   'erc-open-ssl-stream
                                                 'open-network-stream)))
                   (erc :server ,server :port ,port :nick ,nick :password ,pass))))))

### TODO Login proxies

-   redo these tools
    
    -   [ ] hide intermediate functions
    
    -   [ ] hide proxy macro defun
    
    -   [ ] bouncers are red and regenerated from file each time
        erc-bouncer-login is called

Here we define connections to my IRC-server. Server connections
are opened via already available ssh tunnel (provided by gSTM).

Alternative handling strategies

-   different Tunnel manager or,

-   tunneling with emacs commands

-   opening ports from router for irssi-proxies

    ;; create connection functions to my irssi-proxy
    ;; !! NOTE MESSAGES UNENCRYPTED !!!  
    (setq erc-registered-bouncers '())
    
    (defun erc-add-bouncer (key bouncer)
      "Adds bouncer with key to alist if not exists."
      (setq erc-registered-bouncers (add-to-list 'erc-registered-bouncers `(,key . ,bouncer) nil 
            (lambda (o1 o2)
              (equal (car o1) (car o2))))))
    
    (defun erc-get-bouncers ()
      erc-registered-bouncers)
    
    (defun erc-read-bouncer-properties (file)
      (load file))
    
    (defun erc-bouncer-login ()
      "Make connection with each registered bouncer connection."
      (interactive)
      (mapc
       (lambda (current)
         (funcall (cdr current)))
         (erc-get-bouncers)))
    
    (defun erc-create-and-register-bouncers (bouncers)
      "Creates bouncers for each element in bouncers
    list. Assumes that properties are red for each symbol. ssl
    not working at the moment."
      (mapc
       (lambda (current)
         (erc-add-bouncer current (let  ((name 'current) 
                                          (host (get current :host)) 
                                          (port (get current :port))
                                          (user (get current :user))
                                          (ssl (get current :ssl))
                                          (passwd (get current :passwd)))
                                    `(lambda ()
                                       (erc :server ,host :port ,port :nick ,user :password ,passwd)))))
                                    bouncers))
    
    ;; setting login command for erc to my proxy 
    (global-set-key [f2] 'erc-bouncer-login)
    
    (erc-read-bouncer-properties (personal-place ".erc-bouncers.el"))
    
    (erc-create-and-register-bouncers '(erc-irssi-ircnet
                                        erc-irssi-linknet
                                        erc-irssi-freenode))

## IRC custom commands


With this I will send ctcp message to my proxy which will feed me
the current backlog.

    (defun erc-cmd-BACKLOG ()
      (erc-send-ctcp-message "-proxy-" "IRSSIPROXY BACKLOG SEND"))
    
    ;; module for my erc customs  
    (provide 'erc-customs)

# Programming


Here be things related to building software. 

    ;;; programming.el --- different programming language mode configurations 
    
    (add-to-el-sources
     highlight-parentheses elpa
     (progn
       (require 'highlight-parentheses)
       (add-hook 'lisp-mode-hook 'highlight-parentheses-mode)
       (add-hook 'emacs-lisp-mode-hook 'highlight-parentheses-mode))
     )
    
    (add-to-list
     'el-get-sources
     '(:name yasnippet 
             :after
             (progn
               (yas-global-mode 1))))
    
    (add-to-list
     'el-get-sources
     '(:name chm-view :features chm-view))
    
    (add-to-el-sources
     pabbrev
     elpa
     (progn
       (require 'pabbrev)))
    
    ;;optionally loading if found
    (require 'ess-site nil 'no-error)
    
    (setq font-lock-maximum-decoration t)
    (global-font-lock-mode t)

## Compilation shell output

Settings of a compile output buffer/window

    (global-set-key [f11] 'compile)
    (global-set-key [f12] 'recompile)
    
    (setq compilation-scroll-output t
          compilation-window-height 16)

## Folding mode

Enable code block folding as minor-mode, should define those
folding modes and markups.

    (add-to-list
     'el-get-sources
     '(:name folding :after
             (progn
               (load "folding" 'nomessage 'noerror)
               (folding-add-to-marks-list 'haskell-mode "--{{{"  "--}}}"  nil t)
               (folding-mode-add-find-file-hook)
               (add-hook 'haskell-mode-hook 'folding-mode)
               )))

## C

    ;;C-hook
    (add-hook 'c-mode-hook
      (lambda ()
        (font-lock-add-keywords nil
          '(("^[^\n]\\{80\\}\\(.*\\)$" 1 font-lock-warning-face t)))))

## Fortran F90

    ;; g95 to compilation mode
    (eval-after-load "compile"
      '(setq compilation-error-regexp-alist
             (cons '("^In file \\(.+\\):\\([0-9]+\\)" 1 2)
                   compilation-error-regexp-alist))) 

## XREF


Xrefactory configuration part

    ;; some Xrefactory defaults can be set here
    (defvar xref-current-project nil) ;; can be also "my_project_name"
    (defvar xref-key-binding 'none) ;; can be also 'local or 'none
    
    (setq load-path (cons "/usr/lib/emacs/xref/emacs" load-path))
    (setq exec-path (cons "/usr/lib/emacs/xref/" exec-path))
    
    (load "xrefactory")
    
    ;; end of Xrefactory configuration part ;;
    (message "xrefactory loaded")

## JDEE


    ;;JDEE configure
    
    ;; add to list JDEE stuff
    (add-to-list 
     'load-path (expand-file-name "/usr/local/jdee/jde-2.3.5.1/lisp"))
    
    (add-to-list 
     'load-path (expand-file-name "/usr/local/jdee/cedet-1.0beta3b/common"))
    
    (add-to-list 
     'load-path (expand-file-name "/usr/share/emacs/site-lisp/elib"))
    
    (load-file (expand-file-name "/usr/local/jdee/cedet-1.0beta3b/common/cedet.el"))
    
    ;; If you want Emacs to defer loading the JDE until you open a 
    ;; Java file, edit the following line
    (setq defer-loading-jde nil)
    ;; to read:
    (setq defer-loading-jde t)
    (if defer-loading-jde
        (progn
          (autoload 'jde-mode "jde" "JDE mode." t)
          (setq auto-mode-alist
             (append
              '(("\\.java\\'" . jde-mode))
              auto-mode-alist)))
      (require 'jde))
    
    ;;set some jde variables
    (setq jde-jdk (quote ("sun 1.6.0.10"))
          jde-jdk-registry (quote (("sun 1.6.0.10" . "/usr/lib/jvm/java-6-sun-1.6.0.10/") ("open 1.6.0" . "/usr/lib/jvm/default-java"))))
    
    ;; Sets the basic indentation for Java source files
    ;; to two spaces.
    (defun my-jde-mode-hook ()
      (setq c-basic-offset 3))
    
    ;;make mode-hook
    (add-hook 'jde-mode-hook 'my-jde-mode-hook)

## Maven

Enables simple POM property parsing and connection to JDE mode.

    (add-to-list
     'el-get-sources
     '(:name pom))

## Sage


    (add-to-list 'load-path (expand-file-name "$SAGE_DATA/emacs"))
    (require 'sage "sage")
    (setq sage-command "$SAGE_ROOT/sage")
    
    ;; If you want sage-view to typeset all your output and have plot()
    ;; commands inline, uncomment the following line and configure sage-view:
    (require 'sage-view "sage-view")
    (add-hook 'sage-startup-hook 'sage-view)
    You can use commands like
    (add-hook 'sage-startup-hook 'sage-view
    'sage-view-disable-inline-output 'sage-view-disable-inline-plots)
    ;; to have some combination of features.  In future, the customize interface
    ;; will make this simpler... hint, hint!

## Ruby

    (add-to-list
     'el-get-sources
     '(:name ruby-mode :features ruby-mode ;'(ruby-mode ruby-electric)
             :after
             (progn
               (add-to-list 'interpreter-mode-alist '("ruby" . ruby-mode)) 
               (add-to-list 'auto-mode-alist '("\\.rb$" . ruby-mode))
               (defun ruby-eval-buffer () 
                 (interactive)
                 "Evaluate the buffer with ruby."
                 (shell-command-on-region (point-min) (point-max) "ruby"))
               (add-hook 'ruby-mode-hook 
                         (lambda ()
                           (setq standard-indent 4)
                           (pabbrev-mode t)
                           ;;(ruby-electric-mode t)
                           (define-key ruby-mode-map "\C-c\C-a" 'ruby-eval-buffer)))
               )))

## Php

For debugging php files.

    (add-to-list
     'el-get-sources
     '(:name php-mode-improved))

## IDL

Old and trustful data processing language.

    (setq idlwave-block-indent 4
          idlwave-end-offset -4
          idlwave-indent-parens-nested t)

## Groovy

Java groovy configurations.

    ;;; use groovy-mode when file ends in .groovy or has #!/bin/groovy at start
    ;;; note: needed sudo apt-get install bzr
    (add-to-list
     'el-get-sources
     '(:name groovy-emacs-mode :after
             (progn 
               (add-to-list 'auto-mode-alist '("\.groovy$" . groovy-mode))
               (add-to-list 'interpreter-mode-alist '("groovy" . groovy-mode))
               )))

## Promela

Spin model checker uses promela as its programming language  

    (autoload 'promela-mode "promela-mode" "PROMELA mode" nil t)
    (setq auto-mode-alist
          (append
           (list (cons "\\.promela$"  'promela-mode)
                 (cons "\\.spin$"     'promela-mode)
                 (cons "\\.pml$"      'promela-mode)
                 ;; (cons "\\.other-extensions$"     'promela-mode)
                 )
           auto-mode-alist))

## javascript

Nodejs is installed/downloaded outside emacs frame,

    sudo apt-get install nodejs npm

flymake-jslint, flymake-cursor and js2-mode are installed from elpa
and configured.

    ;;(add-to-list 'interpreter-mode-alist '("spidermonkey" . js2-mode))
    
    ;; (require 'js-comint) 
    (add-to-list 
     'el-get-sources 
     '(:name js-comint :type elpa 
             :after 
             (progn
               (setq inferior-js-program-command "/usr/bin/js")
               (add-hook 'js2-mode-hook 
                         '(lambda ()
                            (local-set-key "\C-x\C-e" 'js-send-last-sexp)
                            (local-set-key "\C-\M-x" 'js-send-last-sexp-and-go)
                            (local-set-key "\C-cb" 'js-send-buffer)
                            (local-set-key "\C-c\C-b" 'js-send-buffer-and-go)
                            (local-set-key "\C-cl" 'js-load-file-and-go)
                            ))
               )))
    (add-to-list 
     'el-get-sources 
     '(:name js2-mode :type elpa
             :after 
             (progn
               (add-to-list 'auto-mode-alist '("\\.js\\'" . js2-mode))
               )))
    
    ;;todo enable
    ;;(require 'flymake-jslint)
    ;;(add-hook 'js-mode-hook 'flymake-jslint-load)

## Slime

Superior Lisp mode.

    (add-to-list
     'el-get-sources
     '(:name slime :features slime-autoloads
             :after
             (progn
               (setq inferior-lisp-program "/usr/bin/sbcl")
               (add-to-list 'load-path "/usr/share/emacs/site-lisp/slime") ;; adding slime to load path
               (slime-setup '(slime-fancy))
               )))
    
    (provide 'programming)

# Browsers


Here be variables and things related to emacs-to-internet consept.
Should build function that asks which browers to start (ff/w3c)

    ;;; browsers.el --- utilities to integrate browser actions to emacs buffers 
    (add-to-el-sources
     w3m
     builtin
     (progn 
       (global-set-key (kbd "C-x C-f") 'search-in-internet)
       (global-set-key (kbd "C-x C-m") 'browse-url-at-point) ;;FUCKING REMEMBER THIS!!@!!
       (setq w3m-use-cookies t)
       (setq browse-url-browser-function 
             (lambda(url &optional new-window)
               (interactive)
               (let ((available-browsers '(
                                           ("default" browse-url-default-browser)
                                           ("firefox" browse-url-firefox)
                                           ("w3m" w3m-browse-url))))
                 (funcall 
                  (cadr 
                   (assoc 
                    (read-string 
                     "Select Browser: " 
                     (caar available-browsers)
                     nil
                     (mapcar 'car available-browsers)) available-browsers))
                  url new-window))))
       ))

## The custom search URLs


Function that applies marked region to google search.

    ;; Variables
    (defvar *internet-search-urls*
      (quote ("http://www.google.com/search?ie=utf-8&oe=utf-8&q=%s"
              "http://en.wikipedia.org/wiki/Special:Search?search="
              "http://perldoc.perl.org/search.html?q=")))
    
    ;;; Search a query on the Internet using the selected URL.
    (defun search-in-internet (arg)
      "Searches the internet using the ARGth custom URL for the marked
     text. If a region is not selected, prompts for the string to search
     on. The prefix number ARG indicates the Search URL to use. By default
     the search URL at position 1 will be used."
      (interactive "p")
    
      ;; Some sanity check.
      (if (> arg (length *internet-search-urls*))
          (error "There is no search URL defined at position %s" arg))
    
      (let ((query                          ; Set the search query first.
             (if (region-active-p)
                 (buffer-substring (region-beginning) (region-end))
               (read-from-minibuffer "Search for: ")))
    
            ;; Now get the Base URL to use for the search
            (baseurl (nth (1- arg) *internet-search-urls*)))
    
        ;; Add the query parameter
        (let ((url
               (if (string-match "%s" baseurl)
                   ;; If the base URL has a %s embedded, then replace it
                   (replace-match query t t baseurl)
                 ;; Else just append the query string at end of the URL
                 (concat baseurl query))))
    
          (message "Searching for %s at %s" query url)
          ;; Now browse the URL
          (browse-url url))))
    
    (defun wiki-search ()
      (search-in-internet 2))
    
    (defun perldoc-search ()
      (search-in-internet 3))
    
    (provide 'browsers)

# TODO ElNode


Elnode is a library that enables emacs to expose itself as user
defined web services.

-   dependencies needs to be defined here

    ;;; el-node-services.el --- Example usage of el-node library
    
    (add-to-list
     'el-get-sources
     '(:name elnode :features elnode
             :after 
             (progn
               (global-set-key (kbd "<C-f12>") 'elnode-init-services)
               (global-set-key (kbd "<C-S-f12>") 'elnode-stop-services)    
               )))

## Utility tools

Used to Store and retrieve configuration data of services.

    (defun elnode-add-service-to-init (handler port host)
      (setq elnode-local-handlers (add-to-list 'elnode-local-handlers handler))
      (setplist handler (list :port port :host host)))
    
    (defun get-elnode-local-handlers ()
      elnode-local-handlers)
    
    ;; initialize handler list   
    (setq elnode-local-handlers '())

## Services

Here is definition of the service initialization.

    (defun elnode-init-services()
      "Starts all defined elnode tcp services. These services are
         defined in configuration file, but can be added/modified any
         time."
      (interactive)
      (message "Starting elnode services...")
      (mapc 
       (lambda (request-handler)
         (elnode-start request-handler (get request-handler :port) (get request-handler :host)))
       (get-elnode-local-handlers))
       (message "elnode: Starting done."))
    
    (defun elnode-stop-services()
      "Stopping all services defined in elnode-local-handlers list"
      (interactive)
      (message "Stopping elnode services...")
      (mapc 
       (lambda (request-handler)
         (elnode-stop (get request-handler :port)))
       (get-elnode-local-handlers))
      (message "elnode: Stopping done."))     

### Simple Example service

This is the simplest example possible, hello world.

    (defun nicferrier-handler (httpcon)
      "Demonstration function"
      (elnode-http-start httpcon "200" '("Content-type" . "text/html"))
      (elnode-http-return httpcon "<html><b>HELLO!</b></html>"))
    (elnode-add-service-to-init 'nicferrier-handler 8010 "localhost")

### Complex Example service

This is a example service that can be provided by this little editor,

    (defun orgexpose (httpcon)
      (save-excursion
        (org-export-as-xoxo (get-buffer "school.org"))
        (elnode-http-start httpcon "200" '("Content-type" . "text/html"))
        (elnode-http-return 
         httpcon
         (format "<html>%s</html>" 
                 (with-current-buffer (get-buffer "school.html")
                   (buffer-substring-no-properties (point-min) (point-max)))))))
    (elnode-add-service-to-init 'orgexpose 8020 "localhost")
    
    (provide 'el-node-services)

# Consoles


First we need to define some features, such as colors and
completion, which we want to our shells.

    ;;; consoles.el --- Several different console configuration
    (setq explicit-bash-args '("--noediting" "-i" "-l"))
    
    (add-to-list
     'el-get-sources
     '(:name shell-completion :features shell-completion))

## SQL

Defines customization of the SQL mode. This is very poverfull mode
for integrating SQL database actions to emacs.

### Keybinding

    (global-set-key (kbd "<f9>") 'sql-mysql)

### Hooks

    (add-hook 'sql-interactive-mode 'toggle-truncate-lines)

## Multiterm

My new terminal manager. There is couple of copy/paste issues and
backspacing that renders this quite useless in my usage.

    (add-to-list
     'el-get-sources
     '(:name multi-term :features multi-term
             :after (progn
                      (global-set-key (kbd "<C-f8>") 'multi-term)
                      (setq multi-term-program "/bin/bash"
                            multi-term-shell-arguments "-l"
                            multi-term-buffer-name "bash-shell"))))

## TODO eshell

You should get familiarized with eshell

## git

Here is defined git-emacs interface customization. Currently I'm
using magit.

### magit Configuration

    (add-to-list
     'el-get-sources
     '(:name magit :type elpa
             :after
             (progn
               (global-set-key (kbd "<f10>") 'magit-status))
             ))

### git-gutter

Enable git gutter sublime fork mode so that I can visualize diff
against GIT head.

    (add-to-el-sources
     git-gutter
     elpa 
     (progn
      (global-git-gutter-mode t)
      (global-set-key (kbd "C-x C-g") 'git-gutter:toggle)
      (global-set-key (kbd "C-x v =") 'git-gutter:popup-hunk)
    
      (global-set-key (kbd "C-x p") 'git-gutter:previous-hunk)
      (global-set-key (kbd "C-x n") 'git-gutter:next-hunk)
    
      (global-set-key (kbd "C-x r") 'git-gutter:revert-hunk)))

## Bash-shell

This has been made obsolete by Multiterm package.

### Keybinding

    (global-set-key [f8] 'alt-shell-dwim)
    (global-set-key (kbd "M-r") 'shell-resync-dirs)

### Other

    (defun alt-shell-dwim (arg)
      "Run an inferior shell like `shell'. If an inferior shell as its I/O
    through the current buffer, then pop the next buffer in `buffer-list'
    whose name is generated from the string \"*shell*\". When called with
    an argument, start a new inferior shell whose I/O will go to a buffer
    named after the string \"*shell*\" using `generate-new-buffer-name'."
      (interactive "P")
      (let* ((shell-buffer-list
             (let (blist)
                (dolist (buff (buffer-list) blist)
                  (when (string-match "^\\*shell\\*" (buffer-name buff))
                   (setq blist (cons buff blist))))))
             (name (if arg
                      (generate-new-buffer-name "*shell*")
                    (car shell-buffer-list))))
        (shell name)))
    
    (provide 'consoles)      

# Emacs customization

Here we define and load the file where customization is kept.

    (require 'appearance)
    ;; in separate variable so that emacs can find sexp where to add things.
    (setq custom-file "~/.emacs-custom.el") 
    (load custom-file 'noerror)

# Loading of different aspects

Here I then load these personalization modules to my emacs at
startup. I intentionally left some modules unloaded, because they
are so rarely used.

    ;; here should be org-mode recipe definition from inside org headline... 
    (add-to-el-sources
     org
     elpa
     (progn
       (require 'org-personal)
       (require 'org-crypt)))
    
    ;; here are headline categorized configs as simple modules... 
    (require 'navigation)
    (require 'editing)
    (require 'buffers)
    (require 'erc-customs)
    (require 'browsers)
    
    (require 'consoles)
    (require 'programming)
    ;;    (require 'el-node-services)

## syncing el-get packages

Here we synchronize sync all previously defined packages that were
declared in this configuration file. 

    (setq my-el-get-packages
          (append
           (mapcar 'el-get-source-name el-get-sources)))
    (el-get 'sync my-el-get-packages)

# License

Used external libraries are licensed as they are described in their
source files. This file and its generated derivatives are licensed
by following license:

"This program is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation; either version 3, or (at your option)
any later version.

This program is distributed in the hope that it will be useful, but
WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU
General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program; see the file COPYING.  If not, write to the
Free Software Foundation, Inc., 51 Franklin Street, Fifth Floor,
Boston, MA 02110-1301, USA."

If you notice some license violations in this repository, please
contact original author of this repository.
