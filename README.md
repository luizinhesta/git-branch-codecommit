# 🚀 Projeto AWS CodeCommit + Git Branch + Pipeline para S3

![HTTP Status Code](imagem/imagem(1).jpg)

Este projeto demonstra na prática a utilização de **Git com AWS
CodeCommit**, utilizando **branches para desenvolvimento de
funcionalidades** e **integração com AWS CodePipeline** para realizar o
deploy automático de um **site estático hospedado no Amazon S3**.

O objetivo do projeto é mostrar um fluxo comum utilizado em ambientes de
desenvolvimento, onde novas funcionalidades são desenvolvidas em
**branches separadas** e depois integradas à **branch principal
(master)**.

------------------------------------------------------------------------

# 🏗️ Infraestrutura

![HTTP Status Code](imagem/imagem(2).png)

A arquitetura do projeto utiliza os seguintes serviços da AWS:

-   **AWS CodeCommit**\
    Repositório Git utilizado para armazenar e versionar o código.

-   **Git Branch**\
    Utilização de branches para desenvolvimento separado de
    funcionalidades.

-   **AWS CodePipeline**\
    Pipeline responsável por automatizar o processo de deploy.

-   **Amazon S3**\
    Hospedagem do site estático publicado automaticamente pelo pipeline.

Fluxo de funcionamento:

    Git (Local)
          ↓
    AWS CodeCommit (Repositorio)
          ↓
    AWS CodePipeline (Automação)
          ↓
    Amazon S3 (Site público)

------------------------------------------------------------------------

# 🌿 Fluxo de Branches

Durante o projeto foram utilizadas diferentes branches para organizar o
desenvolvimento:

-   **master**
    -   Branch principal utilizada para produção
    -   Dispara o pipeline para publicação no S3
-   **projetos**
    -   Branch utilizada para adicionar a seção de projetos no site
-   **contatos**
    -   Branch utilizada para adicionar a seção de contatos

Fluxo de trabalho:

    master
       │
       ├── projetos
       │       └── merge → master
       │
       └── contatos
               └── merge → master

------------------------------------------------------------------------

## 🖼️ Galeria de Imagens do Projeto

> Nesta seção estão algumas imagens do projeto mostrando o funcionamento
> da infraestrutura e das implementações realizadas.

  ---------------------------- -------------------------------- ----------------------------
  ![](imagem/imagem(3).png)   ![](imagem/imagem(4).png)       ![](imagem/imagem(5).png)

  ![](imagem/imagem(6).png)   ![](imagem/imagem(7).png)       ![](imagem/imagem(8).png)

  ![](imagem/imagem(9).png)   ![](imagem/imagem(10).png)       
  ---------------------------- -------------------------------- ----------------------------

------------------------------------------------------------------------

# ⚙️ Tecnologias Utilizadas

-   AWS CodeCommit
-   AWS CodePipeline
-   Amazon S3
-   Git
-   HTML
-   CSS

------------------------------------------------------------------------

# 🌐 Minhas redes

-   📺 **YouTube:**\
    https://youtu.be/M89Zw_ljDKE?si=IBPC4sf3BRR7IrMk

-   💼 **LinkedIn:**\
    https://www.linkedin.com/in/luiz-inhesta-341b4b311/

------------------------------------------------------------------------

# 👨‍💻 Autor

**Luiz Augusto**

Infrastructure • Cloud • Monitoring 🚀
