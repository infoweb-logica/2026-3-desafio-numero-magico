# Desafio de 2026.3 - Python - Número mágico

## Informações gerais

- **Público alvo**: alunos da disciplina de **Introdução a lógica e programação** do curso de [Infoweb](https://diatinf.ifrn.edu.br/cursos/tecnico-em-informatica-para-internet/) na [DIATINF](https://diatinf.ifrn.edu.br/) no [CNAT-IFRN](https://portal.ifrn.edu.br/campus/natalcentral/)
- **Professor**: [L A Minora](https://github.com/leonardo-minora/)
- **Objetivo**:
  1. Praticar programação em python com jogo eletrônico

---
## História do jogo

O jogo do número mágico é normalmente uma atividade em uma roda de pessoas onde uma pesso, nomeada como chefe, pensa em um número (ou pega o número de uma tampa) denindo o número mágico da rodada. 
Após ter o número mágico definido, o chefe fala uma faixa de valores com um número menor e outro número maior que o número mágico.
Começa aí o jogo, passando a palavra a cada pessoa da roda falar um número.
Se o jogador acertou o número, o chefe informa que o jogador ganhou.
Caso o jogador errou o número, o chefe ajusta a faixa de menor e maior com o número informado.
Até que alguém advinhe o número ou que a diferença entre o menor e maior número seja de 2.

**Regras** iniciais
- A faixa de valores deve ser informada no início
- O número de particitantes deve ser informado no início
- Cada participante tem um nome e deve ser informado no início
- O número mágico deve ser gerado com `random.randint` no início de cada rodada
- Ganha o jogador quem acertar o número, ou o chefe caso a diferença entre menor e maior seja de 2.

**Regras da rodada**
1. O chefe define o número mágico e passa a palavra para o jogador inicial
2. O chefe define o jogador inicial como o "jogador da vez"
3. O jogador da vez informa número
4. O chefe informa
   1. ou a nova faixa de valores
   2. ou que o jogador foi o vencedor
   3. ou que o chefe foi vencedor
5. Caso o chefe informe a nova faixar de valores
   1. O chefe define o próximo "jogador da vez"
   2. Volta ao passo 3, para o "jogador da vez" jogar

---
