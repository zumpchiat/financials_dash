
# 📊 Modelagem Dimensional (Star Schema) - finacials_dashboard

Este projeto consiste na aplicação dos conceitos de Modelagem Dimensional, especificamente o *Star Schema* , utilizando a base de dados **Financial Sample** no **Microsoft Power BI**. O objetivo foi transformar uma tabela única em um modelo otimizado, separando dados de fato e dimensão para melhorar a performance e a usabilidade em análises e relatórios.

### Screenshots

<img width="895" height="499" alt="image" src="https://github.com/user-attachments/assets/f9d572d4-3de2-4bbf-a6c7-5401374a1ba3" />


## 🎯 Objetivo do Projeto

Transformar a tabela de vendas única (`Financial Sample`) em um modelo de dados em formato *Star Schema*, criando tabelas de **Fato** e **Dimensão** para organizar as informações de maneira eficiente para análises de BI.

## 🛠️ Tecnologias e Ferramentas

  * **Microsoft Power BI Desktop:** Utilizado para ETL (via Power Query), Modelagem de Dados e escrita de funções DAX.
  * **Power Query (M Language):** Utilizado para a transformação dos dados, duplicação e filtragem das tabelas.
  * **DAX (Data Analysis Expressions):** Utilizado para a criação de medidas e da tabela calendário.
  * **GitHub:** Repositório para versionamento e documentação do projeto.

## 🧱 Processo de Construção do Diagrama (Star Schema)

A construção do modelo dimensional seguiu os seguintes passos dentro do **Power BI Desktop**, majoritariamente no **Editor do Power Query**


### 🖼️ Diagrama Star Schema

<img width="716" height="497" alt="image" src="https://github.com/user-attachments/assets/cc15a7bf-fe15-4640-b412-c18def100376" />

> **Figura 1:** Diagrama do Star Schema implementado no Power BI.




## 🚀 Como Utilizar o Projeto

1.  **Clone o Repositório:**
    ```bash
    git clone https://github.com/zumpchiat/financials_dash.git
    ```
2.  **Abra o Projeto:**
      * Abra o arquivo **`Dax_financials.pbix`** incluído neste repositório no Power BI Desktop.
3.  **Explorar o Modelo:**
      * Visualize o `Star Schema` na aba **Modelo** do Power BI.
      * Analise as transformações realizadas no **Editor do Power Query**.

-----

