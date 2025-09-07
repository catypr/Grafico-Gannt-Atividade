# Grafico-Gannt-Atividade
```mermaid
gantt
title Construção de Casa
dateFormat YYYY-MM-DD
section Início do Projeto
Planejamentos e Aprovações: active, a1, 2025-05-01, 20d
Preparação do Terreno: crit, a2, after a1, 10d
Construção da Casa: crit, a3, after a2, 15d
Fundação: crit, a4, after a3, 30d
Instalção Elétrica e Hidráulica: crit, a5, after a4, 20d
Acabamento Interno: crit, a6, after a5, 25d
Acabento Externo: crit, a7, after a6, 15d
Inspeção Final e Entrega da Casa: crit, a8, after a7, 5d
