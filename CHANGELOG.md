# Revision history for nix-thunk

## 0.3.0.0

* Fix readThunk when thunk is checked out [#4](https://github.com/obsidiansystems/nix-thunk/pull/4)
* Fix removal of .git from default destination [#10](https://github.com/obsidiansystems/nix-thunk/pull/10)

## 0.2.0.3

* Default to GHC 8.8.4 and update dependency bounds

## 0.2.0.2
* Add support for GHC 8.8.4.

## 0.2.0.1
* Fix parsing of --rev arguments

## 0.2.0.0
* Add nix-thunk create.  This caused some minor breakage to the Haskell library API, but not the Nix or command line interfaces.

## 0.1.0.0
* Initial release.  Extracted the Nix part of this code from https://github.com/obsidiansystems/reflex-platform and the Haskell part from https://github.com/obsidiansystems/obelisk
