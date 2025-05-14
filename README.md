# Game Design Document: **LineSwords**

## 1. Visão Geral do Jogo

- **Nome do Jogo**: LineSwords  
- **Gênero**: RPG Top-Down 2D  
- **Tema**: Fantasia medieval com combates rápidos e progressão simples.  
- **Plataforma**: PC (Windows) e Web (via navegador).  
- **Público-alvo**: Jogadores casuais que gostam de RPGs leves com elementos de combate, progressão de personagem e batalhas com espadas mágicas.

## 2. Estória

O mundo de **Linearth** foi fragmentado por uma antiga guerra mágica. Agora, espadas lendárias conhecidas como **LineSwords** caíram dos céus, trazendo poder e destruição. O jogador assume o papel de um herói que desperta no meio desse conflito, com a missão de encontrar as LineSwords originais para restaurar o equilíbrio entre os reinos.

À medida que avança, o herói descobrirá que cada espada carrega a alma de um antigo guerreiro, e que o destino do mundo pode depender de qual força ele decide libertar.

## 3. Estilo Visual e Mundo

- **Estilo gráfico**: Pixel art colorido e limpo, com animações simples.
- **Visão**: Top-down (visão de cima).
- **Cenários**: Florestas encantadas, ruínas antigas, vilarejos e calabouços mágicos.

## 4. Classes Jogáveis

O jogador poderá escolher entre **4 classes fixas**, cada uma com estilo único de combate e habilidades próprias. Todas as classes possuem uma arma inicial fixa que pode ser aprimorada com moedas obtidas no jogo.

| Classe    | Estilo de Combate         | Arma Inicial       | Características |
|-----------|---------------------------|--------------------|-----------------|
| Peão      | Corpo a corpo básico      | Espada curta       | Classe inicial com equilíbrio entre ataque e defesa. |
| Guerreiro | Corpo a corpo pesado      | Espada longa       | Alto dano físico e resistência, mas com velocidade reduzida. |
| Arqueiro  | Ataque à distância rápido | Arco curto         | Rápido e ágil, com menor defesa. Ideal para combates de longe. |
| Mago      | Mágica de médio alcance   | Bastão mágico      | Ataques mágicos variados, ideal para causar dano em área. |

- **Troca de classe**: não é possível durante a campanha. A escolha define o estilo de jogo até o final.
- **Progressão de arma**: cada classe possui apenas **uma arma fixa**, mas com **evoluções desbloqueáveis** via **moedas** (sem loot ou drop de armas).

## 5. Sistema de Armas e Upgrades

- **Sem itens de armas**: O jogador não coleta novas armas, apenas melhora a arma da classe escolhida.
- As armas possuem **níveis de aprimoramento**, que aumentam:
  - Dano base
  - Efeitos secundários (ex: flechas perfurantes, espadas flamejantes)
  - Velocidade de ataque ou alcance

| Nível | Custo em Moedas | Benefício |
|-------|------------------|-----------|
| 1     | Inicial           | -         |
| 2     | 100 moedas        | +20% dano |
| 3     | 250 moedas        | +30% velocidade ou efeito bônus |
| 4     | 500 moedas        | +50% alcance ou dano em área |

- O aprimoramento é feito em **altares mágicos** ou **ferreiros** nos vilarejos.
- Cada classe tem uma árvore de evolução única para sua arma.

## 6. Mecânicas de Jogo

### Movimento
- Movimento em 8 direções com WASD ou controle analógico.
- Rolagem/esquiva com cooldown curto.

### Combate
- Sistema de ataque com base na arma da classe.
- Cada arma possui **ataque primário** e **ataque especial** desbloqueável com progresso.

### Progressão
- O jogador ganha **EXP** ao derrotar inimigos.
- Subir de nível melhora atributos e desbloqueia habilidades passivas da classe.

## 7. Atributos do Personagem

- **FOR (Força)**: Aumenta dano físico.
- **AGI (Agilidade)**: Aumenta velocidade de ataque e esquiva.
- **VIT (Vitalidade)**: Aumenta pontos de vida.
- **MAG (Magia)**: Aumenta dano mágico (efetivo apenas para Magos).

## 8. Inimigos

- **Slimes Elementais**: Inimigos fracos, mas em grande número.
- **Guardas Corrompidos**: Usam espadas como o jogador, têm defesa elevada.
- **Espíritos da Espada**: Criaturas mágicas que guardam as LineSwords.
- **Mini-bosses**: Inimigos com padrões únicos e drops de moedas valiosas.

## 9. Interface e HUD

- **Barra de Vida e Mana** no topo.
- Ícone da classe e nível da arma.
- Contador de moedas visível.
- Minimapa com áreas exploradas.

## 10. Áudio e Trilha Sonora

- **Trilha sonora**: Música leve e mística nas áreas calmas, trilhas mais intensas durante os combates.
- **Efeitos sonoros**: Ataques específicos por classe, sons de aprimoramento de arma, sons ambientais suaves.

## 11. Sistema de Save e Menu

- **Menu Principal**
  - Novo Jogo
  - Carregar Jogo
  - Configurações (áudio, resolução, controles)
  - Créditos
  - Sair

- **Sistema de Save**
  - Salvamento automático em altares mágicos.
  - Salvamento manual disponível fora de combate.

## 12. Finais Possíveis

- **Final da Harmonia**: O herói restaura o equilíbrio entre os reinos.
- **Final do Domínio**: O herói conquista todas as espadas e usa o poder para si.
- **Final da Perda**: O herói falha em controlar o poder e o mundo mergulha no caos.


