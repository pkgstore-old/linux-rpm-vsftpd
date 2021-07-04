# vsftpd

**vsftpd** is a Very Secure FTP daemon. It was written completely from scratch.

## Install

### Fedora COPR

```
$ dnf copr enable pkgstore/vsftpd
$ dnf install -y vsftpd
```

### Open Build Service (OBS)

```
# Work in Progress
```

## Update

```
$ dnf upgrade -y vsftpd
```

## Remove

```
$ dnf erase -y vsftpd
$ dnf copr remove pkgstore/vsftpd
```

## How to Build

1. Get source from [src.fedoraproject.org](https://src.fedoraproject.org/rpms/vsftpd).
2. Write last commit SHA from [src.fedoraproject.org](https://src.fedoraproject.org/rpms/vsftpd) to [CHANGELOG](CHANGELOG).
3. Modify & update source (and `*.spec`).
4. Build SRPM & RPM.
