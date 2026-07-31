# 🛠️ Exercícios Práticos de XML – Identificação e Correção de Erros

## 📌 Visão Geral
Este repositório contém o resultado de uma atividade prática voltada para a análise, identificação e resolução de erros de sintaxe em documentos XML. O foco do trabalho foi examinar diferentes trechos de código com falhas estruturais e aplicar as correções necessárias para transformá-los em arquivos XML bem-formatados (*well-formed XML*).

---

## 🚀 O que foi feito

Durante a atividade, foram analisados diversos cenários contendo inconsistências comuns no desenvolvimento XML. Para cada situação, o trabalho consistiu em:

1. **Diagnóstico do Código:** Leitura atenta para identificar violações das regras do padrão W3C para XML.
2. **Mapeamento de Erros:** Classificação dos problemas encontrados (erros de sintaxe, aninhamento, atributos ou nomenclatura).
3. **Refatoração e Correção:** Reescrita dos trechos de código garantindo a correta interpretação por qualquer analisador (*parser*) XML.

---

## 🔑 Principais Regras e Conceitos Abordados

As correções realizadas cobriram os principais pilares da sintaxe XML, tais como:

* **Declaração XML (Prólogo):** Ajuste na formatação e fechamento correto da tag `<?xml ... ?>`.
* **Fechamento e Aninhamento de Tags:** Garantia de que toda tag aberta possua seu fechamento correspondente e respeite a hierarquia em árvore (sem cruzamento de tags).
* **Aspas em Atributos:** Padronização de aspas duplas ou simples para envolver obrigatoriamente os valores de todos os atributos.
* **Uso de Caracteres Reservados:** Substituição de símbolos como `&` por entidades de escape (`&amp;`) dentro dos dados do texto.
* **Nomenclatura Válida:** Ajuste no nome dos elementos para remover espaços internos e evitar o uso de números no início do nome das tags.
* **Sintaxe dos Elementos:** Separação adequada entre nomes de tags, atributos e o conteúdo textual dos elementos.

---

## 🎯 Objetivo Concluído
Com a realização dos exercícios, consolidou-se o domínio prático sobre a estrutura básica do XML, garantindo a capacidade de construir e auditar arquivos legíveis, válidos e livres de erros de sintaxe.