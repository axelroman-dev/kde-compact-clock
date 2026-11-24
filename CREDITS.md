# Credits

## Maintainer

- [axelroman-dev](https://github.com/axelroman-dev) — Plasma 6.8 port and maintenance

## Original author

- [N0repi](https://github.com/N0repi) · [norepi.dev](https://norepi.dev) — Compact Clock for Plasma 6
  ([original repo](https://github.com/N0repi/kde-compact-clock))

## Upstream

Compact Clock is derived from the **Plasma Digital Clock** applet in
[plasma-workspace](https://invent.kde.org/plasma/plasma-workspace)
(reference snapshot: v6.7.3, updated with v6.8.3 changes).

Original Digital Clock authors include (non-exhaustive):

- Martin Klapetek
- Heena Mahour
- Sebastian Kügler
- David Edmundson
- Bhushan Shah
- Kai Uwe Broulik
- ivan tkachenko
- Carl Schwan

See SPDX headers in individual source files for per-file copyright.

## Inspiration

Single-line panel layout ideas were inspired by
[Better Inline Clock](https://www.pling.com/p/1245902)
([repo](https://github.com/MarianArlt/kde-plasmoid-betterinlineclock))
(Marian Arlt et al.), a Plasma 5 plasmoid.

## Runtime dependency

This plasmoid imports `org.kde.plasma.private.digitalclock` and
`org.kde.plasma.clock`, which ship with Plasma. Those modules are
**private** APIs and may change between Plasma releases.
