# dash-docset-matlab
This is a [dashing](https://github.com/technosophos/dashing#readme)
configuration file to help generate dash/zeal docset for Matlab.

Matlab documentation was removed from dash official feeds at the request of MathWorks.
But what's the matter if I just put a json here!

# Steps to generate the docset
+ Install [dashing](https://github.com/technosophos/dashing#readme)
+ `cd MATLAB_ROOT/help`
+ `cp THIS_REPO/{dashing.json,icon.png} .`
+ Edit the version identifier in `dashing.json` if not using Matlab R2015b
+ `dashing build` will give you a `matlab.docset` folder.

Right now this json only roughly parses function names (which is enough for me to use).
Feel free to add more features and contribute!
