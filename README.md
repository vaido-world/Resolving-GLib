# Resolving-GLib

https://askubuntu.com/questions/58321/how-do-i-install-glib

```
MakeRecipe "GLib" "2.68.4" "https://gitlab.gnome.org/GNOME/glib/-/archive/2.68.4/glib-2.68.4.tar.bz2"

InstallPackage --same "remove" "https://github.com/vaido-world/resolving-util-linux/raw/main/Util-Linux--2.35.1--x86_64.tar.bz2"
InstallPackage https://gobolinux.org/packages/017/Fuse--2.9.7--x86_64.tar.bz2
InstallPackage https://gobolinux.org/packages/017/UnionFS-Fuse--2.1--x86_64.tar.bz2
Compile "GLib" "2.68.4" 
```


# Checking if version installed and exists.
```
root@LiveCD ~]cd /Programs/GLib
root@LiveCD /Programs/GLib]ls
2.63.5  2.68.4  Current

```
