# Sistema Automatizado de Esteira de Separação de Produtos

Projeto desenvolvido para a disciplina de Sistemas Automatizados da Universidade São Judas Tadeu.

## Sobre o Projeto

O sistema simula uma esteira automatizada capaz de identificar e separar produtos de diferentes tipos utilizando lógica Ladder em um CLP.

A classificação é realizada por sensores, enquanto desviadores direcionam os produtos para o destino correto de forma automática.

## Objetivo

Desenvolver e validar uma lógica de controle para:

- Identificar produtos na esteira;
- Classificar os itens por tipo;
- Acionar os desviadores correspondentes;
- Registrar a quantidade de produtos processados;
- Sinalizar produtos não identificados.

## Funcionamento

1. O operador liga a esteira.
2. O sensor de presença detecta o produto.
3. O sensor de classificação identifica o tipo:
   - Tipo A → Valor 0
   - Tipo B → Valor 1
   - Não identificado → Valor 2
4. O CLP processa a informação.
5. O desviador correto é acionado.
6. Os contadores registram os dados de produção.

## Tecnologias Utilizadas

- CLP (Controlador Lógico Programável)
- Linguagem Ladder (IEC 61131-3)
- PLC Simulator Online

## Componentes

- Sensor de Presença
- Sensor de Classificação
- Motor da Esteira
- Desviador A
- Desviador B
- Alarme

## Resultados

Os testes realizados no simulador apresentaram:

- 100% de acerto na separação dos produtos;
- Nenhuma falha de triagem;
- Funcionamento estável da lógica de controle;
- Contagem correta dos itens processados.

## Melhorias Futuras

- Sensores de fim de curso nos desviadores;
- Monitoramento de enchimento das caixas;
- Interface HMI/SCADA;
- Integração com sistemas MES.

## Integrantes

- Pedro Henrique Sardinha
- Vinicius Gomes da Silva
- Felipe Delfiol Bernardes
- Lucas Agnelli
- Cauã Carrilla Molinaro

## Instituição

**Universidade São Judas Tadeu**  
Curso de Engenharia de Software  
Disciplina: Sistemas Automatizados  
Professor: Robson Calvetti
