# librespot patches

Fixes applied on top of the librespot commit or release checked out by `debian/rules`
(`LIBRESPOT_COMMIT_ID`, or `LIBRESPOT_VERSION` when the first is not set), in file name order, until they are released upstream.
Each one is a `git format-patch` export, so its message says what it fixes and
why.

When `LIBRESPOT_COMMIT_ID` or `LIBRESPOT_VERSION` moves, drop the patches the new commit or release already
contains, and check that the others still apply.
