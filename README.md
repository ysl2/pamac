# Pamac

> NOTE: This version is patched for colorizing output.
>
> Reference: https://forum.manjaro.org/t/colorizing-pamac-on-the-cli/70219/7

Pamac is a Gtk and CLI front ends of libpamac

#### Features

 - pamac: an easy CLI
 - pamac-manager: a Gtk3 GUI
 - pamac-tray: a Gtk3 tray icon with updates notifications
 - pamac-tray-appindicator: a AppIndicator tray icon with updates notifications
 - pamac updates indicator: a gnome-shell extension with updates notifications

#### Installing from source

1. Dependencies

    ```text
    meson
    vala
    asciidoc
    ```

2. Pamac uses [Meson](http://mesonbuild.com/index.html) build system.
In the source directory run:

    `mkdir builddir && cd builddir`

    `meson setup --prefix=/usr --sysconfdir=/etc --buildtype=release`

    `meson compile`

    `sudo meson install`

