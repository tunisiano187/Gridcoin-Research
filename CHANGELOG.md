# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]
### Added
 - Add RPC commands for changing debug flags: debug, debugnet, debug2, debug3,
   debug4, debug5, debug10. #309 (@Foggyx420).
 - Add support for themes via stylesheets, #233 (@skcin).
 - Add support for OpenSSL 1.1.x, #164.

### Changed
 - Wallet overview cleanup, #233 (@skcin)
   - The main overview page is now cleaner, more structured and holds more of
     the recent transactions.
   - Displayed DPOR weight should now be accurate. , #233 (@skcin).
 - Show as many of the recent transactions as we can fit.
 - Update Portuguese translations (Miguel Veiga).

## [3.5.8.9] - 2017-05-15
### Added
- Implement voting functionality for Linux and OSX (@skcin).

### Changed
- Windows are now resizable 
- Replace Windows voting dialog with the new dialog.
- Update Gridcoin icon on Windows.
- Enable C++11.
- Update Hungarian translations (@matthew11).
- Update Portuguese translations (Miguel Veiga).
- Update icon set by @Peppernrino.
- Update icon on OSX, #193 (@coagmano).
- Reduced memory usage by around 100MB+.
- Improve UI when used with dark themes on Linux, #222 (@skcin).
- Fix occasional crashes when starting on Linux, #139.
- Fix freeze when clicking on the "Amount" field under Send Coins when using
  KDE, #210.
- Fix OSX build issues, #174 (@coagmano).
- Possible fix for invalid time check in diagnostic.