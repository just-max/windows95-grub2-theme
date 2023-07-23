GRUB2 Theme: Windows 95
-----------------------
The Windows 95 GRUB2 theme is a GRUB2 theme in the style of Windows 95.

Installing
----------

The process is the same as for any GRUB2 theme.

(1) Clone (or download and unpack) the content of this repository.
(2) Copy the content of the 'theme/' folder to '/etc/grub/themes/win95/',
or the correct path for your system.
(3) Modify your GRUB2 config to include the following line:

        GRUB_THEME=/usr/share/grub/themes/win95/theme.txt

How you modify your GRUB2 config depends on how your system is configured.
On Debian systems, that typically means editing '/etc/default/grub' and
then following the hint given there:

        # If you change this file, run 'update-grub' afterwards to update
        # /boot/grub/grub.cfg.

What's Inside
-------------

The Windows 95 GRUB2 theme uses a couple of other great projects.

This project includes the W95FA font by Alina Sava:

        Re-created after the default Windows 95 font (MS Sans Serif),
        W95FA is a free Windows 95 font complete with pixel style.
        The original MS Sans Serif was a a proportional raster font,
        but W95FA is a proper scalable .otf.

W95FA is licensed under the SIL Open Font License.

It also uses the wonderful Less Perfect DOS VGA by Adam Moore (LÆMEUR),
based on the work of Zeh Fernando, an emulation of the 80/25 text screen
used on VGA monitors

Less Perfect DOS VGA is "free for all use, commercial and non-commercial."

The background image (theme/desktop.png) was included in the original
distribution of Windows 95, and is likely still protected by copyright.
I am not aware of any attempts to enforce this copyright though.

W95FA: <https://w95font.com/>
Less Perfect DOS VGA: <https://laemeur.sdf.org/fonts/>

Warning: Beware of Rabbit Holes

Licence
-------

The Windows 95 GRUB2 theme itself (anything not listed under "What's Inside")
is licensed under the Mozilla Public License, Version 2.0.

Further Material
----------------

You can preview this theme, or any of your own tweaks, using the GRUB2 Theme
Preview utility <https://github.com/hartwork/grub2-theme-preview>.

+-<*>-+<[@]>+-<*>-+-<*>-+-<*>-+-<*>-+<[@]>+-<*>-+-<*>-+-<*>-+-<*>-+<[@]>+-<*>-+
