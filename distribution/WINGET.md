# Windows Package Manager submission

Package ID: `Karvo.LaunchPad` · launcher version: `1.0.0` · architecture: x64 · installation scope: current user.

The three manifests are in [winget/1.0.0](winget/1.0.0). They reference the official GitHub installer mirror and its verified SHA-256 hash. The installer is self-signed; Microsoft security/reputation checks may require further review.

The prepared upstream fork branch is https://github.com/dev2cge/winget-pkgs/tree/karvo-launchpad-1.0.0/manifests/k/Karvo/LaunchPad/1.0.0

Both the existing release credential and GitHub connector lack permission to open a pull request against microsoft/winget-pkgs. The submission is **not yet open or approved**. After the hosted Windows check passes and the branch is current, the owner can open the comparison at https://github.com/microsoft/winget-pkgs/compare/master...dev2cge:winget-pkgs:karvo-launchpad-1.0.0?expand=1

Do not advertise `winget install Karvo.LaunchPad` as available until Microsoft merges and indexes the package. This repository's checks verify manifest validity and installation metadata; they do not replace Microsoft's security review or gameplay testing.
