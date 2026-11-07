# pass-manager

## uso

```sh
pass-manager
```

## instalação via bash

Execute na raiz do projeto:
```sh
echo "export PATH=\"\$PATH:$(pwd)/bin\"" >> ~/.bashrc
```

## responsabilidades

Responsabilidade da ferramenta
- Criptografar e descriptografar arquivos

Responsabilidade do usuário
- Gerenciamento das chaves gpg
- Versionamento
- Distribuição
- Backup

## gerando um par de chaves gpg

```sh
gpg --full-generate-key
```

Preencha GPG_ID com o endereço de e-mail usado na chave