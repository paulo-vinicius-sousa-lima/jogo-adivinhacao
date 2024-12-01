# Jogo de Adivinhação em C 🎲

Este é um jogo de adivinhação simples desenvolvido em linguagem C. O objetivo do jogador é adivinhar um número aleatório entre 1 e 16 em até 4 tentativas. Após cada palpite, o programa fornece dicas indicando se o número correto é maior ou menor que o palpite.

## Funcionalidades

- **Números Aleatórios**: O programa gera um número entre 1 e 16 a cada rodada.
- **Dicas Interativas**: Informa se o número correto é maior ou menor.
- **Validação de Entrada**: Garante que o jogador insira apenas números dentro do intervalo permitido.
- **Rodadas Ilimitadas**: O jogador pode jogar quantas vezes quiser.
- **Interface Simples**: Interação fácil via linha de comando.

## Como Executar

1. Clone este repositório ou copie o código para o seu editor C.
2. Compile o programa usando o GCC ou outro compilador compatível:

   gcc jogo_adivinhacao.c -o jogo_adivinhacao

3. Execute o programa:

   ./jogo_adivinhacao

4. Siga as instruções exibidas no terminal para jogar.

## Requisitos

- Um compilador C (GCC ou equivalente).
- Sistema operacional que suporte execução de programas compilados em C.

## Regras do Jogo

1. Um número aleatório entre 1 e 16 será gerado.
2. O jogador tem até 4 tentativas para adivinhar.
3. Após cada tentativa:
   - Se acertar, o programa encerra a rodada.
   - Se errar, uma dica será exibida (maior ou menor).
4. Após as tentativas, o número correto é revelado caso o jogador não acerte.
5. No final de cada rodada, o jogador pode optar por jogar novamente ou encerrar.

## Exemplo de Execução

Adivinhe o número entre 1 e 16.
Tentativa 1:
Qual número você acha que é? 8
Você errou. O número é maior.
Tentativa 2:
Qual número você acha que é? 12
Você acertou. O número era 12.
Quer jogar de novo? (Digite 'n' para sair): n
Jogo finalizado.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

## Licença

Este projeto é de código aberto e está disponível sob a [Licença MIT](LICENSE).
