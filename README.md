Description
===========

Brought to my attention here: http://www.cfd-online.com/Forums/openfoam/105601-transient-simplefoam.html

Original source code version from here: http://openfoamwiki.net/index.php/Main_ContribExamples/PISOvsTransientSimple

This repository brings you minor adjustments to this code for keeping up with
the latest OpenFOAM releases.

Keep in mind that this is a contribution made in the community and not part of
OpenFOAM(R). Furthermore, this is not a solver meant to be used as a final
solver, this is only for educational purposes, so use it at your own risk or
contribute/sponsor to it to standardize and validate the implementation.

'''Note regarding versions''':

  * The `master` branch works fine with OpenFOAM 1.7.x, 2.0.x, 2.1.x and 2.2.x.
    It also works with 1.6-ext.

  * The branch `OF23` works with OpenFOAM 2.3.x and 2.4.x.

  * The branch `OF30` works with OpenFOAM 3.0.x.

  * The branch `OF4` works with OpenFOAM 4, 5 and 6.


This repository at https://github.com/wyldckat/transientSimple was brought to
you by Bruno Santos (wyldckat@github working at [FSD blueCAPE Lda](http://www.bluecape.com.pt)).


License
=======

This is bound to the same license as OpenFOAM, namely GPLv3. Which means that
you can redistribute it and/or modify it under the terms of the GNU General
Public License as published by the Free Software Foundation, either version 3 of
the License, or (at your option) any later version.
See http://www.gnu.org/licenses/ for more information about GPL.


Downloading for the correct OpenFOAM version
============================================

Before continuing, first go to your user folder:

```
mkdir -p $FOAM_RUN
cd $FOAM_RUN/..
```

Then follow the instructions for the OpenFOAM version you want to use:


OpenFOAM 1.7.x, 2.0.x, 2.1.x and 2.2.x, as well as foam-extend 1.6-ext
----------------------------------------------------------------------

Download, either using `git` or use the *Downloads* pseudo-button on the
top right at https://github.com/wyldckat/transientSimple - or simply follow
these instructions:

* For using `git`, clone the repository by using the following commands:

  ```
  git clone https://github.com/wyldckat/transientSimple.git
  cd transientSimple
  ```

* For using ZIP, download and unpack a snapshot of the repository by using
the following commands:

  ```
  wget https://github.com/wyldckat/transientSimple/archive/master.zip -O transientSimple-master.zip
  unzip transientSimple-master.zip
  mv transientSimple-master.zip transientSimple
  cd transientSimple
  ```


OpenFOAM 2.3.x and 2.4.x
------------------------

Download, either using `git` or use the *Downloads* pseudo-button on the
top right at https://github.com/wyldckat/transientSimple - or simply follow
these instructions:

* For using `git`, clone the repository by using the following commands:

  ```
  git clone https://github.com/wyldckat/transientSimple.git
  cd transientSimple
  git checkout OF23
  ```

* For using ZIP, download and unpack a snapshot of the repository by using
the following commands:

  ```
  wget https://github.com/wyldckat/transientSimple/archive/OF23.zip -O transientSimple-OF23.zip
  unzip transientSimple-OF23.zip
  mv transientSimple-OF23.zip transientSimple
  cd transientSimple
  ```


OpenFOAM 3.0.x
--------------

Download, either using `git` or use the *Downloads* pseudo-button on the
top right at https://github.com/wyldckat/transientSimple - or simply follow
these instructions:

* For using `git`, clone the repository by using the following commands:

  ```
  git clone https://github.com/wyldckat/transientSimple.git
  cd transientSimple
  git checkout OF30
  ```

* For using ZIP, download and unpack a snapshot of the repository by using
the following commands:

  ```
  wget https://github.com/wyldckat/transientSimple/archive/OF30.zip -O transientSimple-OF30.zip
  unzip transientSimple-OF30.zip
  mv transientSimple-OF30.zip transientSimple
  cd transientSimple
  ```


OpenFOAM 4.x, 5.x and 6
-----------------------

Download, either using `git` or use the *Downloads* pseudo-button on the
top right at https://github.com/wyldckat/transientSimple - or simply follow
these instructions:

* For using `git`, clone the repository by using the following commands:

  ```
  git clone https://github.com/wyldckat/transientSimple.git
  cd transientSimple
  git checkout OF4
  ```

* For using ZIP, download and unpack a snapshot of the repository by using
the following commands:

  ```
  wget https://github.com/wyldckat/transientSimple/archive/OF4.zip -O transientSimple-OF4.zip
  unzip transientSimple-OF4.zip
  mv transientSimple-OF4.zip transientSimple
  cd transientSimple
  ```


Building with OpenFOAM
======================

  2. Run:

     ```
     wmake transientSimpleFoam
     ```

  3. Clean up:

     ```
     wclean transientSimpleFoam
     ```

  4. Go to the page http://openfoamwiki.net/index.php/Main_ContribExamples/PISOvsTransientSimple to continue learning how to use this solver.


