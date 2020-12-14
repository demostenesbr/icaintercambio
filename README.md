# I.C.A - Intercâmbio com apoio.

Um projeto com o apoio exclusivo para o Social Hack 2.0 - ação do SEBRAE nacional. Implementação de um canal digital que facilite todo o processo de estudos no exterior de pessoas PCD, desde a escolha da escola de estudos ou intercâmbio, encontrar bolsas de estudo, o processo de aceitação nas escolas/universidades, documentação necessária (carta de motivação, teste de proficiência linguística, CV, visto etc), as que possuem instalações/estruturas acessíveis, encontrar cursos e colégios e universidades de interesse do estudante; os períodos de avaliações e entregas dos trabalhos de cada curso; carga efetiva de duração de cada curso e o processo de certificação. 


# Linguagens disponíveis

O projeto responsivo atua com os gerenciadores de pacote Yarn com suporte para as linguagens:
- Java;
- JavaScript;
- TypeScript;
- Node JS;
- React JS;
- React Native;
- React Native com Expo para iOS e Android;
- Objective C;
- Ruby & Rails.

## O projeto

O projeto em si trata-se de um *monorepo* que unifique as bases para servidor, web e mobile. Inspirada na solução da Rocketseat, incluidas as navegações web e mobile para o projeto, e elementos básicos em acessibilidade digital.

## Para acessar o projeto

Para acessar e rodar as funcionalidades do projeto execute:
- O projeto *web*, executando em packages/web: 
`yarn start`

- O projeto *mobile*, executando em packages/app:
`expo start`

## Executando no Yarn

Ao executar o Yarn, você estará baixando um único **node_modules** para o projeto ser executando tanto para as plataformas *mobile* e *web* do projeto.

## Mapa mental do projeto
```mermaid
graph LR
A[Cenário] -- Link text --> B[Problema]
B[Problema] -- Link test --> C[Solução]
C[Solução] -- Link test --> D[Produto]
D[Produto] -- Link test --> A[Cenário]```