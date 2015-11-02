# dash-docset-matlab
This is a [dashing](https://github.com/technosophos/dashing#readme)
configuration file to help generate dash docset for Matlab.

Matlab documentation was removed from dash official feeds at the request of MathWorks.
But what's the matter if I just post a json here!

# Steps to generate the docset
+ Install [dashing](https://github.com/technosophos/dashing#readme)
+ `cd MATLAB_ROOT/help`
+ `cp THIS_REPO/dashing.json .`
+ edit `dashing.json` if not using Matlab R2014b
+ `dashing build`

Right now this json only roughly parses some function names (which is enough for me to use).
Feel free to add more and contribute back!
