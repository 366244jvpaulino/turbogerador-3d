# Turbogerador 3D

Modelo 3D interativo de um conjunto **turbina a vapor, redutor e gerador síncrono**, feito com JavaScript e Three.js. O projeto roda direto no navegador, sem instalação.

**Demonstração:** [https://366244jvpaulino.github.io/turbogerador-3d/](https://366244jvpaulino.github.io/turbogerador-3d/)

## O que o projeto faz

- **Seleção de peças:** ao clicar em um componente, o painel mostra o que ele faz, valores típicos de operação e uma curiosidade técnica.
- **Vista explodida:** separa as peças para mostrar como o conjunto é montado.
- **Ver por dentro:** deixa a carcaça transparente e mostra estator, rotor e excitatriz.
- **Ventilação:** animação do circuito fechado de ar (quente sobe, frio desce) passando pelos resfriadores.
- **Sistema de óleo:** linhas de lubrificação indo do tanque aos mancais.
- **Etiquetas de temperatura**, **isolamento térmico** e **cabine acústica** ativados por botões.
- **Controles:** rotação e zoom com mouse ou toque (celular).

## Componentes representados

Turbina a vapor, válvulas, escape, mancais, acoplamentos, redutor de velocidade, giro lento, gerador síncrono (carcaça, estator, rotor, tampas, excitatriz, caixa de ligação), resfriadores de ar, sistema de óleo e base.

## Tecnologias

- JavaScript
- [Three.js](https://threejs.org/) (WebGL)
- HTML e CSS

Tudo em um único arquivo (index.html), sem etapa de build.

## Como usar

**Online:** abra o link da demonstração no navegador.

**Localmente:**

1. Baixe o arquivo index.html.
2. Abra no navegador (Chrome, Edge ou Firefox).
3. Arraste para girar, use a roda do mouse para aproximar e clique nas peças.

## Contexto

Projeto desenvolvido a partir da minha experiência como operador de turbo gerador em usina de cogeração, com o objetivo de unir conhecimento industrial e desenvolvimento web. O mesmo tipo de equipamento é alvo de **monitoramento de condição e manutenção preditiva** (vibração, temperatura, pressão de óleo), tema que pretendo aprofundar com IoT e análise de dados.

## Aviso

Modelo **esquemático e didático**, fora de escala. Os valores exibidos são **ilustrativos** e não representam nenhuma instalação real.

## Próximos passos

- Simular leituras de vibração e temperatura variando no tempo
- Gerar alertas quando um valor passar do limite
- Painel com histórico das leituras

## Autor

**João Victor Paulino de Jesus**
Técnico em Eletromecânica e estudante de Desenvolvimento de Software Multiplataforma (FATEC Araras)
GitHub: [366244jvpaulino](https://github.com/366244jvpaulino)
