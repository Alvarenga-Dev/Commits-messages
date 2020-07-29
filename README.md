<span align="center">
    <h2>Padronização de mensagens no Git com Commitlint!</h2>
    <img src="https://raw.githubusercontent.com/Alvarenga-Dev/Commits-messages/master/images/header-image.png" width="70%">
</span>

## Estrutura de um commit ✏️

A padronização dos commits permitem ter mais significado semântico do histórico do nosso git.

Padrão:

```
    tipo (escopo?): título
```

> A interrogação (?) indica que é opcional. 

Nossos commits também podem possuir um corpo (body), isto é, uma descrição mais completa e um rodapé (footer).

```
    tipo (escopo?): título
    corpo?
    rodapé?
```

Tipos baseados no [commitlint-config-conventional (Angular convention)](https://github.com/conventional-changelog/commitlint/tree/master/%40commitlint/config-conventional#type-enum):

- **build:** Alterações que pode afetar a estrutura ou dependências externas.
- **ci:** Alterações em arquivos ou scripts de configuração de integração contínua (**C**ontinuous **I**ntegration).
- **chore:** Alterações ou inicialização do projeto
- **docs:** Totalmente relacionado a alterações na documentação do projeto.
- **feat:** Um novo recurso é adicionado **(feature)**.
- **fix:** Correção de Bugs.
- **perf:** Alteração que indique melhora no desempenho.
- **refactor:** Uma alteração de código que não corrige um bug e nem adiciona uma feature.
- **revert:** Procura reverter um commit anterior.
- **style:** Alterações apenas na formatação do código sem promover mudanças no seu significado (espaço em branco, formatação, ponto e vírgula, etc).
- **test:** Adicionar ou corrigir testes no projeto.

### Título

Deve ser claro e objetivo! 

> Não coloque um ponto (.) no final

> Escreva sempre que possível no imperativo (add / change / remove)

### Corpo 

Descrição mais detalhada sobre o commit. 

> Não precisa ser uma redação... 😂

### Rodapé

Restringe-se às alterações de estado via smart commit, como resoluções de estado de [issues](https://help.github.com/en/enterprise/2.16/user/github/managing-your-work-on-github/closing-issues-using-keywords), e.g. ‘close #312’.


## Commitlint 🧰

Ferramenta que nos auxilia para evitar commits com estruturas inadequadas e para facilitar a padronização. Assim, o commitlint ele procura verificar as messagens de commit.

### Como utilizar o commitlint?

Acesse o repositório do commitlint clicando [aqui](https://github.com/conventional-changelog/commitlint).

> Você pode utilizar o yarn ou npm.

## Autor 🙋🏻‍♂️

**Lucas Alvarenga**

* Meu Portfólio: https://alvarengadev.firebaseapp.com
* Github: [@Alvarenga-Dev](https://github.com/Alvarenga-Dev)

## Dá uma estrelinha! ⭐️

Copyright © 2020 [Lucas Alvarenga](https://github.com/Alvarenga-Dev). 
