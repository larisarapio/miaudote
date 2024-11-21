# MIAUDOTE 🐈 [em construção 🔨]

> Este projeto foi idealizado a partir da crescente preocupação com a quantidade de gatos abandonados e sem um lar. O objetivo é criar uma plataforma onde administradores possam cadastrar gatos que precisam de um lar, permitindo que potenciais adotantes visualizem as informações dos animais e possam realizar a adoção de forma simples e eficiente. A plataforma visa contribuir para a redução do número de gatos abandonados, promovendo o encontro entre gatos necessitados de cuidados e pessoas dispostas a oferecer um novo lar e carinho.
> 

- Requisitos - o que o sistema deve fazer
    - Funcionais:
        - Cadastro de gatos.
        - Listagem de gatos disponíveis.
        - Atualizar status de adoção.
        - Consultar histórico de adoções.
    - Não funcionais - regras de performance, segurança, e usabilidade
        - O sistema deve funcionar em dispositivos móveis.
        - O back-end deve ser escalável.
- Regra de negócio
    - Somente administradores podem cadastrar ou excluir gatos.
    - Um gato só pode ser listado como "adotado" se tiver um adotante associado.
    - Não é permitido excluir um gato já adotado.
- Casos de uso
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/6d3ff49e-a2f7-47f8-a360-87c251cf58c5/2073b414-fb0f-41d0-97ca-4bdd0c4724e6/image.png)
    
- Diagrama de sequência
    - Exemplo
        - O usuário acessa a lista de gatos.
        - Clica no botão "Adotar".
        - Preenche um formulário de interesse.
        - O administrador recebe a solicitação.
- ROADMAP
    - BACKEND
        - 1a versão
            - [x]  CRUD mockado
            - [x]  ajustar arquitetura
            - [ ]  implementar regra de negócio
        - 2a versão
            - [ ]  implementação banco de dados
            - [ ]  testes
    
    - FRONTEND
        - 1a versão
            - [x]  montar design
            - [ ]  passar pro código
            - [ ]  integração
            - [ ]  QA