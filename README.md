AntiMicroX Profiles
==================

This repository contains AntiMicroX profiles that can be used to provide
controller support for desktop applications and computer games that do not
provide controller support or that provide poor support.

Currently, the layout of the repository is the following:

    applications -> APPLICATION -> Controller UniqueID / Controller GUID -> PROFILE

Most applications will have profiles that are mapped against the special
SDL Game Controller API. The GUID that will be used in this repository for
this case is **sdlgamecontroller**.To find the GUID/UniqueID for your controller,
open AntiMicroX and then go to Options -> Properties. The GUID/UniqueID of your
controller will be listed in the Properties window.

If you compile AntiMicro from source, you must be using a version of AntiMicro
that was compiled with SDL 2 support. This will also require that you use at
least AntiMicro version 2.0 in order to use an sdlgamecontroller profile.

Once you have finished your changes, please submit a pull request
and I will review your changes. Once your changes have been reviewed and
nothing is wrong with the submission, I will accept the changes.

<br/>

## Rules

1. Create a new directory in "applications" containing the game title
2. Name properly your file - the title of game
3. For each assigned button write some action name (If you don't know how, go to [ProfileTips.md](https://github.com/juliagoda/antimicroX-profiles/blob/master/ProfileTips.md) file)
