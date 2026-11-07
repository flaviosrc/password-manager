# pass-manager

Store your passwords in encrypted text files

## usage

```sh
pass-manager --help
```

## bash install

```sh
echo "export PATH=\"\$PATH:$(pwd)/bin\"" >> ~/.bashrc
source ~/.bashrc
```

## responsibilities

pass-manager:
- encrypt and decrypt your secrets

user:
- manage gpg keys
- versioning
- distribution
- backup

## generating new gpg key pair

```sh
gpg --full-generate-key
```

*"one key to rule them all"*
