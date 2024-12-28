# Sistema de Controle de Ordens de Serviço - Oficina Mecânica

## Descrição
Este repositório contém o modelo conceitual básico de um banco de dados para o gerenciamento de ordens de serviço em uma oficina mecânica, desenvolvido utilizando o MySQL Workbench. O modelo define as entidades, atributos e relacionamentos necessários para representar as informações de clientes, veículos, mecânicos, ordens de serviço, peças e serviços realizados.

## Tecnologias Utilizadas
* **MySQL Workbench:** Ferramenta utilizada para modelar o banco de dados.
* **MySQL:** Sistema gerenciador de banco de dados relacional.

## Estrutura do Projeto
* **oficina.mwb:** Arquivo principal do projeto, contendo o diagrama ER (Entidade-Relacionamento) completo.
* **oficina.png:** O diagrama do Projeto Conceitual modelado.

## Como Utilizar
1. **Importar o modelo:** Abra o arquivo `oficina.mwb` no MySQL Workbench.
2. **Conectar ao banco de dados:** Configure a conexão com o seu banco de dados MySQL.
3. **Gerar script SQL:** Utilize a função de geração de script SQL do Workbench para criar o script de criação das tabelas e índices.
4. **Executar o script:** Execute o script SQL gerado no seu banco de dados MySQL.

## Descrição das Tabelas

* **Cliente:**
    * Armazena os dados cadastrais dos clientes, incluindo nome, identificação, endereço e telefone.
* **Veículo:**
    * Armazena as informações dos veículos dos clientes, como placa, modelo, marca e ano de fabricação.
* **Equipe:**
    * Armazena os dados das equipes de trabalho da oficina.
* **Mecânico:**
    * Armazena as informações sobre os mecânicos, incluindo nome, especialidade e a equipe à qual pertencem.
* **Ordem de Serviço (OS):**
    * Armazena os dados das ordens de serviço, incluindo veículo, cliente, equipe responsável, data de emissão, conclusão, status e valor total.
* **Peça:**
    * Armazena os dados das peças utilizadas nas ordens de serviço, incluindo nome e preço.
* **Serviço:**
    * Armazena os serviços oferecidos pela oficina, incluindo descrição e valor da mão de obra.
* **Servico_OS:**
    * Relaciona os serviços executados em cada ordem de serviço, registrando a quantidade e o valor total de cada serviço.
* **Peca_OS:**
    * Relaciona as peças utilizadas em cada ordem de serviço, registrando a quantidade e o valor total de cada peça.

## Licença
Este projeto está licenciado sob a MIT License.

![oficina](https://github.com/user-attachments/assets/2f511b34-bcda-4100-b973-5533095e6b34)


