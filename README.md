**Descrição do projeto**

- Mimi Pet temo como objetivo facilitar e melhorar o acompanhamento das informações dos animais de estimação, focando no momento nas vacinas, medicamentos, além de possibilitar adoção de animais que precisam de lares, bem como o usuário que utiliza o aplicativo possam colocar para adoção.

**Tecnologias utilizadas**

- Desenvolvimento da API em NodeJS e Typescript para tipagens
- TypeORM para mapeamento do banco de dados
- PostgreSQL e PGAdmin para banco de dados
- Docker para subir contêiner do banco e gerenciador
- React Native para desenvolvimento do aplicativo
- Postman para requisições da API

**Requisitos - App**

- Cadastrar Pet (lista pets)
- Listar vacinas recentes
- Listar todas as vacinas do animal
- Editar dados do pet
- Deletar pet
- Visualizar vacinas
- Visualizar informações sobre pet

**Requisitos - API**

- Buscar aplicações de vacina
- Criar aplicações de vacina
- Cadastrar tutor
- Editar tutor
- Deletar tutor
- Cadastrar animal
- Editar animal
- Deletar animal
- Cadastrar vacina
- Editar vacina
- Deletar vacina
- Adicionar estoque
- Deletar estoque
- Editar estoque
- Adicionar observações sobre as vacinas e medicamento (opcional)

**Requisitos não funcional**

- Ao realizar o POST/PUT na API, deve ser atualizada as vacinas no mesmo momento
- Aplicativo e API devem ter um documentação de fácil entendimento

**Regras de negócios**

- Ao realizar aplicação de uma vacina e dar baixa na API, o estoque dessa vacina deve diminuir
- Antes de aplicar a vacina o sistema deve verificar se existe estoque
- Todas as vacinações devem ser registradas no aplicativo e ser acessadas em um histórico de saúde

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/703650b9-aae5-4be5-bbec-7fd1aab2791e/5430c64d-f3ca-4abe-ad46-83d916e51691/image.png)