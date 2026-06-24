---

# 🎮 Projeto 2 - Experiências 3D Interativas com Unity

Este projeto consiste em duas experiências interativas desenvolvidas em **Unity 6.3 LTS** com **Cinemachine 3.1.6**, publicadas em **WebGL** e integradas num portfólio interativo.

---

## 🌐 Acesse o Portfólio

A landing page centraliza os dois projetos e permite jogá-los diretamente num **iframe**, mantendo o utilizador dentro do portfólio.

🔗 **[Abrir Portfólio](https://pedrobabau.github.io/Projeto_2_Experiencias_3D_Interativas_Unity/)**

---

## 🎮 Projetos

| Projeto | Link no itch.io | Descrição |
|---------|----------------|-----------|
| **🎯 Projeto A - Visualizador Orbital** | [Jogar no itch.io](https://pedrobpinheiro.itch.io/projeto-a-visualizador-orbital-3d) | Câmera orbital controlada por slider UI. Aproxima e afasta a câmara em torno do objeto 3D. |
| **🎬 Projeto B - Realizador de Cinema** | [Jogar no itch.io](https://pedrobpinheiro.itch.io/projeto-b-realizador-de-cinema) | Sistema de 4 câmeras cinematográficas (Close-Up, Americano, Geral e Sobre Ombro) com toggles. |

---

## 🛠️ Tecnologias Utilizadas

- **Unity 6.3 LTS** — Motor de jogo
- **Cinemachine 3.1.6** — Sistema de câmaras virtuais
- **WebGL** — Build para navegador
- **itch.io** — Publicação e hospedagem dos jogos
- **GitHub Pages** — Hospedagem da landing page

---

## 📋 Requisitos Técnicos Implementados

| Requisito | Projeto A (Orbital) | Projeto B (Camera) |
|-----------|:---:|:---:|
| Cinemachine 3.1.6 | ✅ | ✅ |
| WebGL Build | ✅ | ✅ |
| Publicação itch.io | ✅ | ✅ |
| UI Slider (Orbital) | ✅ | — |
| UI Toggles (4 Câmaras) | — | ✅ |
| Personagem Animado (Mixamo) | — | ✅ |
| Landing Page com GitHub Pages | ✅ | ✅ |
| 4 Planos de Câmara | — | ✅ |

---

## 🖥️ Estrutura do Portfólio

A landing page (`index.html`) apresenta:

- Cards para cada projeto com descrição e tags técnicas
- Botão **"Jogar Agora"** que abre o jogo num modal com iframe
- Modal com:
  - Cabeçalho com título e botão **"Fechar"**
  - Indicador de carregamento (spinner)
  - Iframe com o jogo embutido
- Fechar com tecla `ESC` ou clique fora do modal
- Secção com requisitos técnicos
- Rodapé com ligação ao repositório GitHub

---

## 🔗 Links de Embed dos Jogos

Os jogos são carregados via iframe utilizando os seguintes URLs:

| Projeto | URL do Embed |
|---------|--------------|
| Orbital Viewer | `https://itch.io/embed-upload/18061663?color=333333` |
| Camera Director | `https://itch.io/embed-upload/18061855?color=333333` |

---

## 📁 Estrutura de Ficheiros

```
/
├── index.html          # Landing page principal
├── README.md           # Este ficheiro
```

---

## 🚀 Como Executar Localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/PedroBabau/Projeto_2_Experiencias_3D_Interativas_Unity.git
   ```
2. Abra o ficheiro `index.html` no navegador
3. Clique em **"Jogar Agora"** para abrir os jogos no modal

---

## 📦 Publicação

- **Jogos**: Publicados no itch.io com WebGL
- **Landing Page**: Publicada via GitHub Pages

---

## 👤 Autor

**PedroBPinheiro**  
GitHub: [PedroBabau](https://github.com/PedroBabau)  
itch.io: [PedroBPinheiro](https://pedrobpinheiro.itch.io/)

---

## 📄 Licença

Projeto desenvolvido para a disciplina de **Edições Multimédia Interativas**.

---

### ✅ Nota sobre o Iframe

Os jogos são carregados num iframe dentro da landing page, mantendo o utilizador no portfólio, conforme recomendado para uma melhor experiência de navegação.

---