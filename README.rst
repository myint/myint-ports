=====================
Custom MacPorts ports
=====================


Ports
=====

- ``aqua/iTerm2``: Older version that builds on OS X 10.11.
- ``graphics/poppler``: Without ``gobject-introspection`` dependency.


Installation
============

- Clone this somewhere as ``root``.
- Prepend the above cloned path into ``/opt/local/etc/macports/sources.conf``.
  Order matters since we want the custom repository to be accessed first.

``port`` will pull the latest from this repository whenever it updates itself.
