ConfessionCoin integration/staging tree
=======================================

http://www.confessioncoin.com

Copyright (c) 2009-2013 Bitcoin Developers
Copyright (c) 2011-2013 Litecoin Developers
Copyright (c) 2014-2014 ConfessionCoin Developers

What is ConfessionCoin?
----------------

Confession is an alternative version of Bitcoin using scrypt as a proof-of-work algorithm.
 - 45 second block targets
 - no subsidy halves
 - ~70 million total coins

For more information, as well as an immediately useable, binary version of
the Litecoin client sofware, see http://www.confessioncoin.com.

License
-------

Confessioncoin is released under the terms of the MIT license. See `COPYING` for more
information or see http://opensource.org/licenses/MIT.

Development process
-------------------

Developers work in their own trees, then submit pull requests when they think
their feature or bug fix is ready.

If it is a simple/trivial/non-controversial change, then one of the ConfessionCoin
development team members simply pulls it.

If it is a *more complicated or potentially controversial* change, then the patch
submitter will be asked to start a discussion (if they haven't already) on the
ConfessionCoin thread on bitcointalk.org

The patch will be accepted if there is broad consensus that it is a good thing.
Developers should expect to rework and resubmit patches if the code doesn't
match the project's coding conventions (see `doc/coding.txt`) or are
controversial.

The `master` branch is regularly built and tested, but is not guaranteed to be
completely stable. [Tags](https://github.com/confessioncoin/confessioncoin/tags) are created
regularly to indicate new official, stable release versions of ConfessionCoin.

Testing
-------

Testing and code review is the bottleneck for development; we get more pull
requests than we can review and test. Please be patient and help out, and
remember this is a security-critical project where any mistake might cost people
lots of money.