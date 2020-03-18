```
$ gpg --version
gpg (GnuPG) 2.2.19
libgcrypt 1.8.5
```

- ascii armored to gpg binary packets:

      gpg --dearmor --out RPM-GPG-KEY-CentOS-7.gpg RPM-GPG-KEY-CentOS-7

- verify and return message with attached signature:

      gpg --no-default-keyring --keyring ./RPM-GPG-KEY-CentOS-7.gpg --decrypt sha256sum.txt.asc

- verify signed message with detached signature:

      gpg --no-default-keyring --keyring ./fedora.bin --verify fedora-coreos-31.20200223.3.0-live.x86_64.iso.sig fedora-coreos-31.20200223.3.0-live.x86_64.iso
