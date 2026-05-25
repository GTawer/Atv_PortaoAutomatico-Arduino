# 📳 Sistema Automatizado de Controle de Portão: Automação e Controle de Acesso com Arduino 🔌

![Status](https://img.shields.io/badge/Status-Conclu%C3%ADdo-brightgreen?style=for-the-badge&logo=github)
![Platform](https://img.shields.io/badge/Plataforma-Tinkercad%20%2F%20Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)

Este projeto simula uma solução real de automação industrial e residencial para resolver problemas de controle de acesso de veículos em um estacionamento privado. O sistema substitui a operação manual por um controle automatizado inteligente, mitigando riscos de segurança e falhas operacionais através de sinalização visual e controle de movimento preciso.

A lógica foi desenvolvida em **C++** e implementada utilizando o microcontrolador **Arduino UNO**, associado a um **Servo Motor** e LEDs indicadores de estado.

---

## 📂 Detalhes do Projeto

| Item | Descrição | Status |
| :--- | :--- | :--- |
| `Hardware` | Montagem de Servo Motor, 2 Botões de comando e LEDs indicadores na Protoboard. | ✅ |
| `Controle de Movimento`| Posicionamento angular preciso do servo para simular abertura (90°) e fechamento (160°). | ✅ |
| `Sinalização Visual` | Lógica de LEDs para indicar o status do portão (em movimento ou fechado/parado). | ✅ |
| `Código-Fonte` | Programação embarcada em C++ utilizando a biblioteca `Servo.h`. | ✅ |

---

## ⚙️ Funcionamento e Lógica do Sistema

O protótipo foi programado para responder de forma imediata aos comandos dos operadores, seguindo as seguintes regras de negócio:

* **Comando "ABRE":** * O Servo Motor gira para o ângulo de **90°** (simulando a abertura completa).
  * Os **LEDs Verde e Vermelho piscam alternadamente**, servindo como alerta visual de que o portão está em movimento.
* **Comando "FECHA":** * O Servo Motor gira para o ângulo de **160°** (simulando o fechamento).
  * Ambos os **LEDs permanecem apagados**, indicando de forma clara que o portão concluiu o curso, está fechado e parado.

> ⚠️ **Foco em Segurança:** A transição visual dos LEDs resolve o problema crítico da falta de feedback para os operadores, evitando acidentes e colisões de veículos com a estrutura do portão.

---

## 🔗 Link do Projeto
* [Acesse aqui o projeto no Tinkercad - Seu Nome](https://www.tinkercad.com/things/seu-link-aqui)

---

## 🛠️ Ferramentas Utilizadas

* **Tinkercad:** Plataforma de simulação do circuito eletrônico.
* **Arduino UNO:** Microcontrolador responsável pela inteligência do sistema.
* **Servo Motor SG90:** Atuador utilizado para simular o movimento mecânico do portão.
* **Linguagem C/C++:** Código estruturado com manipulação de registradores digitais e controle de interrupções/condicionais (`if/else`).

---

## 👥 Autores

* **Disciplina:** Lógica de Programação / Internet das Coisas (IoT)
* **Professores:** [Nome do Professor]
* **Equipe (Alunos):**
  * Seu Nome (Nº XX) - *Dev & Hardware*
  * Nome do Colega (Nº XX) - *Dev & Hardware*
* **Data:** 25/05/2026

#### Projeto desenvolvido no SENAI.

<p align="left">
  <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExbmhzcWZ3ODd5cHdyYXRvbnM4dnplazhrOHQ1eTNqZW92dHl5ZnlhNiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/3gYWogv6vnbrq/giphy.gif" width="220" height="auto" alt="Automatic Gate Animation" />
</p>
