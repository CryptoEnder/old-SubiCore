Subi Core version 0.16.x is now available from:

  <https://subicore.org/bin/subi-core-0.16.x/>

This is a new major version release, including new features, various bugfixes
and performance improvements, as well as updated translations.

Please report bugs using the issue tracker at GitHub:

  <https://github.com/subi/subi/issues>

To receive security and update notifications, please subscribe to:

  <https://subicore.org/en/list/announcements/join/>

How to Upgrade
==============

If you are running an older version, shut it down. Wait until it has completely
shut down (which might take a few minutes for older versions), then run the
installer (on Windows) or just copy over `/Applications/SUBI-Qt` (on Mac)
or `subid`/`subi-qt` (on Linux).

The first time you run version 0.15.0 or newer, your chainstate database will be converted to a
new format, which will take anywhere from a few minutes to half an hour,
depending on the speed of your machine.

Note that the block database format also changed in version 0.8.0 and there is no
automatic upgrade code from before version 0.8 to version 0.15.0 or higher. Upgrading
directly from 0.7.x and earlier without re-downloading the blockchain is not supported.
However, as usual, old wallet versions are still supported.

Downgrading warning
-------------------

Wallets created in 0.16 and later are not compatible with versions prior to 0.16
and will not work if you try to use newly created wallets in older versions. Existing
wallets that were created with older versions are not affected by this.

Compatibility
==============

Subi Core is extensively tested on multiple operating systems using
the Linux kernel, macOS 10.8+, and Windows Vista and later. Windows XP is not supported.

Subi Core should also work on most other Usubi-like systems but is not
frequently tested on them.

Notable changes
===============

Example item
-------------

Example item for a notable change.

0.16.x change log
------------------

(to be filled in at release time)

Credits
=======

Thanks to everyone who directly contributed to this release:

(to be filled in at release time)

As well as everyone that helped translating on [Transifex](https://www.transifex.com/projects/p/subi/).
