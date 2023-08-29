# hypr-ansible
This ansible playbook is meant for post installation configuration of a linux arch system.
If you want to use this playbook, note that it
1. Creates a custom x11 keymap which is a mixture of the de and us keymap
2. Changes the SDDM theme and enables autologin to a hyprland session of user "mainuser"
3. installs (but not removes) a bunch of packages.
4. it was build for my personal use and so has many configuration that may only apply for my needs