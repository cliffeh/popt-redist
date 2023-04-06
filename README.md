# popt-redist
a redistributable version of the popt argument parsing library 

## Motivations
[popt](https://github.com/rpm-software-management/popt) is an excellent argument parsing library - full-featured, battle-hardened (it's been around for decades now), etc. It is also widely-available at this point..._but_:

* It is not included by default on all distributions/platforms, and
* Even when libpopt is included by default, the development headers (required for building software from source) often are _not_

This repo is an attempt to repackage popt such that it can be "parachuted" into a development project with minimal refactoring/hassle. It's not so much making it "redistributable" - popt's [license](COPYING) already allows for that - it's more about making it readily re-packageable.
