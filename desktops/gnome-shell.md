# GNOME Shell

## [Problem] Gnome Shell Drains CPU Resources On Fedora

### Description

After a clean install of Fedora, some users reported high CPU usage without obvious reasons. This problem was first noticed with Fedora 21 back in 2015, and questions about it still continue.

The causes may vary depending on the hardware in hand, but a lot of users reported that it was because of the GNOME Shell extension "Background Logo" which is enabled by default in Fedora. For some reason, it  doesn't play well with some graphic cards, thus leading to draining CPU resources.

### Solution

Install GNOME Tweak Tool and disable the "Background Logo" extension. Or remove that extension however you like.

### Additional Information

You may read the [following question](https://ask.fedoraproject.org/en/question/62522/gnome-shell-very-high-cpu-usage-on-a-clean-install-f21/) on Ask Fedora.
