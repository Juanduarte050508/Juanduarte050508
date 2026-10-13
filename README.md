<!--
  README DE PERFIL — Juan Duarte Moura
  Conceito: o perfil é o visor de uma câmera; cada seção é um "frame".
  Arquivos locais (pasta assets/): banner.svg, typing.svg, divider.svg,
  shutter.svg e visuall-logo.png — todas as animações são SVG do próprio repo.
-->

<p align="center">
  <img width="100%" src="./assets/banner.svg" alt="Juan Duarte Moura — Eng. de Software, Python, Visão Computacional e Hardware"/>
</p>

<p align="center">
  <img src="./assets/typing.svg" width="650" alt="detectando: Python, Visão Computacional, Machine Learning, Full-Stack JavaScript, Arduino + ESP32"/>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/juan-duarte-moura"><img src="https://img.shields.io/badge/LinkedIn-161618?style=flat-square&logo=linkedin&logoColor=FF3B47" alt="LinkedIn"/></a>
  <a href="mailto:juanduarte0505008@gmail.com"><img src="https://img.shields.io/badge/Email-161618?style=flat-square&logo=gmail&logoColor=FF3B47" alt="Email"/></a>
  <img src="https://img.shields.io/badge/FIAP-161618?style=flat-square" alt="FIAP"/>
  <img src="https://img.shields.io/badge/São_Paulo-161618?style=flat-square&logo=googlemaps&logoColor=FF3B47" alt="São Paulo"/>
</p>

<p align="center"><img src="./assets/divider.svg" width="100%" alt=""/></p>

### `[ FRAME 01 ]` &nbsp;sobre mim

| | |
|---|---|
| 🎓 **Graduação** | Engenharia de Software na **FIAP** |
| 🔧 **Formação técnica** | Técnico em **Mecatrônica** pela **ETEC** |
| 📍 **Localização** | São Paulo, Brasil |
| 🎯 **Foco** | Full-Stack · IA / Visão Computacional · Automação |
| 💼 **Em busca de** | Estágio em Engenharia de Software |

Sou um desenvolvedor com base sólida em engenharia, migrando do mundo de
**robótica e sistemas embarcados** para o **desenvolvimento de software moderno**.
A formação em mecatrônica me deixa confortável na ponte entre o código e o mundo
físico — de pipelines de visão computacional a aplicações web full-stack.

<p align="center"><img src="./assets/divider.svg" width="100%" alt=""/></p>

### `[ FRAME 02 ]` &nbsp;projetos

<details open>
<summary><b>🤟 VisuAll</b> — reconhecimento de Libras em tempo real &nbsp;<code>confiança: 0.99</code></summary>
<br/>

<img src="./assets/visuall-logo.png" alt="Logo do VisuAll" width="140" align="left" hspace="16"/>

Sistema que reconhece Libras pela câmera e traduz em tempo real, aproximando
pessoas surdas e ouvintes. Funciona no celular e também em **óculos inteligentes
com ESP32**, que fazem a mesma leitura e deixam a conversa com as mãos livres.
Desenvolvido em equipe no **Challenge FIAP 2026**, em parceria com a **JOVI** —
o VisuAll é um dos **6 finalistas do NEXT** (24/10/2026).

<br clear="left"/>

**Como funciona**

- 🔤 **Modo Alfabeto** — reconhece a soletração completa, de A a Z, incluindo as letras com movimento
- 🧍 **Modo Corpo** — reconhece sinais pelos pontos do corpo, rosto e mãos, com as palavras-chave *computador*, *ajuda*, *pessoa*, *surda* e *conversar*
- 🗣️ **Resposta por voz** — quem ouve fala ou digita e o texto aparece para a pessoa surda ler, com opção de girar a tela para aumentar a letra
- 🕘 **Histórico** — guarda o que já foi dito na conversa
- 👓 **Óculos** — alterna entre a câmera do celular e a dos óculos; com a tela bloqueada, o celular fica no bolso enquanto os óculos fazem a leitura e o áudio da tradução sai pelo fone ou pela haste

**Por baixo do capô**

- 🧠 **Alfabeto** com modelos MLP estáticos e dinâmicos
- 🦴 **Sinais corporais** com MediaPipe Holistic + LSTM
- 🔗 Backend e frontend unificados, calibração facial adaptativa e frases montadas por lista de tokens

`Python` `TensorFlow/Keras` `MediaPipe` `scikit-learn` `WebSocket` `Kotlin` `ESP32`

[**abrir repositório ↗**](https://github.com/Juanduarte050508/VisuAll)

</details>

<details open>
<summary><b>🦾 Robotic Hand</b> — mão robótica controlada por visão computacional &nbsp;<code>confiança: 0.97</code></summary>
<br/>

Projeto final (TCC) do curso técnico em Mecatrônica. Uma webcam captura os pontos de
referência da mão em tempo real via OpenCV/MediaPipe, e um Arduino reproduz os
movimentos em 5 servomotores. Foi o precursor direto do VisuAll.

`Python` `OpenCV` `MediaPipe` `Arduino C++` `Fusion 360`

[**abrir repositório ↗**](https://github.com/Juanduarte050508/Engineering-Portfolio)

</details>

<p align="center"><img src="./assets/divider.svg" width="100%" alt=""/></p>

### `[ FRAME 03 ]` &nbsp;tecnologias

**Linguagens**<br/>
<img src="https://img.shields.io/badge/Python-161618?style=for-the-badge&logo=python&logoColor=FF3B47" alt="Python"/>
<img src="https://img.shields.io/badge/JavaScript-161618?style=for-the-badge&logo=javascript&logoColor=FF3B47" alt="JavaScript"/>
<img src="https://img.shields.io/badge/TypeScript-161618?style=for-the-badge&logo=typescript&logoColor=FF3B47" alt="TypeScript"/>
<img src="https://img.shields.io/badge/C++-161618?style=for-the-badge&logo=cplusplus&logoColor=FF3B47" alt="C++"/>
<img src="https://img.shields.io/badge/HTML5-161618?style=for-the-badge&logo=html5&logoColor=FF3B47" alt="HTML5"/>
<img src="https://img.shields.io/badge/CSS3-161618?style=for-the-badge&logo=css3&logoColor=FF3B47" alt="CSS3"/>

**IA e Visão Computacional**<br/>
<img src="https://img.shields.io/badge/OpenCV-161618?style=for-the-badge&logo=opencv&logoColor=FF3B47" alt="OpenCV"/>
<img src="https://img.shields.io/badge/MediaPipe-161618?style=for-the-badge&logo=google&logoColor=FF3B47" alt="MediaPipe"/>
<img src="https://img.shields.io/badge/TensorFlow-161618?style=for-the-badge&logo=tensorflow&logoColor=FF3B47" alt="TensorFlow"/>
<img src="https://img.shields.io/badge/Keras-161618?style=for-the-badge&logo=keras&logoColor=FF3B47" alt="Keras"/>
<img src="https://img.shields.io/badge/scikit--learn-161618?style=for-the-badge&logo=scikitlearn&logoColor=FF3B47" alt="scikit-learn"/>
<img src="https://img.shields.io/badge/Pandas-161618?style=for-the-badge&logo=pandas&logoColor=FF3B47" alt="Pandas"/>

**Web**<br/>
<img src="https://img.shields.io/badge/React-161618?style=for-the-badge&logo=react&logoColor=FF3B47" alt="React"/>
<img src="https://img.shields.io/badge/Node.js-161618?style=for-the-badge&logo=nodedotjs&logoColor=FF3B47" alt="Node.js"/>

**Hardware e Modelagem 3D**<br/>
<img src="https://img.shields.io/badge/Arduino-161618?style=for-the-badge&logo=arduino&logoColor=FF3B47" alt="Arduino"/>
<img src="https://img.shields.io/badge/ESP32-161618?style=for-the-badge&logo=espressif&logoColor=FF3B47" alt="ESP32"/>
<img src="https://img.shields.io/badge/Fusion_360-161618?style=for-the-badge&logo=autodesk&logoColor=FF3B47" alt="Fusion 360"/>

**Ferramentas**<br/>
<img src="https://img.shields.io/badge/Git-161618?style=for-the-badge&logo=git&logoColor=FF3B47" alt="Git"/>
<img src="https://img.shields.io/badge/GitHub-161618?style=for-the-badge&logo=github&logoColor=FF3B47" alt="GitHub"/>
<img src="https://img.shields.io/badge/VS_Code-161618?style=for-the-badge&logo=visualstudiocode&logoColor=FF3B47" alt="VS Code"/>

<p align="center"><img src="./assets/divider.svg" width="100%" alt=""/></p>

### `[ FRAME 04 ]` &nbsp;atividade

<p align="center">
  <img src="./profile-3d-contrib/profile-visor.svg" width="100%" alt="Gráfico 3D de contribuições no GitHub"/>
</p>

<p align="center"><img src="./assets/divider.svg" width="100%" alt=""/></p>

### `[ FRAME 05 ]` &nbsp;próximos passos

- 🔭 Finalizar o **VisuAll** para o Challenge 2026 da FIAP e apresentá-lo no **NEXT**
- 🌱 Aprofundar **Full-Stack JavaScript** (React + Node + Express)
- 💼 Conquistar meu primeiro **estágio** em Engenharia de Software
- 🤝 Colaborar em projetos de **IA / Visão Computacional**

<br/>

<p align="center"><i>"From the physical to the digital — building things that work."</i></p>

<p align="center"><img src="./assets/divider.svg" width="100%" alt=""/></p>

<p align="center">
  <img src="./assets/shutter.svg" width="100%" alt="■ STOP · obrigado por assistir até aqui"/>
</p>
