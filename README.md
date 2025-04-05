# Processo Seletivo - Desafio de Código Java Cloud Native Bradesco (DIO)

![Java](https://img.shields.io/badge/Java-Cloud_Native-blue) ![DIO](https://img.shields.io/badge/DIO-Bootcamp-green)

Este repositório contém a implementação de um desafio de código do Bootcamp **Java Cloud Native Bradesco**, desenvolvido na plataforma **DIO**. O objetivo deste projeto é simular um processo seletivo para candidatos, onde são realizadas diversas operações como seleção com base no salário pretendido, tentativas de contato e análise dos candidatos.

---

## 📋 **Funcionalidades Implementadas**

1. **Seleção de Candidatos**
   - Os candidatos são avaliados com base no salário que solicitam.
   - Somente os candidatos que solicitam um salário igual ou inferior ao salário base da vaga são selecionados.
   - A seleção é limitada a 5 candidatos.

2. **Tentativas de Contato**
   - Para cada candidato, o sistema realiza até 3 tentativas de contato.
   - Caso o candidato atenda, o contato é considerado realizado com sucesso.
   - Caso contrário, o sistema informa que não foi possível realizar o contato após as tentativas máximas.

3. **Lista de Candidatos**
   - Exibe uma lista numerada dos candidatos participantes do processo seletivo.

4. **Análise de Candidatos**
   - Analisa o salário pretendido pelo candidato e sugere ações como ligar para o candidato, fazer uma contra-proposta ou aguardar o resultado dos demais candidatos.

---

## 🛠️ **Estrutura do Código**

### **Métodos Principais**

1. **`main(String[] args)`**
   - Ponto de entrada do programa.
   - Executa o processo de tentativas de contato com os candidatos.

2. **`selecaoCandidatos()`**
   - Realiza a seleção dos candidatos com base no salário pretendido.
   - Limita o número de candidatos selecionados a 5.

3. **`entrandoEmContato(String candidato)`**
   - Simula tentativas de contato com um candidato.
   - Realiza até 3 tentativas e exibe o resultado.

4. **`imprimirSelecionados()`**
   - Exibe uma lista numerada dos candidatos participantes.

5. **`analisarCandidatos(double salarioPretendido)`**
   - Analisa o salário pretendido pelo candidato e sugere ações.

6. **`valorPretendido()`**
   - Gera um valor aleatório de salário pretendido entre R$ 1.800,00 e R$ 2.200,00.

7. **`atender()`**
   - Simula a probabilidade de um candidato atender o contato.

---
