# Standard-Conventions
This repository is the place to establish Fesslab coding conventions. This is where contributors post standard conventions/formats/styles.

(1) use = instead of <- because the former is more common in other programming languages.

(2) avoid creating objects with a dot in the name and use the underscore instead (e.g. data_study1 instead of data.study1) because in many other languages dots in names create problems

(3) no magic numbers (a value that should be given a symbolic name, but was used as a literal). Example/ using "SCALE_REVERSAL_VALUE" instead of "8"---> loose floating constants such as "8" are potentially dangerous. 

(4) should we always load packages at the top of the script? or is it better to load in the line just above when the package is needed? perhaps the latter is useful while the code is in development, but moving to the top is a polishing step?

