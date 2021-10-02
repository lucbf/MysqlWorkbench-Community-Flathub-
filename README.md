Building Mysql Workbench Community from sources. I'm sorry I couldn't get past which should be the last roadblock to fully compile the program. The linker throws the error:

/usr/bin/ld: /run/build/mysql-workbench/library/parsers/libparsers.so.8.0.26: undefined reference to `antlr4::ANTLRInputStream::ANTLRInputStream(std::basic_string_view<char, std::char_traits >)'

At Workbench's 90% build process. I'm posting this in case there's someone who wishes to pick up the job.

# Flathub

Flathub is the central place for building and hosting Flatpak builds.

Using the Flathub repository
----------------------------

To install applications that are hosted on Flathub, use the following:
```
flatpak remote-add flathub https://flathub.org/repo/flathub.flatpakrepo
flatpak install flathub org.gnome.Recipes
```

To install applications from the beta branch, use the following:
```
flatpak remote-add flathub-beta https://flathub.org/beta-repo/flathub-beta.flatpakrepo
flatpak install flathub-beta org.godotengine.Godot
```

For more information and more applications see https://flathub.org

Contributing to Flathub
-----------------------

For information on creating packages or reporting issues please see the [contributing page](/CONTRIBUTING.md).

***Note:*** *this repository is not for reporting issues related to the flathub.org website itself or contributing to its development. For that, go to https://github.com/flathub/linux-store-frontend*
