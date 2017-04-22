## NLOscillator ##

Van der Pol and Duffing oscillator UGens. Forked from [SWUGens](http://www2.informatik.hu-berlin.de/~oberthol/SWUGens-0.01/) by Oswald Berthold.

## Installation

OS X and Linux:

    mkdir build && cd build
    cmake -DSC_PATH="/path/to/supercollider/" ..
    make

Here, `/path/to/supercollider/` is the path to a directory of the SuperCollider source code. The path should contain a file at `include/plugin_interface/SC_PlugIn.h`. If you get a warning that `SC_PlugIn.h` could not be found, then `SC_PATH` is not set correctly.

After building, install the directory as you would a quark. You can copy/move/symlink it in your Extensions directory, or go to `Quarks.gui` > Install a folder.
