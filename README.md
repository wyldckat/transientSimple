Description
===========

Brought to my attention here: http://www.cfd-online.com/Forums/openfoam/105601-transient-simplefoam.html

Original source code version from here: http://openfoamwiki.net/index.php/Main_ContribExamples/PISOvsTransientSimple

This repository brings you minor adjustments to this code for keeping up with the latest OpenFOAM releases. After you run `git clone`, use `git branch -a` to see what OpenFOAM versions have been tested.

'''Note''': The master branch works fine with OpenFOAM 1.7.x, 2.0.x and 2.1.x. It also works with 1.6-ext.

Keep in mind that this is a contribution made in the community and not part of OpenFOAM(R).

This repository at https://github.com/wyldckat/transientSimple was brought to you by Bruno Santos (wyldckat@github working at [FSD blueCAPE Lda](http://www.bluecape.com.pt)).


License
=======

This is bound to the same license as OpenFOAM, namely GPLv3. Which means that you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.
See http://www.gnu.org/licenses/ for more information about GPL.


Building with OpenFOAM
======================

  0. Go to your user folder:

     ```
     mkdir -p $FOAM_RUN
     cd $FOAM_RUN/..
     ```

  1. Download, either using `git` or use the ''Downloads'' pseudo-button on the top right at https://github.com/wyldckat/transientSimple - or simply follow these instructions:

    * For using `git`, clone the repository by using the following commands:

      ```
      git clone https://github.com/wyldckat/transientSimple.git
      cd transientSimple
      ```

    * For using ZIP, download and unpack a snapshot of the repository by using the following commands:

      ```
      wget https://github.com/wyldckat/transientSimple/archive/master.zip -O transientSimple-master.zip
      unzip transientSimple-master.zip
      mv transientSimple-master.zip transientSimple
      cd transientSimple
      ```

  2. Run:

     ```
     wmake transientSimpleFoam
     ```

  3. Clean up:

     ```
     wclean transientSimpleFoam
     ```

  4. Go to the page http://openfoamwiki.net/index.php/Main_ContribExamples/PISOvsTransientSimple to continue learning how to use this solver.


