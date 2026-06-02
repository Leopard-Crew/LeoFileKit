# LeoFileKit

LeoFileKit is a small native file object semantics brick for MacOS 10.5.8 Leopard PPC.

A Leopard file is not merely a path to bytes.
It is a Mac file object with filesystem, metadata, Finder, and Launch Services semantics.

So LeoFileKit does not replace HFS+, NSFileManager, Carbon File Manager, POSIX,
Launch Services, or xattr APIs.

Its purpose is to expose a consistent layer for treating files,
folders, bundles, and volumes as native Mac file objects rather than plain
byte streams.

LeoFileKit preserves and reports Leopard-relevant file semantics:
resource forks, Finder metadata, extended attributes, permissions, bundle
structure, HFS+ name behavior, volume capabilities, and safe write/replace
behavior.

