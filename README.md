# fnf_to_sm
Fork of ![shockdude's fnf-to-sm](https://github.com/shockdude/fnf-to-sm).

## What's new?
- The repository has been reformatted to work like a Python module, for ![mod_to_sm](https://github.com/rsrunner/mod_to_sm).
- sm_to_fnf
- - Added support for `dance-double`.
- - - Comes with automatic `must_hit_section` algorithm
- - Add the option to choose difficulties through the command line
- fnf_to_sm
- - Support for Tricky mines
- - Added `dance-single` support, multiplexing both players into an one-player chart

## Usage
`python main.py chart(.json|.sm) (difficulty)`
where `difficulty` can be a Stepmania difficulty, if .sm is provided.