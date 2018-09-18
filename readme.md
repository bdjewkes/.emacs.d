Expects an org-directory to be initialized in a non-source controlled file to allow for system-specific configurations, ie:


;; Loads configuration from source controlled directory
(setq user-init-file "C:/Users/Brian/.emacs.d/init.el")
(setq org-directory "C:/Users/Brian/Dropbox/org/")
(load user-init-file)
