# Projetofullexemplo

### Autenticação JWT


## Passos para a Execução
- 1 Clonar este repositório
- 2 Abrir com o VS code
- 3 Na pasta ./api criar um arquivo **.env** contendo: 
```js
DATABASE_URL="mysql://root@localhost:3306/oss?schema=public&timezone=UTC"
```
- 4 Abrir XAMPP  e clicar em Start nos serviços **Mysql** e **Apache**.
- 5 Instalar as dependências e o banco de dados
```bash
cd api 
npm i
npx prisma migrate dev --name init
```
- 6 Voltar ao VsCode e Exercutar a API
```bash
npx nodemon
```
- Acessar a pasta ./front
- Exercutar o arquivos **index.html** com **live server**
