# 🐍 Snake Moderno

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge\&logo=html5\&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge\&logo=css3\&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge\&logo=javascript\&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

### Um clássico Snake reinventado com visual moderno, animações suaves e mecânicas extras.

</div>

---

## 🎮 Demonstração

<p align="center">
  <img src="./preview.gif" alt="Snake Moderno Preview" width="700">
</p>

> Adicione um GIF ou screenshot do jogo para deixar o repositório ainda mais atrativo.

---

# ✨ Funcionalidades

✅ Interface moderna com efeito glassmorphism

✅ Sistema de pontuação dinâmica

✅ Velocidade aumenta conforme a pontuação

✅ Frutas especiais com efeitos diferentes

✅ Sistema de obstáculos temporários

✅ Pausa e retomada da partida

✅ Reinício rápido via teclado

✅ Totalmente responsivo

---

# 🍎 Mecânicas do Jogo

| Item       | Efeito                          |
| ---------- | ------------------------------- |
| 🍌 Banana  | +1 ponto                        |
| 🍎 Maçã    | +1 ponto                        |
| 🍊 Laranja | +2 pontos e +2 segmentos        |
| 🍍 Abacaxi | +1 ponto e gera um 💩           |
| 💩 Cocô    | Colisão instantânea (Game Over) |

---

# 🎯 Controles

| Tecla       | Ação                     |
| ----------- | ------------------------ |
| ⬆️ ⬇️ ⬅️ ➡️ | Movimentação             |
| W A S D     | Movimentação alternativa |
| Espaço      | Pausar / Continuar       |
| Enter       | Reiniciar após derrota   |

---

# 🚀 Tecnologias Utilizadas

* HTML5 Canvas
* CSS3 Moderno
* JavaScript Vanilla
* RequestAnimationFrame
* Responsive Design

---

# 📂 Estrutura do Projeto

```text
snake-moderno/
│
├── index.html
├── README.md
├── preview.png
└── preview.gif
```

---

# 🧠 Arquitetura

O código foi organizado em módulos lógicos:

```javascript
Configuração
Estado do Jogo
Utilidades
Frutas
Obstáculos (💩)
Pontuação
Game Over
Física
Renderização
Loop Principal
Controles
```

Essa estrutura facilita manutenção e futuras expansões.

---

# ⚡ Sistema de Dificuldade

A velocidade aumenta automaticamente conforme a pontuação:

```javascript
const multiplier = (1 + score * 0.05);
currentSpeed = BASE_SPEED / multiplier;
```

Quanto mais você pontua, mais rápido o jogo fica.

---

# 🎨 Recursos Visuais

* Fundo com gradiente radial
* Interface Glassmorphism
* Animações suaves nas frutas
* Cobra com gradiente moderno
* Overlay de Game Over
* Indicador visual de pausa

---

# 📱 Responsividade

O jogo adapta automaticamente o tamanho do canvas para:

* Desktop
* Notebook
* Tablet
* Smartphone

---

# 🔮 Possíveis Melhorias Futuras

* Sistema de recordes (Local Storage)
* Ranking online
* Power-ups
* Diferentes mapas
* Sons e efeitos
* Modo infinito
* Modo multiplayer
* Temas visuais

---

# ▶️ Como Executar

### Clone o repositório

```bash
git clone https://github.com/seu-usuario/snake-moderno.git
```

### Entre na pasta

```bash
cd snake-moderno
```

### Abra o arquivo

```bash
index.html
```

Ou utilize a extensão **Live Server** do VS Code.

---

# 📸 Screenshots

Adicione imagens do jogo aqui:

```markdown
![Gameplay](./preview.png)
```

---

# 🤝 Contribuições

Contribuições são bem-vindas.

1. Faça um Fork
2. Crie uma Branch

```bash
git checkout -b feature/minha-feature
```

3. Commit

```bash
git commit -m "feat: minha nova feature"
```

4. Push

```bash
git push origin feature/minha-feature
```

5. Abra um Pull Request

---

# 📜 Licença

Este projeto está sob a licença MIT.

Sinta-se livre para estudar, modificar e utilizar.

---

<div align="center">

### 🐍 Snake Moderno

Desenvolvido com HTML, CSS e JavaScript puro.

⭐ Se gostou do projeto, deixe uma estrela no repositório.

</div>
