# Validador de CPF

## Objetivo

Validador de CPF desenvolvido em JavaScript puro que verifica se um CPF é válido usando o algoritmo oficial de validação.

## Funcionalidades

- Validação de CPF usando o algoritmo oficial
- Formatação automática do campo de entrada
- Verificação de CPFs com todos os números iguais
- Validação pressionando Enter
- Interface responsiva

## Como Usar

1. Abra o arquivo index.html no navegador
2. Digite um CPF (com ou sem formatação)
3. Clique em "Validar CPF" ou pressione Enter
4. Visualize o resultado

## Exemplos para Teste

**CPFs Válidos:**
- 11144477735
- 12345678909

**CPFs Inválidos:**
- 11111111111 (todos os números iguais)
- 123456789 (menos de 11 dígitos)
- 12345678900 (dígitos verificadores incorretos)

## Como Funciona

O algoritmo de validação segue os seguintes passos:

1. Remove formatação (pontos, traços, espaços)
2. Verifica se tem exatamente 11 dígitos
3. Verifica se não são todos os números iguais
4. Calcula o primeiro dígito verificador
5. Calcula o segundo dígito verificador
6. Compara os dígitos calculados com os informados

## Estrutura do Código

- `validateCPF()` - Função principal de validação
- `isValidCPF()` - Implementa o algoritmo de validação
- `formatCPF()` - Formata o CPF para exibição
- `showResult()` - Exibe o resultado na interface

## Tecnologias

- HTML5
- CSS3
- JavaScript

## Execução

Abra o arquivo index.html em qualquer navegador moderno. Não requer servidor web.