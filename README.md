# pass-manager

gpg password manager

*"one password to rule them all"*

## usage

```sh
pass-manager --help
```

## bash install

```sh
cd bin
echo "export PATH=\"\$PATH:$(pwd)\"" >> ~/.bashrc
```

## responsibilities

pass-manager:
- encrypt and decrypt password files

user:
- manage gpg keys
- versioning
- distribution
- backup

## generating new gpg key pair

```sh
gpg --full-generate-key
```
