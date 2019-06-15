Trinacoin integration/staging tree
================================

trinacoinproject@gmail.com

Copyright (c) 2009-2014 Bitcoin Developers
Copyright (c) 2011-2014 Litecoin Developers
Copyright (c) 2019 Trinacoin Developer

What is Trinacoin?
----------------

Trinacoin is a lite version of Bitcoin using scrypt as a proof-of-work algorithm.
 - 2 minute block targets
 - subsidy halves in 400k blocks (~1.5 year)
 - 30 million total coins
 - 40 coins per block
 - 2160 blocks to retarget difficulty

For more information, as well as an immediately useable, binary version of
the Trinacoin client sofware, ask trinacoinproject@gmail.com.

License
-------

Trinacoin is released under the terms of the MIT license. See `COPYING` for more
information or see http://opensource.org/licenses/MIT.


Download Windows Binaries
------------

https://github.com/trinacoin/trinacoin/releases/download/v1.1/trinacoin-v1.1-0.8.7.5-win32-setup.exe


Installation (Linux)
--------------------

git clone "https://github.com/trinacoin/trinacoin.git"

qmake

make

Development process
-------------------

Developers work in their own trees, then submit pull requests when they think
their feature or bug fix is ready.

If it is a simple/trivial/non-controversial change, then one of the Trinacoin
development team members simply pulls it.

If it is a *more complicated or potentially controversial* change, then the patch
submitter will be asked to start a discussion with the devs and community.

The patch will be accepted if there is broad consensus that it is a good thing.
Developers should expect to rework and resubmit patches if the code doesn't
match the project's coding conventions (see `doc/coding.txt`) or are
controversial.

The `master` branch is regularly built and tested, but is not guaranteed to be
completely stable. [Tags](https://github.com/trinacoin/trinacoin/tags) are created
regularly to indicate new official, stable release versions of Trinacoin.
