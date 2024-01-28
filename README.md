# README

![Licença Proprietária](https://img.shields.io/badge/Licença-Proprietária-red)

- [Submodules](#submodules)
- [Proto3 Language Guide](#proto3-language-guide)
- [Licença](#licença)
- [Segurança](#segurança)
- [Pull Requests](#pull-requests)
- [Corrigindo Bugs](#corrigindo-bugs)
- [Licença](#licença)

## Submodules

Esse projeto é um submodule do front-end e do back-end.

- Para adicionar no projeto utilize o seguinte comando (somente adicione se não estiver no arquivo `.gitmodules`).

```sh
git submodule add https://github.com/NatanAmorim/gs_protobufs
```

- Se for a primeira vez que você faz check-out de um repositório, você precisa usar `init` primeiro:

```sh
git submodule init
```

- Para atualizar no seu projeto local utilize os seguintes comandos.

```sh
git submodule update --init
```

```sh
git submodule update --recursive --remote
```

## Proto3 Language Guide

- [Language Guide (proto 3)](https://protobuf.dev/programming-guides/proto3) covers how to use the version 3 of Protocol Buffers in your project.
- gRPC uses a set of well defined [status response codes](https://grpc.github.io/grpc/core/md_doc_statuscodes.html) as part of the RPC API.
- [gRPC Guides](https://grpc.io/docs/guides/)

## Licença

Todo o código do software é propriedade da empresa.
Toda a documentação e código fonte do software é confidencial.

- Os direitos do software da são exclusivos a empresa.
- A distribuição do código fonte, executável e documentação do software é proibida em qualquer forma ou meio não autorizado.
- É proibido a terceiros executar, copiar, distribuir, estudar, mudar e melhorar o software.

## Segurança

Se você acredita que encontrou uma vulnerabilidade de segurança no software, encorajamos você a nos informar imediatamente. Investigaremos todos os relatórios legítimos e faremos o possível para corrigir o problema rapidamente.

## Pull Requests

- Descreva de forma clara o que deve ser consertado ou adicionado.
- Tente minimizar a quantidade de alterações no código, use estilos/funções já existentes.

## Corrigindo Bugs

Para facilitar a resposta a problemas por favor siga essas orientações quando for explicar o problema.

- Descreva o que deve ser consertado, se for relevante anexe logs/screenshots.
- Descreva como reproduzir o bug, para que possa ser consertado.
