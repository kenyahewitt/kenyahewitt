# Security Policy

## Supported Versions

Use this section to tell people about which versions of your project are
currently being supported with security updates.

| Version | Supported          |
| ------- | ------------------ |
| 5.1.x   | :white_check_mark: |
| 5.0.x   | :x:                |
| 4.0.x   | :white_check_mark: |
| < 4.0   | :x:                |

## Reporting a Vulnerability

Use this section to tell people how to report a vulnerability.

Tell them where to go, how often they can expect to get an update on a
reported vulnerability, what to expect if the vulnerability is accepted or
declined, etc.
sshd(8): On Cygwin, run as SYSTEM where possible, using S4U for
   token creation if it supports MsV1_0 S4U Logon.

 * sshd(8): On Cygwin, use custom user/group matching code that
   respects the OS' behaviour of case-insensitive matching.

 * sshd(8): Don't set $MAIL if UsePAM=yes as PAM typically specifies
   the user environment if it's enabled; bz#2937

 * sshd(8) Cygwin: Change service name to cygsshd to avoid collision
   with Microsoft's OpenSSH port.

 * Allow building against OpenSSL -dev (3.x)

 * Fix a number of build problems against version configurations and
   versions of OpenSSL. Including bz#2931 and bz#2921

 * Improve warnings in cygwin service setup. bz#2922

 * Remove hardcoded service name in cygwin setup. bz#2922

Checksums:
==========

 - SHA1 (openssh-8.0.tar.gz) = 8aaa99091fc7e5a92a4a320e1e5521046b3f95f0
 - SHA256 (openssh-8.0.tar.gz) = 1xvSJk1KYSnOLPYEUzyCVwTEQ7MHOaCO65DzeNuuLdo=

 - SHA1 (openssh-8.0p1.tar.gz) = 756dbb99193f9541c9206a667eaa27b0fa184a4f
 - SHA256 (openssh-8.0p1.tar.gz) = vZQ4eeaUmOgDHra39E0IzcN9WaeraJqgtDcyDDSB/Wg=

Please note that the SHA256 signatures are base64 encoded and not
hexadecimal (which is the default for most checksum tools). The PGP
key used to sign the releases is available as RELEASE_KEY.asc from
the mirror sites.

Reporting Bugs:
===============

- Please read http://www.openssh.com/report.html
  Security bugs should be reported directly to openssh@openssh.com
