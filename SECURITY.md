To prevent Man-in-the-Middle (MitM) attacks and ensure the integrity of the software, this project strictly adheres to secure delivery protocols. It is requested that when pulling this repository you use HTTPS only, meaning all project artifacts, metadata, and cryptographic hashes are served exclusively over TLS (HTTPS).

in a coming release any plain HTTP requests to project domains will be automatically redirected to HTTPS to prevent downgrade attacks. Do not rely solely on transport security. All releases must be verified using the following chain of trust. Every release includes a checksum file (e.g., SHA256SUMS) that is digitally signed using a GPG/OpenPGP key.

Please do not report security vulnerabilities via public GitHub issues. 
Instead, please use [GitHub's Private Vulnerability Reporting](https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-a-vulnerability) 
feature available in this repository.

## Integrity Verification
All releases are accompanied by a `CHECKSUMS.txt.asc` file. 
You should verify the GPG signature before installing any binaries or scripts.

If you find a security issue, please contact me at 'robertb12905@gmail.com'.
