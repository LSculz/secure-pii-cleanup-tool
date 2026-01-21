# secure-pii-cleanup-tool
# Automação de Limpeza de Dados PII em Ambiente Fintech 🔒

Este repositório apresenta uma solução prática e eficiente que desenvolvi para resolver um problema real de acúmulo de dados sensíveis e performance em uma estação de trabalho dentro de uma Fintech.

## 📋 Cenário e Motivação
No fluxo diário de formalização de propostas de crédito, recebemos um grande volume de documentos de clientes. O acúmulo desses arquivos gerava dois pontos de atenção:
1. **Risco de Segurança:** Manter documentos com dados pessoais (PII) localmente após o processamento aumenta a superfície de exposição.
2. **Performance:** O volume de arquivos impactava o desempenho da máquina e a organização do diretório de trabalho.

## 🚀 A Solução
Utilizando conceitos iniciais de **Cibersegurança e Higiene Digital**, criei um script de automação simples e eficaz para garantir que nenhum dado sensível permanecesse na máquina após o expediente.

### 🛠️ Implementação Técnica

1. **O Script (`.bat`):**
   Utilizei a linguagem de script do Windows (Batch) para criar um comando de limpeza rápida.
   ```batch
   @echo off
   :: Navega até o diretório alvo e remove todos os arquivos de forma silenciosa
   del /q "C:\Caminho\Para\Seus\Documentos\*.*"
