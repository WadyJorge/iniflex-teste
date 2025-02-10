# 🧑‍💻 Teste Prático - Iniflex

Este projeto foi desenvolvido como parte do teste técnico Iniflex. O objetivo é desenvolver um projeto Java que segue os requisitos fornecidos.

---

## 📋 Requisitos do Projeto

### Classes

1. **Classe `Pessoa`**:
   - Atributos: `nome` (String) e `dataNascimento` (LocalDate).

2. **Classe `Funcionario`**:
   - Estende a classe `Pessoa`.
   - Atributos adicionais: `salario` (BigDecimal) e `funcao` (String).

3. **Classe `Principal`**:
   - Contém o método `main` para executar as ações solicitadas.

---

## 🛠️ Funcionalidades Implementadas

A classe `Principal` executa as seguintes ações:

1. **Inserir Funcionários**:
   - Adiciona todos os funcionários conforme a tabela fornecida.

2. **Remover Funcionário**:
   - Remove o funcionário "João" da lista.

3. **Imprimir Funcionários**:
   - Exibe todos os funcionários com informações formatadas:
     - Data no formato `dd/MM/aaaa`.
     - Valores numéricos com separador de milhar como ponto e decimal como vírgula.

4. **Aumento de Salário**:
   - Aumenta o salário de todos os funcionários em 10%.

5. **Agrupar por Função**:
   - Agrupa os funcionários por função em um `Map`.

6. **Imprimir Agrupado por Função**:
   - Exibe os funcionários agrupados por função.

7. **Aniversariantes dos Meses 10 e 12**:
   - Imprime os funcionários que fazem aniversário nos meses de outubro (10) e dezembro (12).

8. **Funcionário Mais Velho**:
   - Exibe o funcionário mais velho, com nome e idade.

9. **Ordenar por Nome**:
   - Imprime a lista de funcionários em ordem alfabética.

10. **Total dos Salários**:
    - Calcula e exibe o total dos salários dos funcionários.

11. **Salários em Salários Mínimos**:
    - Exibe quantos salários mínimos cada funcionário ganha, considerando o salário mínimo de R$ 1212,00.

---

## 🚀 Como Executar o Projeto

### Pré-requisitos

- Java 17 ou superior.
- Maven (opcional, para gerenciamento de dependências).

### Passos

1. Clone o repositório:
   ```bash
   git clone https://github.com/WadyJorge/iniflex-teste.git
