## SametSisartenep's public key

It's based on Elliptic Curve Cryptography, so maybe you'll need to update
your GnuPG version in order to use it.

> GPG 2.1.9

### Info

I cloned the GnuPG's libgcrypt repo from `git://git.gnupg.org/libgcrypt.git`
and installed it manually to get Ed25519 working from master branch (v1.7.x).
You'll need libgpg-error (v1.20) installed in your system to get it working
too.
You can download it from [ftp://ftp.gnupg.org/gcrypt/libgpg-error](http://ftp.gnupg.org/gcrypt/libgpg-error/).

Reference: [Creating newer ECC keys for
GnuPG](http://www.gniibe.org/memo/software/gpg/keygen-25519.html)

### PGP Public Key
([file](https://raw.githubusercontent.com/SametSisartenep/gpg-public-key/master/7BAD7C59.asc))

```txt
-----BEGIN PGP PUBLIC KEY BLOCK-----

mDMEVjaZiRYJKwYBBAHaRw8BAQdA2FhYSlMMgXf7x/5vyEyeAVAe3T5fhvFEbpKn
m6FR/3i0Q1JvZHJpZ28gR29uesOhbGV6IEzDs3BleiAoU2FtZXRTaXNhcnRlbmVw
KSA8cm9kcmlnb3Nsb29wQGdtYWlsLmNvbT6IfwQTFgoAJwUCVjaZiQIbAwUJAeEz
gAULCQgHAwUVCgkICwUWAgMBAAIeAQIXgAAKCRAeo67Fe618WQYGAQDSA92yHzTu
2IScOiT/Qg9CBcALRb41Q/qyEREG6dhh6gD9Fvjn7KzGeoku4infwE60xP+dtuIB
vNzenUt1SgZmVgu4OARWNpmJEgorBgEEAZdVAQUBAQdAes0namkSMf2hcOOqjhGs
jrcLBDrIRFVYWtmnoLZIQyIDAQgHiGcEGBYKAA8FAlY2mYkCGwwFCQHhM4AACgkQ
HqOuxXutfFlQyAEArK+FTnUNwBcrwfZWk84OSkIXW/pKkysxsA2WZ8hmmq0A/2/7
vZzv7e7lil/2FbupE4IULFCdeAubDmtSBlyIozEJ
=qDCP
-----END PGP PUBLIC KEY BLOCK-----
```

### PGP Fingerprint

```txt
C597 23E7 A766 EB85 9D72  6F49 1EA3 AEC5 7BAD 7C59
```

> Rodrigo González López (SametSisartenep)
