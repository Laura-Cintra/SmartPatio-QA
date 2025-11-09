# SmartPátio — Challenge Mottu

<img src="logo-app-dark.png" alt="Logo do Projeto" width="120" height="120">

## 🔗 Links Entregáveis

1. **Azure Boards:** [Acessar Plano de testes](https://dev.azure.com/Challenge-Mottu/SmartPatio/_boards/board/t/SmartPatio%20Team/Features)

---

## 1. Problema

Atualmente, o processo de **gestão e localização das motos nos pátios da Mottu** é manual e pouco eficiente.  
Isso gera **perda de tempo**, **falhas operacionais** e **dificuldade para encontrar motos específicas**, especialmente quando o pátio tem grande volume de veículos.

---

## 2. Solução

O **SmartPátio** é um sistema desenvolvido que utiliza **IoT** e **visão computacional** para automatizar o controle do entrada e localização das motos nos pátios Mottu.  

### 🔹 Componentes da Solução

1. **App Mobile (React Native + Expo):** interface para cadastro, gestão e busca de motos em tempo real.
2. **Dispositivo IoT (“carrapato”):** dispositivo acoplado à moto, com LED âmbar e buzzer. Quando acionado via app, o carrapato **pisca e apita**, indicando a posição exata da moto.
3. **Leitura automática de placas:** via câmera e OCR, otimizando o processo de entrada e saída das motos.
4. **Sistema Java (Spring Boot):** Atua como o **monitor do pátio**, exibindo dashboards e informações úteis para o gestor do pátio.
5. **Banco de Dados (Oracle):** Centraliza todas as informações de motos, pátios, usuários e logs de movimentação.
6. **Azure DevOps:** Utilizado para **integração contínua (CI/CD)**, **gerenciamento ágil (Boards)** e **deploy automatizado** no Azure App Service.

Essa integração torna o processo mais **ágil**, **automatizado** e **confiável**, eliminando erros e aumentando a eficiência do pátio.

---

## Integrantes

| Nome                              | RM     | Turma  | GitHub                                             |
| --------------------------------- | ------ | ------ | -------------------------------------------------- |
| **Laura de Oliveira Cintra**      | 558843 | 2TDSPJ | [@Laura-Cintra](https://github.com/Laura-Cintra)   |
| **Maria Eduarda Alves da Paixão** | 558832 | 2TDSPJ | [@MariaEdPaixao](https://github.com/MariaEdPaixao) |
| **Vinícius Saes de Souza**        | 554456 | 2TDSPY | [@ViniciuSaeSouza](https://github.com/ViniciuSaeSouza) |

---
> **SmartPátio** - Tecnologia a favor da eficiência operacional nos pátios da Mottu.
