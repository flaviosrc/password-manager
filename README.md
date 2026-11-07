# password-manager

generates and stores passwords in encrypted text files

## usage

```sh
password --help
```

## bash install

```sh
echo "alias pm=\"$(pwd)/bin/password\"" >> ~/.bashrc
source ~/.bashrc
```

## responsibilities

password-manager:
- gen, encrypt and decrypt your passwords

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
