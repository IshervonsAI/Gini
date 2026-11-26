# Security

Please report a security problem privately: email security@ishervonsai.eu.org, or use Security → Report a vulnerability on this repository. Do not open a public issue.

Include what you found, how to reproduce it, and the IVC version (ivc version). We reply within 7 days. Please give us a reasonable time to fix it before you tell anyone else.

How releases are protected: every release's checksum list (SHA256SUMS) is signed with the IshervonsAI release key (SHA256SUMS.sig, RSA-3072). The installers refuse a release whose signature or any file checksum does not match, and pin the exact versions and checksums of every tool they download (PREREQS.txt, itself covered by the signature).
