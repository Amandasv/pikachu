# \<pikachu\>

Ferramenta de UX colaborativa

## Objetivo

Desenvolver uma ferramenta de apoio a desenvolvedores com o objetivo de permitir avaliação colaborativa de usabilidade por usuários técnicos e leigos.

## Requisitos do sistema

1. Permitir que usuários se cadastrem utilizando uma rede social (Facebook, Google) ou perfil do Github.
2. Permitir que usuários registrados enviem os seus trabalhos para avaliação, por meio de screenshots (ou gif's para animações).
3. Usuários leigos ou técnicos poderão avaliar os trabalhos de outros usuários, podendo comentar cada screenshot e deixar uma marcação visual se necessário com lápis ou texto.
4. Os usuários receberão pontos por cada avaliação, e bônus por cada marcação após a postagem, e também receberão pontos para cada "like" recebido em sua avaliação.
5. Com esses pontos os usuários poderão requerer novas avaliações de usabilidade, dessa forma será incentivada a participação de todos.
6. Incluir um sistema de *achievements* (conquistas), com premiação de badges (medalhas).
7. O usuário deverá comunicar a sua especialidade durante o cadastro, e após conseguir os achievements requeridos irá receber uma marca exclusiva de especialista em determinada área, dependendo dos achievements conquistados.
8. Quando o usuário postar um trabalho para avaliação, deverá informar o especialista requerido ou se prefere a avaliação de usuários leigos, dessa forma o sistema fará sugestões para os especialistas (ou leigos) e recompensará o usuário que avaliar, e que receber like pela avaliação com a marca dessa área.
9. Uma dessas especialidades deverá ser acessibilidade com subcategorias (ou categorias de mesmo nível) para cada tipo de necessidade especial.

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Viewing Your Application

```
$ polymer serve
```

## Building Your Application

```
$ polymer build
```

This will create a `build/` folder with `bundled/` and `unbundled/` sub-folders
containing a bundled (Vulcanized) and unbundled builds, both run through HTML,
CSS, and JS optimizers.

You can serve the built versions by giving `polymer serve` a folder to serve
from:

```
$ polymer serve build/bundled
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
