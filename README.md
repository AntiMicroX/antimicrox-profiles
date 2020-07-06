AntiMicroX Profiles
==================

This repository contains AntiMicroX profiles that can be used to provide
controller support for desktop applications and computer games that do not
provide controller support or that provide poor support.

Currently, the layout of the repository is the following:

    applications -> APPLICATION -> Controller GUID -> PROFILE or ARCHIVE (tar.gz or tar.bz2)

Most applications will have profiles that are mapped against the special
SDL Game Controller API. The GUID that will be used in this repository for
this case is **sdlgamecontroller**.To find the GUID for your controller,
open AntiMicroX and then go to Options -> Properties. The GUID of your
controller will be listed in the Properties window.

If you compile AntiMicro from source, you must be using a version of AntiMicro
that was compiled with SDL 2 support. This will also require that you use at
least AntiMicro version 2.0 in order to use an sdlgamecontroller profile.

If you would like to submit a profile to this repository, please clone this
repository and place the XML file in the appropriate place. You also have the
option to create an archive file in either tar.gz or tar.bz2 format. Zip files
will **not** be accepted. Archives can be used to include a profile along
with supplementary files like a README, a controller mapping reference image,
and any configuration files that might be needed to change the bindings
in a game. Please do not include any exe files or the profile will
be rejected.

Once you have finished your changes, please submit a pull request
and I will review your changes. Once your changes have been reviewed and
nothing is wrong with the submission, I will accept the changes.
