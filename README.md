# Sample Utils

Antes de compilar o projeto, certifique-se que tenha instalado:
- [.NET Core SDK 8.0](https://dotnet.microsoft.com/pt-br/download/dotnet/8.0)


## Sobre

Esta é uma lib para auxiliar o desenvolvimento de projetos

## Utilização:

Vincule ao seu projeto como um submodule.
Para isso navegue a raiz do seu projeto via terminal

```
$ cd <path/to/main-project>
```

Crie suas sub pastas para não sujar o path raiz do project.
Adicione o submódulo:

```
$ git submodule add git@github.com:your-user/my-submodule.git path/to/submodule
```

Faça um Commit
Para clonar uma nova branch ou repository com submodule:

```
$ git clone git@github.com:your-user/main-project.git
$ cd main-project
$ git submodule update --init --recursive
```

Lembre-se submodulo é projeto e sofre atualizações para isso é possível atualiza-lo separadamente.
