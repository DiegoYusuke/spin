# ♠️ Spin Pilot HUD - High Performance

Ferramenta web de decisão rápida para jogadores profissionais de Spin & Go / Jackpot Poker. Desenvolvido para substituir tabelas estáticas (PDFs) por uma interface interativa, rápida e responsiva.

🔗 **Acesse Online:** [https://diegoyusuke.github.io/spin/](https://diegoyusuke.github.io/spin/)

## 🚀 Funcionalidades

* **Split Screen UI:** Separação clara entre estratégias Heads-Up (Azul) e 3-Handed (Verde).
* **Navegação Instantânea:** Sistema de "One-Click" para acessar ranges específicos.
* **Smart Legends:** Legendas dinâmicas que alteram o significado das cores baseadas no contexto (ex: Nash vs Open Raise).
* **Filtro de Stacks:** Visualização focada por profundidade de stack (25bb a 8bb).
* **Nash Equilibrium:** Integração completa de tabelas Push/Fold/Call para Late Game.
* **Hotkeys:** Tecla `ESC` para retorno rápido ao menu principal.

## 🛠️ Ferramentas Inclusas

### Range Painter (Team Edition)
O projeto inclui um editor gráfico (`painter.html`) para criação e manutenção dos ranges.
* Permite "pintar" a grade de mãos.
* Exporta imagens em **Alta Resolução (4K)** prontas para o HUD.
* Sincronizado com as mesmas classes CSS do projeto principal.

## 📂 Estrutura do Projeto

* `index.html`: A aplicação principal (HUD).
* `painter.html`: O editor de ranges.
* `/assets/ranges/`: Onde ficam as imagens das estratégias, organizadas por pastas (`hu`, `3h`, `nash`).

## 💻 Como Rodar Localmente (Opcional)

Se você não quiser usar a versão online:

1.  Baixe este repositório (Code > Download ZIP).
2.  Extraia a pasta em seu computador.
3.  Clique duas vezes em `index.html` para abrir no navegador.

---
*Desenvolvido para alta performance em mesas de Spin & Go.*