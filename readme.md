# Calculadora de Partidas Ranqueadas

Este projeto consiste em uma calculadora de partidas ranqueadas implementada em HTML, CSS e JavaScript. A calculadora permite que o usuário insira a quantidade de vitórias e derrotas, calcula o saldo de vitórias e determina o nível do jogador com base nas condições predefinidas.

## Estrutura do Projeto

- **index.html:** Contém a estrutura HTML para a interface da calculadora.
- **style.css:** Arquivo CSS para estilizar a interface.
- **script.js:** Código JavaScript responsável pela lógica da calculadora.

## Funcionalidades Implementadas

### Função `calcular`

A função `calcular` é responsável por processar a entrada do usuário, calcular o saldo de vitórias e exibir o resultado na interface.

- **Obtenção de Entradas:**
  - Utiliza `document.getElementById` para obter os valores inseridos nos campos de vitórias e derrotas.

- **Chamada da Função `calcularRanked`:**
  - Chama a função `calcularRanked` passando as quantidades de vitórias e derrotas como parâmetros.

- **Atualização da Interface:**
  - Atualiza o conteúdo do elemento HTML com o resultado do cálculo.

### Função `calcularRanked`

A função `calcularRanked` realiza o cálculo do saldo de vitórias e determina o nível do jogador com base nas condições fornecidas.

- **Cálculo do Saldo de Vitórias:**
  - Calcula o saldo de vitórias subtraindo as derrotas das vitórias.

- **Determinação do Nível:**
  - Utiliza estruturas condicio

## Live

<https://calculadora-de-partidas-rankeadas.vercel.app/>
