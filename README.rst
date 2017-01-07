=====================
Custom MacPorts ports
=====================


Ports
=====

- ``aqua/MenuMeters``: With macOS 10.12 support.
- ``graphics/poppler``: Without ``gobject-introspection`` dependency.


Installation
============

- Clone this somewhere as ``root``.
- Prepend the above cloned path into ``/opt/local/etc/macports/sources.conf``.
  Order matters since we want the custom repository to be accessed first.

``port`` will pull the latest from this repository whenever it updates itself.
