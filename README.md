
<img src="https://komarev.com/ghpvc/?username=robsonmt2018&label=PROFILE+VIEWS&color=00D9FF&style=for-the-badge" alt="Profile Views"/><img src="https://img.shields.io/github/followers/robsonmt2018?label=FOLLOWERS&style=for-the-badge&color=0066FF&labelColor=080B18" alt="GitHub Followers"/>
---


# 🚀 ORBITAL DEFENDER - ULTIMATE EDITION v2.3

<img width="1024" height="683" alt="image" src="https://github.com/user-attachments/assets/ea7ce33a-a793-4b03-b961-394f6a5d8cd3" />

> Um jogo de nave 3D estilo *arcade shoot 'em up* desenvolvido para rodar diretamente no navegador com gráficos WebGL dinâmicos e áudio procedural.

---

## 📌 Sobre o Jogo

**Orbital Defender** coloca o jogador no controle de uma nave interceptora orbital com a missão de defender o planeta contra hordas de meteoros, naves inimigas e chefões colossais ao longo de 5 fases progressivas.

O projeto foi totalmente construído sem a necessidade de arquivos de mídia externos (imagens ou arquivos de áudio MP3/WAV) — toda a renderização 3D é gerada em tempo real via **Three.js** e os efeitos sonoros/músicas são sintetizados via **Web Audio API**.

---

## ✨ Destaques e Funcionalidades

* 🌌 **Gráficos 3D em Tempo Real:** Iluminação dinâmica, partículas de rastro de motor, campo estelar e atmosfera planetária que evolui a cada fase.
* 🔊 **Sintetizador de Áudio Procedural:** Efeitos de tiros, explosões, sirenes e música de boss gerados via código através da `Web Audio API`.
* 🛡️ **Sistemas de Defesa e Habilidades:**
  * **Escudo Energético (🛡️):** Invulnerabilidade temporária com tempo de recarga.
  * **Bomba Inteligente (💣):** Limpa os inimigos na tela e causa dano massivo a chefões.
  * **Upgrade de Armas:** Evolução de tiros (Normal, Duplo, Triplo e Laser).
* 🎯 **Múltiplas Formas de Controle:** Suporte completo para **Teclado (PC)** e **Joystick Virtual Touch (Mobile)**.
* 📊 **HUD & Radar Vertical:** Acompanhe o progresso do percurso, multiplicador de combo (x1 a x5) e recorde salvo no navegador (`localStorage`).

---

## 🗺️ Fases e Bosses

| Fase | Ambiente | Ameça Principal | Chefe de Fase |
| :---: | :--- | :--- | :--- |
| **1** | Órbita Baixa | Chuva de Meteoros | **ASTEROID CRUSHER** |
| **2** | Cinturão de Asteroides | Naves Inimigas | **VOID INTERCEPTOR** |
| **3** | Espaço Profundo | Caos Total (Meteoros + Naves) | **PLASMA DREADNOUGHT** |
| **4** | Limiar da Galáxia | Esquadrão de Elite | **BEAM BLASTER** |
| **5** | Núcleo de Crise | Hordas Finais e Raios Laser | **APOCALYPSE TITAN** |

---

## 🕹️ Controles

### 💻 Computador (Teclado)

| Ação | Tecla |
| :--- | :--- |
| **Movimentação** | `W`, `A`, `S`, `D` ou `Setas Direcionais` |
| **Atirar** | `Espaço` (Segurar para disparo contínuo) |
| **Pausar** | `Esc` |

### 📱 Dispositivos Móveis (Touch)

* **Analógico Esquerdo:** Movimentação fluida da nave.
* **Botão 🎯:** Disparo contínuo.
* **Botão 💣:** Ativar Bomba Inteligente.
* **Botão 🛡️:** Ativar Escudo Temporal.

---

## 🛠️ Tecnologias Utilizadas

* **Linguagem:** JavaScript (ES6 Modules)
* **Estrutura & Estilização:** HTML5 e CSS3 Responsive Layout
* **3D Engine:** [Three.js](https://threejs.org/) (v0.160.0)
* **Áudio:** Web Audio API (Osciladores e Filtros Procedurais)
* **Armazenamento Local:** `localStorage` para pontuação alta (High Score)

---

## 🚀 Como Executar o Projeto

Como o jogo utiliza importações ES6 de módulos WebGL, é recomendável executá-lo através de um servidor local simples para evitar bloqueios de CORS do navegador.

1. **Clone este repositório:**
   ```bash
   git clone [https://github.com/seu-usuario/orbital-defender.git](https://github.com/seu-usuario/orbital-defender.git)
