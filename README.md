# 🎮 Jogo da Velha — Tic Tac Toe Inteligente

Projeto web interativo desenvolvido com **HTML, JavaScript puro e Tailwind CSS**, apresentando uma versão moderna do clássico **Jogo da Velha**, incluindo modos multiplayer e inteligência artificial com níveis de dificuldade.

---

📸 Preview do Projeto
🧭 Menu 1 — Jogador vs Jogador (P1 vs P2)

Modo clássico onde dois jogadores disputam localmente no mesmo dispositivo.

Alternância automática de turnos

Identificação visual do jogador atual

Detecção automática de vitória ou empate

Atualização do placar em tempo real

Ideal para partidas rápidas entre dois usuários.

![Preview do Projeto](./preview-menu.png)


🤖 Menu 2 — Jogador vs Máquina (P1 vs PC)

Modo single player onde o jogador enfrenta a Inteligência Artificial.

Escolha de níveis de dificuldade

IA com tomada de decisão estratégica

Sistema de bloqueio e tentativa de vitória automática

Experiência progressiva conforme o nível selecionado

Simula diferentes níveis de habilidade da máquina.

![Preview do Projeto](./preview-menu2.png)

🎮 Menu 3 — Área do Jogo

Tela principal onde ocorre a partida.

Tabuleiro interativo 3x3

Feedback visual das jogadas

Destaque da combinação vencedora

Sistema de reinício de rodada

Persistência do placar utilizando LocalStorage

Interface responsiva adaptada para desktop e mobile.


![Preview do Projeto](./tela.png)


✅ Tela Final — Jogo Finalizado com Sucesso

Após a conclusão da partida, o sistema identifica automaticamente o resultado do jogo e apresenta o estado final ao usuário.

Nesta etapa:

O jogador vencedor é destacado visualmente

A combinação vencedora é evidenciada no tabuleiro

O placar é atualizado automaticamente

O resultado da rodada é exibido de forma clara (vitória ou empate)

O usuário pode iniciar uma nova partida rapidamente

Essa tela garante uma experiência completa, fornecendo feedback imediato ao jogador e mantendo a continuidade da gameplay sem necessidade de recarregar a página.

![Preview do Projeto](./final.png)

---

## ✨ Funcionalidades

✅ Interface moderna e responsiva  
✅ Modo **Jogador vs Jogador (PvP)**  
✅ Modo **Jogador vs Máquina (IA)**  
✅ 5 níveis de dificuldade da IA  
✅ Modo aleatório automático  
✅ Sistema de placar em tempo real  
✅ Persistência de pontuação com LocalStorage  
✅ Destaque visual da jogada vencedora  
✅ Reinício de rodada e partida  

---

## 🧠 Inteligência Artificial

A máquina utiliza diferentes estratégias conforme o nível escolhido:

| Nível | Comportamento |
|------|--------------|
| 1 | Movimento totalmente aleatório |
| 2 | Parcialmente estratégico |
| 3 | Estratégia tática (bloqueia e vence) |
| 4 | Alto nível estratégico |
| 5 | Melhor jogada possível (quase imbatível) |

A lógica inclui:

- Verificação de vitória imediata
- Bloqueio do adversário
- Prioridade do centro
- Estratégia de cantos
- Escolha otimizada de movimentos

---

## 🛠️ Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript (Vanilla JS)
- Tailwind CSS
- LocalStorage API

---

## 📂 Estrutura do Projeto

```
Jogo-da-Velha/
│
├── index.html
└── preview.png
```

---

## ▶️ Como Executar o Projeto

1. Clone o repositório:

```bash
git clone https://github.com/SEU-USUARIO/jogo-da-velha.git
```

2. Acesse a pasta:

```bash
cd jogo-da-velha
```

3. Abra o arquivo:

```
index.html
```

no navegador.

✅ Não necessita instalação de dependências.

---

## 🎯 Objetivo do Projeto

Este projeto foi desenvolvido com foco em:

- Prática de lógica de programação
- Manipulação do DOM
- Estruturação de estados em JavaScript
- Criação de IA baseada em regras
- Desenvolvimento de interfaces responsivas

---

## 📈 Melhorias Futuras

- [ ] Modo online multiplayer
- [ ] Animações de jogada
- [ ] Sistema de ranking
- [ ] Sons e efeitos
- [ ] Dark Mode

---

## 👨‍💻 Autor

**Walisson Patrick Helmer**

- 💼 LinkedIn: https://www.linkedin.com/in/walissonpatrickhelmer/
- 💻 GitHub: https://github.com/WalissonPatrickHelmer

---

⭐ Se gostou do projeto, considere deixar uma estrela no repositório!