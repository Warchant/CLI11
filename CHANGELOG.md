## Version 0.2

* Moved to simpler syntax, where `Option` pointers are returned and operated on
* Removed `make_` style options
* Simplified Validators, now only requires `->check(function)`
* Removed Combiners
* Fixed pointers to Options, stored in `unique_ptr` now
* Added `Option_p` and `App_p`, mostly for internal use
* Startup sequence, including help flag, can be modified by subclasses

## Version 0.1

Initial version

