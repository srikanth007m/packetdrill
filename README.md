# packetdrill #

The web site for packetdrill is here:

> https://code.google.com/p/packetdrill/

The USENIX 2013 paper describing the tool and our team's experiences
using it may be found here:

> http://research.google.com/pubs/pub41316.html

# building #

To build packetdrill, first install flex and bison.

Then set up the Makefile for your platform:

```
# ./configure
```

Then build the tool:

```
#  make
```

# running #

Here's a quick example.

On FreeBSD, OpenBSD, and NetBSD, try:

```
# ./packetdrill tests/bsd/fast_retransmit/fr-4pkt-sack-bsd.pkt 
```

On Linux try:

```
# ./packetdrill  tests/linux/fast_retransmit/fr-4pkt-sack-linux.pkt 
```

To run all the Linux tests:
```
# cd tests/linux/
# ./run_tests.sh
```

# license #

The packetdrill tool is released under version 2 of the GPL. See the
COPYING file for full details.


# discussion and contributions #

If you have any questions, or code or patches to offer, please join
the packetdrill e-mail list at:

> http://groups.google.com/group/packetdrill

Contributions of code or tests are both welcomed!

Enjoy!