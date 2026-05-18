# 🧠 Caderno Temático Inteligente: Python e IA Aplicados à Automação e Processos Comerciais
**Autora:** Daiana Mendes  
**Programa:** DIO Campus Expert #16 & Santander Open Academy  
**Ferramentas Utilizadas:** NotebookLM (Google), GitHub, Python 3.

---

## 🎯 1. Contexto e Objetivos

Este repositório foi construído como parte de um projeto prático de aprendizagem ativa utilizando Inteligência Artificial. O objetivo central é consolidar um **"Segundo Cérebro"** utilizando a ferramenta **NotebookLM** para acelerar a transição de carreira para o mercado de tecnologia, unindo uma sólida bagagem comercial em vendas complexas (SaaS/High-Ticket) com competências técnicas em **Python, Estruturas de Dados e Automação**.

### Objetivos de Estudo:
* Dominar a sintaxe básica de Python orientada à limpeza e padronização de dados brutos (Strings).
* Compreender a aplicação de estruturas condicionais na tomada de decisão de sistemas automatizados.
* Utilizar IA generativa de forma crítica como assistente de desenvolvimento (*copiloto*), documentando falhas, acertos e processos de troubleshooting (resolução de problemas).

---

## 📚 2. Curadoria de Fontes

Para alimentar o modelo de contexto do NotebookLM e estruturar o ecossistema de estudos, foram selecionadas e validadas as seguintes fontes abertas de conhecimento:

1.  **Artigo Técnico: 10 Dicas Essenciais para Iniciantes em Python para Análise de Dados** (Katherine, 2026) - Focado em boas práticas de ambiente (Jupyter Notebook) e introdução às bibliotecas Pandas e Seaborn.
2.  **Documentação Oficial do Python (Python.org)** - Seções específicas sobre manipulação de métodos de string (`.strip()`, `.split()`, `.join()`) e controle de fluxo (`if`, `elif`, `else`).
3.  **Material Didático DIO: Bootcamp Python para Análise e Automação de Dados** - Grades conceituais e guias de projetos de portfólio práticos.

---

## ⚡ 3. Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

O desenvolvimento técnico não ocorre em linha reta. Abaixo estão documentados os testes de prompts, erros reais enfrentados durante a execução dos scripts na plataforma DIO e as respectivas correções baseadas em raciocínio lógico.

### Cenário 1: O Erro de Indentação Fantasma
* **Prompt de Contexto:** *"Estou tentando rodar uma estrutura condicional em Python para avaliar faixas de bônus e valores de compra, mas o sistema está retornando erro na linha do else."*
* **Resposta da IA / Diagnóstico:** A IA identificou que trechos de comentários textuais de instrução (`TODO`) estavam grudados na mesma linha do código, além de espaços irregulares antes das palavras-chave.
* **Cicatriz (O que aprendi):** O Python é uma linguagem rigidamente estruturada por espaços (indentação). Espaços invisíveis provocam o erro `IndentationError: unexpected indent`.
* **Solução Implementada:** Reset do editor de código, remoção de caracteres ocultos e alinhamento obrigatório de 4 espaços para blocos internos de execução.

### Cenário 2: Padronização de Dados de Leads (Strings)
* **Prompt Aplicado:** *"Como tratar uma string de entrada onde o usuário pode digitar espaços duplos ou letras totalmente desordenadas (maiúsculas e minúsculas misturadas) para salvar o nome de forma limpa em um CRM?"*
* **Resultado e Referência:** Uso combinado dos métodos `.strip().split()` seguido de *List Comprehension* com `.capitalize()`. O comportamento do método `.split()` sem argumentos provou ser a melhor solução para eliminar múltiplos espaços internos automaticamente.

---

## 📑 4. Miniguia de Estudo (Entrega Final)

### 📘 Resumos Estruturados do Assunto

#### A) Tomada de Decisão Automatizada (Estruturas Condicionais)
Sistemas de software utilizam blocos lógicos (`if`, `elif`, `else`) para direcionar o comportamento do usuário. Em ecossistemas de vendas SaaS, essa lógica é aplicada para definir regras de desconto automáticas no checkout, roteamento de leads para diferentes vendedores ou gatilhos de alertas de churn baseados no comportamento do cliente.

#### B) Higienização de Dados (String Manipulation)
Dados inseridos por humanos são, por natureza, bagunçados. Antes de enviar qualquer informação para um banco de dados SQL ou disparar uma automação via API, o sistema precisa higienizar o texto. A remoção de ruídos textuais garante a integridade dos relatórios gerenciais (BI).

### 📖 Glossário de Conceitos Aprendidos
* **`input()`**: Função nativa do Python utilizada para capturar dados inseridos pelo usuário através do terminal.
* **`int()`**: Função de conversão de tipo (casting) que transforma uma string numérica em um número inteiro, permitindo operações matemáticas e comparações.
* **`.strip()`**: Método de string que remove espaços em branco inúteis localizados estritamente no início e no final do texto.
* **`.split()`**: Divide uma string em partes menores (uma lista de palavras) com base em um delimitador (por padrão, espaços em branco).
* **`.capitalize()`**: Altera o primeiro caractere de uma string para maiúsculo e força todos os demais a se tornarem minúsculos.
* **`' '.join()`**: Agrupa uma lista de palavras isoladas de volta em uma única string, inserindo um caractere de espaço entre elas.

### 🛠️ Prompts Reutilizáveis para Revisões Futuras
Copie e cole estes prompts no seu assistente de IA para fixar conteúdos avançados:
1.  *"Atue como um Engenheiro de Dados Sênior. Explique como a lógica de strings em Python que aprendi hoje se conecta com a construção de uma pipeline de limpeza de dados em larga escala utilizando a biblioteca Pandas."*
2.  *"Crie um simulado com 3 questões de múltipla escolha focadas em erros de indentação e escopo de variáveis dentro de funções em Python."*
