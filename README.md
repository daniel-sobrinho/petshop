## Descrição do Projeto
Trabalho avaliativo da disciplina de Desenvolvimento Web II, do curso de Técnico em Informática para Internet do IFCE _Campus_ Tianguá.

Foi desenvolvido um sistema de PetShop com objetivo de por em prática os conhecimentos adquiridos na disciplina.

## Execução do Projeto
Para executar o projeto, será necessário ter em execução uma instância do MySQL, com um banco chamado `petshop` e o Noje.JS v16+.

Faça uma cópia do arquivo `.env.example` que se encontra na raiz do projeto e salve a cópia também na raiz do projeto.

Renomeie a cópia que você criou para `.env`.

No arquivo .env, altere o campo `DB_PASS`de acordo com o que você definiu para o usuário root no momento de instalação do banco MySQL.

Em seguida execute o seguinte comando para instalar das dependências do projeto.

```
npm ci
```

Após executar o comando acima, o node criará uma pasta chamada `node_modules` na raiz do projeto, esta pasta contém as dependências do projeto.

Quando o `npm` finalizar a instalação dos pacotes, execute o comando abaixo para executar a aplicação.

```
npm run start-server
```

Após a execução do comand, o projeto estará executando e você pode acessa-lo através da URL. http://localhost:3000.
