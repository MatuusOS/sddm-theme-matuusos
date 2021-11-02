#-*- mode: org -*-
#+STARTUP: showall

* MatuusOS SDDM config

You reached a repo for MatuusOS SDDM theme! MatuusOS SDDM theme is for MatuusOS, but you can use it on any distro that has SDDM display manager.

* How to install it:
  * Arch/Archbased distros: 
  #+ begin_src python
  
  yay -S sddm-theme-matuusos
  
  #+end_src
  * Debian/Debian-based distros:
  #+ begin_src python
  
  git clone https://github.com/MatusModder/sddm-theme-matuusos.git
  cd sddm-theme-matuusos
  makedeb -si
  
  #+ end_src
  * NOTE: You must edit a file called sddm.conf by typing: 
  
 
