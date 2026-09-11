# Gerador de CPF 🔢

## Descrição
Este projeto é um gerador de Cadastro de Pessoas Físicas (CPF) desenvolvido em Python, que cria números de CPF válidos seguindo as regras oficiais de geração.

## Funcionalidades
- Gera 100 CPFs válidos automaticamente
- Implementa o algoritmo oficial de cálculo dos dígitos verificadores
- Aleatoriedade na geração dos 9 primeiros dígitos

## Como Funciona 🧮
O algoritmo segue estas etapas:

1. Gera 9 dígitos aleatórios
2. Calcula o primeiro dígito verificador:
   - Multiplica cada dígito por um peso regressivo (10 a 2)
   - Soma os resultados
   - Aplica o cálculo para obter o primeiro dígito
3. Calcula o segundo dígito verificador:
   - Usa os 9 dígitos originais + primeiro dígito verificador
   - Multiplica por pesos regressivos (11 a 2)
   - Soma os resultados
   - Aplica o cálculo para obter o segundo dígito

## Exemplo de Uso
```python
# Execute o script para gerar 100 CPFs
python gerador_cpf.py
```

## Você pode gerar a vontade com o link abaixo:
https://geraldohumberto.github.io/gerador_cpf/

## Regras e Validação
- Gera números que passam na validação do algoritmo oficial
- Não garante que sejam CPFs reais, apenas matematicamente válidos

## Tecnologias
- Linguagem: Python
- Bibliotecas: `random`, `sys`

## Contribuição
Sinta-se livre para abrir issues ou enviar pull requests.

## Licença
MIT License
