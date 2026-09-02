<div align="center">

<!-- Banner do projeto / Project banner -->
<img src="https://raw.githubusercontent.com/henriquejne/henriquejne/assets/banner_universo_ternario.png" alt="Universo Ternário — Computação em 3 Estados / Three-State Computing" width="100%">

<h1>🌌 Universo Ternário</h1>

<p><strong>Desenvolvendo a computação Ternária: +1, 0 e -1</strong><br>
<em>Sim, Não e Talvez. Vamos explorar os Três.</em></p>

<p><strong>Developing Ternary Computing: +1, 0 and -1</strong><br>
<em>Yes, No and Maybe. Let's explore the Three.</em></p>

<!-- Badges -->
<a href="https://www.youtube.com/@UniversoTernário" target="_blank">
  <img src="https://img.shields.io/badge/YouTube-Universo%20Ternário-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube">
</a>
<a href="https://tiktok.com/@universoternario7?lang=pt-BR" target="_blank">
  <img src="https://img.shields.io/badge/TikTok-@universoternario7-000000?style=for-the-badge&logo=tiktok&logoColor=white" alt="TikTok">
</a>
<a href="https://x.com/henriqu07337076" target="_blank">
  <img src="https://img.shields.io/badge/X-@henriqu07337076-000000?style=for-the-badge&logo=x&logoColor=white" alt="X">
</a>
<a href="mailto:universoternario@gmail.com">
  <img src="https://img.shields.io/badge/Email-universoternario@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
</a>

<br><br>

<img src="https://img.shields.io/badge/License-Apache%202.0-blue?style=for-the-badge" alt="Apache 2.0">
<img src="https://img.shields.io/badge/Status-Em%20Desenvolvimento%20/%20In%20Development-orange?style=for-the-badge" alt="Em Desenvolvimento / In Development">
<img src="https://img.shields.io/badge/Codificação%20/%20Encoding-BET-green?style=for-the-badge" alt="BET">
<img src="https://img.shields.io/badge/IA%20/%20AI-Suporte%20Ativo-purple?style=for-the-badge" alt="IA / AI">

</div>

---

## 🇧🇷 Português

### 🧠 O que é a Computação Ternária?

A computação ternária opera com **três estados lógicos** em vez de dois:

| Estado | Significado |
|--------|-------------|
| **+1** | Sim / Verdadeiro / Positivo |
| **0**  | Talvez / Indeterminado / Neutro |
| **-1** | Não / Falso / Negativo |

> *Enquanto o mundo computacional tradicional vive no binário (0 e 1), o **Universo Ternário** explora a lógica de três estados — mais próxima da realidade natural e da lógica fuzzy.*

### ⚙️ Codificação BET — Binary-Encoded Ternary

Como ainda não existe hardware que opere nativamente em 3 estados, o **Universo Ternário** implementa a computação ternária através da codificação **BET** (*Binary-Encoded Ternary*).

Cada **trit** (dígito ternário) é codificado em **dois bits** binários:

| Trit | Bits (BET) | Descrição |
|------|------------|-----------|
| **+1** | `10` | Positivo / Sim |
| **0**  | `11` | Neutro / Talvez |
| **-1** | `01` | Negativo / Não |
| — | `00` | **Erro / Inválido** (reservado para detecção de falhas) |

#### 💡 Por que BET?

- ✅ **Hardware binário existente** — não precisamos esperar por transistores ternários
- ✅ **Detecção de erros integrada** — o padrão `00` acusa erros automaticamente
- ✅ **Lógica ternária balanceada** — operações aritméticas e lógicas em 3 estados
- ✅ **Caminho para o futuro** — quando o hardware ternário surgir, a transição será natural

### 🏗️ Arquitetura BET — Visão Geral

A imagem abaixo ilustra a estrutura completa da codificação BET no Universo Ternário, mostrando o fluxo desde os softwares e arquivos até os circuitos digitais e manutenção técnica:

<div align="center">
  <img src="https://raw.githubusercontent.com/henriquejne/henriquejne/main/assets/arquitetura_bet.png" alt="Arquitetura BET — Universo Ternário" width="100%">
  <p><em>Arquitetura BET: Software → Circuitos Digitais → Manutenção Técnica</em></p>
</div>

**Componentes da arquitetura:**

1. **Software e Arquivos** — Dados ternários codificados em pares de bits (01, 01 / 10, 01 / 01, 01)
2. **Tabela de Conversão Ternária** — Mapeamento direto entre trits balanceados e binário:
   - TRIT +1 (Verdadeiro, Positivo, +5V) → `10`
   - TRIT 0 (Neutro, 0V) → `11`
   - TRIT -1 (Falso, Negativo, -5V) → `01`
   - **Detecção de erro:** `00` = Erro (Falha de Hardware)
3. **Circuitos Digitais** — Decodificador de trit com controle de tensão e seleção de voltagem (+5V, 0V, -5V)
4. **Barramento Ternário Simulado** — Bus que transporta os trits codificados em binário
5. **Manutenção Técnica** — Fluxo de diagnóstico com verificação de código:
   - Código válido (10, 11, 01) → Operação Normal
   - Código inválido (00) → Erro Detectado (Linha Desconectada / Falha)

### 🤖 Inteligência Artificial

> **O Universo Ternário é desenvolvido com suporte de Inteligência Artificial.**
>
> Ver arquivo [NOTICE](NOTICE).

O uso de ferramentas de Inteligência Artificial (IA) auxilia na pesquisa, desenvolvimento, documentação e divulgação da computação ternária. A lógica ternária balanceada, a codificação BET e as arquiteturas propostas são conceitos originais do projeto Universo Ternário.

### 🚀 Sobre o Projeto

O **Universo Ternário** é um projeto de pesquisa e desenvolvimento dedicado exclusivamente à divulgação e implementação da computação ternária. Nosso foco é:

- 📐 **Arquiteturas ternárias** baseadas em BET
- 🔧 **Simuladores e emuladores** de processadores ternários
- 📚 **Educação** — tornar a computação ternária acessível a todos
- 🧪 **Experimentação** — provar que sistemas ternários são viáveis hoje

> **Líder do projeto:** `Henriquejne`

### 📦 Repositórios

> 🔒 **Em breve:** nossos repositórios estão em desenvolvimento privado e serão liberados publicamente assim que atingirem maturidade suficiente para a comunidade.

Fique de olho — o Universo Ternário está se expandindo. 🌌

---

## 🇺🇸 English

### 🧠 What is Ternary Computing?

Ternary computing operates with **three logical states** instead of two:

| State | Meaning |
|-------|---------|
| **+1** | Yes / True / Positive |
| **0**  | Maybe / Indeterminate / Neutral |
| **-1** | No / False / Negative |

> *While traditional computing lives in the binary world (0 and 1), **Universo Ternário** explores three-state logic — closer to natural reality and fuzzy logic.*

### ⚙️ BET Encoding — Binary-Encoded Ternary

Since hardware that operates natively in 3 states does not yet exist, **Universo Ternário** implements ternary computing through the **BET** (*Binary-Encoded Ternary*) encoding.

Each **trit** (ternary digit) is encoded into **two binary bits**:

| Trit | Bits (BET) | Description |
|------|------------|-------------|
| **+1** | `10` | Positive / Yes |
| **0**  | `11` | Neutral / Maybe |
| **-1** | `01` | Negative / No |
| — | `00` | **Error / Invalid** (reserved for fault detection) |

#### 💡 Why BET?

- ✅ **Existing binary hardware** — we don't need to wait for ternary transistors
- ✅ **Built-in error detection** — the `00` pattern automatically flags errors
- ✅ **Balanced ternary logic** — arithmetic and logical operations in 3 states
- ✅ **Path to the future** — when ternary hardware emerges, the transition will be seamless

### 🏗️ BET Architecture — Overview

The image below illustrates the complete structure of BET encoding in Universo Ternário, showing the flow from software and files to digital circuits and technical maintenance:

<div align="center">
  <img src="https://raw.githubusercontent.com/henriquejne/henriquejne/main/assets/arquitetura_bet.png" alt="BET Architecture — Universo Ternário" width="100%">
  <p><em>BET Architecture: Software → Digital Circuits → Technical Maintenance</em></p>
</div>

**Architecture components:**

1. **Software & Files** — Ternary data encoded in bit pairs (01, 01 / 10, 01 / 01, 01)
2. **Ternary Conversion Table** — Direct mapping between balanced trits and binary:
   - TRIT +1 (True, Positive, +5V) → `10`
   - TRIT 0 (Neutral, 0V) → `11`
   - TRIT -1 (False, Negative, -5V) → `01`
   - **Error detection:** `00` = Error (Hardware Failure)
3. **Digital Circuits** — Trit decoder with voltage control and selection (+5V, 0V, -5V)
4. **Simulated Ternary Bus** — Bus that transports trits encoded in binary
5. **Technical Maintenance** — Diagnostic flow with code verification:
   - Valid code (10, 11, 01) → Normal Operation
   - Invalid code (00) → Error Detected (Disconnected Line / Failure)

### 🤖 Artificial Intelligence

> **Universo Ternário is developed with Artificial Intelligence support.**
>
> See [NOTICE](NOTICE) file.

The use of Artificial Intelligence (AI) tools assists in the research, development, documentation, and dissemination of ternary computing. The balanced ternary logic, the BET encoding, and the proposed architectures are original concepts of the Universo Ternário project.

### 🚀 About the Project

**Universo Ternário** is a research and development project exclusively dedicated to the dissemination and implementation of ternary computing. Our focus is:

- 📐 **Ternary architectures** based on BET
- 🔧 **Simulators and emulators** of ternary processors
- 📚 **Education** — making ternary computing accessible to everyone
- 🧪 **Experimentation** — proving that ternary systems are viable today

> **Project lead:** `Henriquejne`

### 📦 Repositories

> 🔒 **Coming soon:** our repositories are currently in private development and will be released publicly as soon as they reach sufficient maturity for the community.

Stay tuned — the Ternary Universe is expanding. 🌌

---

## 🌐 Conecte-se / Connect With Us

| Plataforma / Platform | Link |
|-----------------------|------|
| 🎬 **YouTube** | [youtube.com/@UniversoTernário](https://www.youtube.com/@UniversoTernário) |
| 📱 **TikTok** | [tiktok.com/@universoternario7](https://tiktok.com/@universoternario7?lang=pt-BR) |
| 🐦 **X (Twitter)** | [x.com/henriqu07337076](https://x.com/henriqu07337076) |
| 📧 **Email** | [universoternario@gmail.com](mailto:universoternario@gmail.com) |

---

## 📄 Licença / License

```
Copyright 2026 L Henrique B Santos

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```

---

<div align="center">

**Universo Ternário** — *Sim, Não e Talvez. / Yes, No and Maybe.* 🌌

</div>
