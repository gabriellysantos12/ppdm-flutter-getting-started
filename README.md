# PPDM - Programação para Dispositivos Móveis

## Parte 1: Respostas Conceituais

### 1. Diferença de Arquiteturas

O desenvolvimento nativo utiliza linguagens e ferramentas específicas para cada sistema, como Kotlin ou Java para Android e Swift para iOS. Já o desenvolvimento Cross-Platform, como o Flutter, permite criar aplicativos para diferentes plataformas utilizando uma única base de código, facilitando a manutenção e reduzindo o tempo de desenvolvimento.

### 2. Ciclo de Vida e Widgets

No Flutter, os widgets são os elementos que formam a interface do aplicativo.

- **StatelessWidget:** é utilizado quando o componente não precisa gerenciar um estado que muda durante sua utilização. Exemplo: um título ou um texto fixo.
- **StatefulWidget:** é utilizado quando o componente precisa atualizar sua aparência conforme as mudanças de estado. Exemplo: um contador que aumenta quando o usuário pressiona um botão.

### 3. Gerenciamento de Estado

Quando chamamos o método `setState()` dentro de um `StatefulWidget`, o Flutter identifica que o estado foi alterado e agenda uma nova construção da interface. Assim, a tela é atualizada para mostrar os novos valores ou refletir as mudanças realizadas.

## Parte 2: Prática Hands-on

Projeto desenvolvido com Flutter, seguindo o tutorial oficial **Flutter Getting Started**, da documentação do Flutter.

**Conteúdos praticados:**
- Construção da árvore de widgets com `Scaffold`, `Row`, `Column` e `Container`.
- Criação de interfaces e componentes.
- Adição de interatividade.
- Gerenciamento de estado.
- Organização do código.

**Tecnologias utilizadas:** Flutter e Dart.

**Repositório GitHub:** [INSIRA AQUI O LINK DO SEU REPOSITÓRIO]
