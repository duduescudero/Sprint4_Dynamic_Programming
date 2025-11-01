# Dynamic Programming – Sprint 4

## Integrantes
- Arthur Felipe – RM: 553320  
- Eduardo Pires – RM: 556527  
- Luca Monteiro – RM: 556906  
- Leonardo Munhoz – RM: 556824  
- Davi Vieira – RM: 556798  

---

## 📘 Descrição do Projeto
Este projeto foi desenvolvido como parte da disciplina **Dynamic Programming** na Sprint 4.  
O objetivo é otimizar o controle de consumo e reposição de insumos em unidades de diagnóstico, utilizando **Programação Dinâmica** para minimizar o custo total de pedidos e armazenagem.

---

## 🧩 Estrutura e Algoritmos Utilizados

### 1️⃣ Estruturas de Dados
- **Listas** para armazenar demandas e tabelas de custos (`dp`, `choice`).
- **Tabelas acumuladas** (`cum`) para cálculo rápido de somas parciais de demanda.

### 2️⃣ Algoritmos
- **Versão Recursiva:** implementa o raciocínio direto da decisão de pedidos.  
- **Versão Memoizada (Top-Down):** armazena resultados intermediários para evitar recomputações.  
- **Versão Iterativa (Bottom-Up):** preenche a tabela de DP de trás para frente, sendo a mais eficiente.

---

## 🧮 Resultados
- **Custo total mínimo:** 261.0  
- **Plano ótimo de pedidos:**
  - Pedido no dia 1 → cobre dias 1–4 → 28 unidades  
  - Pedido no dia 5 → cobre dias 5–8 → 24 unidades  
  - Pedido no dia 9 → cobre dias 9–10 → 17 unidades  

---

## 🧠 Conclusão
O uso de **Programação Dinâmica** permitiu otimizar o processo de reposição de insumos, garantindo uma solução eficiente e de menor custo.  
Os três métodos — recursivo, memoizado e iterativo — produzem resultados idênticos, comprovando a consistência do modelo.

---


