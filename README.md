# Jogo de Batalha em Python

Um simples jogo de batalha em Python onde você enfrenta monstros em combates por turnos.

## Funcionalidades

- **Criação de Personagem:** Você começa com um personagem predefinido chamado Gustavo.
- **Geração de NPCs:** Monstros são gerados automaticamente com base no seu nível.
- **Batalha por Turnos:** As batalhas acontecem por turnos entre o jogador e os NPCs.
- **Sistema de Experiência e Níveis:** O jogador ganha experiência e sobe de nível ao derrotar NPCs.

## Como Jogar

1. Clone o repositório.
2. Certifique-se de ter o Python instalado em seu sistema.
3. Execute o script `jogo.py`.
4. Siga as instruções no console para jogar.

## Como Contribuir

Contribuições são bem-vindas! Se você quiser melhorar este jogo, siga estes passos:

1. Fork o repositório.
2. Crie uma nova branch (`git checkout -b feature/nova-funcionalidade`).
3. Faça suas modificações.
4. Commit suas alterações (`git commit -am 'Adiciona nova funcionalidade'`).
5. Push para a branch (`git push origin feature/nova-funcionalidade`).
6. Crie um novo Pull Request.

## Exemplo de Uso

```python
# Gerar NPCs
gerar_npcs(3)

# Selecionar um NPC
npc_selecionado = lista_npcs[0]

# Iniciar batalha com o NPC selecionado
iniciar_batalha(npc_selecionado)
