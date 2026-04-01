# 🧠 Neural Datapath Simulator

---

## 🇧🇷 Português

### 📖 Visão Geral

O **Neural Datapath Simulator** é um projeto que integra conceitos de **Arquitetura de Computadores e Inteligência Artificial**, com foco na **simulação de um neurônio artificial utilizando um modelo inspirado em datapath**.

O projeto demonstra como operações fundamentais de hardware — como acesso à memória, uso de registradores e execução na ULA — impactam diretamente o custo computacional no treinamento de modelos de IA.

---

### 🎯 Objetivos

* Simular o funcionamento de um neurônio artificial
* Relacionar Inteligência Artificial com arquitetura de hardware
* Analisar custo computacional (RAM, registradores e ULA)
* Demonstrar aprendizado supervisionado (perceptron)
* Explorar limitações da arquitetura de von Neumann

---

### 📊 Funcionalidades

* Simulação de operações de memória e registradores
* Execução de operações da ULA (adição e subtração)
* Implementação de um neurônio artificial
* Execução do forward pass
* Atualização de pesos baseada no erro
* Monitoramento de custo computacional

---

### 🧠 Funcionamento do Modelo

O modelo simula um neurônio com:

* Entradas: `x1`, `x2`
* Pesos: `w1`, `w2`
* Limiar: `θ`

O sistema executa:

1. Cálculo da soma ponderada (`z`)
2. Aplicação da função de ativação
3. Comparação com o valor esperado (`d`)
4. Atualização dos pesos com base no erro

Todas as operações são realizadas via **simulação explícita de hardware**.

---

### 📁 Estrutura do Repositório

```
neural-datapath-simulator/
├── neural-datapath-simulator.ipynb
├── README.md
├── LICENSE
└── .gitignore
```

---

### ▶️ Como Executar

**Pré-requisitos**

* Python 3.x
* Jupyter Notebook

**Passos**

```bash
git clone <repository-url>
cd neural-datapath-simulator
jupyter notebook
```

Execute o arquivo:

```
neural-datapath-simulator.ipynb
```

---

### 🛠️ Tecnologias e Conceitos

* Python
* Arquitetura de Computadores
* Modelo de von Neumann
* Inteligência Artificial
* Perceptron
* Simulação de hardware (RAM, registradores, ULA)

---

### 📈 Diferenciais

Este projeto não utiliza bibliotecas de machine learning, implementando toda a lógica do neurônio a partir de operações de hardware simuladas.

Isso permite uma compreensão mais profunda do custo computacional envolvido na execução de modelos de IA.

---

### 📌 Status

✔ Estável — simulação funcional com análise de custo computacional

---

### 👥 Autores

* Augusto Oliveira
* Felipe de Oliveira Cabral
* Gabriel Tonelli Avelino Dos Santos
* Vinícius Adrian Siqueira de Oliveira
* Sofia Bueris Netto de Souza

---

### 📄 Licença

Este projeto está licenciado sob a **MIT License** — consulte o arquivo `LICENSE` para mais detalhes.

---

## 🇺🇸 English

### 📖 Overview

**Neural Datapath Simulator** is a project that combines **Computer Architecture and Artificial Intelligence**, focusing on the **simulation of an artificial neuron using a datapath-inspired model**.

The project demonstrates how fundamental hardware operations — such as memory access, register usage, and ALU execution — directly impact the computational cost of training AI models.

---

### 🎯 Objectives

* Simulate an artificial neuron
* Connect AI concepts with hardware architecture
* Analyze computational cost (RAM, registers, ALU)
* Demonstrate supervised learning (perceptron)
* Explore limitations of von Neumann architecture

---

### 📊 Features

* Simulation of memory and register operations
* Execution of ALU operations (addition and subtraction)
* Artificial neuron implementation
* Forward pass execution
* Weight update mechanism
* Computational cost tracking

---

### 🧠 Model Behavior

The model simulates a neuron with:

* Inputs: `x1`, `x2`
* Weights: `w1`, `w2`
* Threshold: `θ`

The system performs:

1. Weighted sum calculation (`z`)
2. Activation function application
3. Comparison with expected value (`d`)
4. Weight update based on error

All operations are executed through **explicit hardware simulation**.

---

### 📁 Repository Structure

```
neural-datapath-simulator/
├── neural-datapath-simulator.ipynb
├── README.md
├── LICENSE
└── .gitignore
```

---

### ▶️ How to Run

**Prerequisites**

* Python 3.x
* Jupyter Notebook

**Steps**

```bash
git clone <repository-url>
cd neural-datapath-simulator
jupyter notebook
```

Run the file:

```
neural-datapath-simulator.ipynb
```

---

### 🛠️ Technologies and Concepts

* Python
* Computer Architecture
* Von Neumann Model
* Artificial Intelligence
* Perceptron
* Hardware simulation (RAM, registers, ALU)

---

### 📈 Highlights

This project does not rely on machine learning libraries, implementing the neuron logic entirely through simulated hardware operations.

This approach provides a deeper understanding of the computational cost behind AI model execution.

---

### 📌 Status

✔ Stable — functional simulation with computational cost analysis

---

### 📄 License

This project is licensed under the **MIT License** — see the `LICENSE` file for details.

---
