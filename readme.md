A simple canvas line drawing to play with fourier transforms of hand
drawn line paths.

All code was written by GPT4. -- However, it really wanted to use a
library to do the fourier transforms, and it kept making mistakes
trying to use them.  Once it started explaining to me how Fourier
transforms worked, I told it to just implement one from scratch and it
worked on the first try.

The UI is terrible and needs some path management logic.

Start a drawing around the center and then drop fourier terms that are
below a certain amplutide or above the max frequency.


