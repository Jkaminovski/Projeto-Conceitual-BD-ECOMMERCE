# 📊 Projeto Conceitual de Banco de Dados - ECOMMERCE

**Desafio:** Refinando um Projeto Conceitual de Banco de Dados – ECOMMERCE  
**Bootcamp:** [Suzano - Análise de Dados com Power BI](https://web.dio.me/track/coding-future-suzano-analise-dados)  
**Plataforma:** [DIO](https://www.dio.me/)  

### 📚 Descrição do Desafio
_"Modelamos juntos um contexto reduzido de e-commerce. Agora é a sua vez! Escolha a ferramenta de modelagem e refine o projeto. Lembre-se de que se optar por ferramentas como **MySQL Workbench** ou **DBDesigner**, deverá especificar corretamente as **PK (Primary Keys)** e **FK (Foreign Keys)**. Apesar de não utilizarmos essas chaves na modelagem conceitual, é importante compreendê-las. O objetivo é criar um modelo conceitual para o cenário de **E-commerce**."_  

**Instrutora:** Juliana Mascarenhas

---

### 🎯 Objetivo do Desafio
Refine o modelo conceitual, adicionando os seguintes pontos:

- **Cliente PJ e PF:** Uma conta pode ser **Pessoa Jurídica (PJ)** ou **Pessoa Física (PF)**, mas não pode ter ambas as informações simultaneamente.
- **Pagamento:** Permitir o cadastro de **múltiplas formas de pagamento**.
- **Entrega:** A entidade de entrega deve incluir **status** e **código de rastreio**.

---

### 🛠️ Ferramentas Utilizadas

- **[MySQL Workbench](https://www.mysql.com/products/workbench/)**

---

### 📑 Respostas ao Desafio

- **Cliente:** Foram criadas duas novas entidades:  
  - `PJ_Pessoa Jurídica` (CNPJ)  
  - `PF_Pessoa Física` (CPF)  
  Isso garante que uma conta seja exclusivamente **PJ** ou **PF**, mas não ambas.

- **Pagamento:** A entidade **Pagamento** foi detalhada em duas subentidades para armazenar as diferentes formas de pagamento:  
  - **Cartão**  
  - **Boleto**

- **Entrega:** Foi criada a entidade **Entrega** para registrar as informações de envio de cada pedido, como:
  - **Data do pedido**  
  - **Data de envio**  
  - **Data de entrega**  
  - **Status**  
  - **Código de rastreio**

![Diagrama do Projeto](https://github.com/Jkaminovski/Projeto-Conceitual-BD-ECOMMERCE/raw/e21c4aa6f9df8364b0f781f8702756c78595913a/caminho/para/a/imagem.png)

---

### 📊 Anexos
Inclui diagramas de **Ordem de Serviço** e **Universidade**, desenvolvidos no **MySQL Workbench**, como complementos do desafio.
