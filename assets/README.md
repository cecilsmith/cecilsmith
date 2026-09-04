# Icon assets

Every icon in the profile README is served from this directory rather than from a
third-party badge service, so the profile keeps rendering if one of those services
goes away.

All tiles are 256x256 SVGs with a 60px corner radius, so they line up on one
baseline at one size when the README sets `height="48"`.

## Sources

| File              | Mark           | Source                                                                            | License       |
| ----------------- | -------------- | --------------------------------------------------------------------------------- | ------------- |
| `c.svg`           | C              | [tandpfun/skill-icons](https://github.com/tandpfun/skill-icons)                   | MIT           |
| `cpp.svg`         | C++            | tandpfun/skill-icons                                                              | MIT           |
| `rust.svg`        | Rust           | tandpfun/skill-icons                                                              | MIT           |
| `python.svg`      | Python         | tandpfun/skill-icons                                                              | MIT           |
| `csharp.svg`      | C#             | tandpfun/skill-icons                                                              | MIT           |
| `javascript.svg`  | JavaScript     | tandpfun/skill-icons                                                              | MIT           |
| `java.svg`        | Java           | tandpfun/skill-icons                                                              | MIT           |
| `arduino.svg`     | Arduino        | tandpfun/skill-icons                                                              | MIT           |
| `raspberrypi.svg` | Raspberry Pi   | tandpfun/skill-icons                                                              | MIT           |
| `linux.svg`       | Linux          | tandpfun/skill-icons                                                              | MIT           |
| `rhel.svg`        | Red Hat        | tandpfun/skill-icons                                                              | MIT           |
| `nodejs.svg`      | Node.js        | tandpfun/skill-icons                                                              | MIT           |
| `vue.svg`         | Vue            | tandpfun/skill-icons                                                              | MIT           |
| `unity.svg`       | Unity          | tandpfun/skill-icons                                                              | MIT           |
| `podman.svg`      | Podman         | [devicons/devicon](https://github.com/devicons/devicon)                           | MIT           |
| `flightctl.svg`   | Flight Control | [flightctl/flightctl](https://github.com/flightctl/flightctl)                     | Apache-2.0    |
| `bootc.svg`       | bootc          | [bootc-dev/bootc-dev.github.io](https://github.com/bootc-dev/bootc-dev.github.io) | none declared |

## Notes on the three composed tiles

Podman, Flight Control, and bootc have no tile in skill-icons, so those three were
built here on a `#242938` background to match the set.

`flightctl.svg` comes from `internal/auth/oidc/pam/templates/flight-control-logo.svg`
in the Flight Control repository.

`bootc.svg` comes from `static/logo.png` on the bootc project site, cropped above
the wordmark and embedded as a PNG. The upstream logo is raster, so this tile is
the one in the set that is not vector art.

The bootc site repository declares no license. The logo is used here the same way
every other mark in this directory is, to show a tool used.

All marks belong to their respective projects. Their presence here is not a claim
of affiliation or endorsement.
