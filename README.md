# the Tractor

Probabilistic astronomical source detection & measurement

## authors & license

Copyright 2011-2013 Dustin Lang (CMU) & David W. Hogg (NYU)

Licensed under GPLv2; see LICENSE.

## install

To check out and build the code in a *tractor* directory:

    wget -O - https://raw.github.com/dstndstn/tractor/master/checkout.sh | bash
    cd tractor

Or if you prefer:

    # Grab and install the Astrometry.net code (http://astrometry.net/downloads)
    git clone git@github.com:dstndstn/tractor.git
    cd tractor
    make

It is possible to run directly out of the checked-out *tractor*
directory.  But if you want to install it:

    make
    python setup.py install # --prefix=/some/place    or maybe --home=/your/place

Prereqs:

* scipy (> 0.7; 0.9 works)
* numpy (>= 1.4)

## documentation:

Horribly incomplete, but online at http://thetractor.org/doc

## collaboration:

We are trying to move from a "Research code that only we use" phase to
"Research code that other people can use".  We are happy to hear your
feedback; please feel free to file Issues.  And naturally we will be
pleased to see pull requests!
