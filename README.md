# ♟️ Chess System (POO)

Sistema de jogo de xadrez desenvolvido utilizando **Programação Orientada a Objetos (POO)**.  
O projeto simula uma partida completa de xadrez no terminal, aplicando regras oficiais do jogo e conceitos fundamentais de design orientado a objetos.

---

## 🚀 Funcionalidades

- ✅ Criação e exibição de tabuleiro de xadrez
- ✅ Movimentação de peças conforme as regras oficiais
- ✅ Validação de jogadas
- ✅ Controle de turnos (jogador branco e preto)
- ✅ Detecção de:
  - Xeque
  - Xeque-mate
- ✅ Jogadas especiais:
  - Roque
  - En passant
  - Promoção de peão
- ✅ Interface em modo texto (console)

---

## 🧠 Conceitos de POO aplicados

Este projeto foi desenvolvido com foco nos principais pilares da Programação Orientada a Objetos:

- **Encapsulamento** → proteção dos estados internos das classes  
- **Herança** → reutilização de código entre peças (ex: Torre, Bispo, Cavalo)  
- **Polimorfismo** → comportamentos diferentes para cada tipo de peça  
- **Abstração** → modelagem do domínio do jogo de xadrez  

---

## 🏗️ Estrutura do Projeto

```bash
src/
│
├── application/     # Classe principal (main)
├── boardgame/       # Estrutura genérica de tabuleiro
│   ├── Board
│   ├── Piece
│   └── Position
│
└── chess/           # Regras específicas do xadrez
    ├── ChessMatch
    ├── ChessPiece
    ├── ChessPosition
    └── pieces/
        ├── King
        ├── Queen
        ├── Rook
        ├── Bishop
        ├── Knight
        └── Pawn
