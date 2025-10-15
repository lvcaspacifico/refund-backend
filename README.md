# 💸 Refound 2.0 (Backend)

Projeto de estudo backend utilizando **Node.js**, **TypeScript** e **Express**, com **Prisma** para ORM.

Refund é uma plataforma de gerenciamento de reembolso de despesas de funcionários, idealmente despesas relacionadas a transporte, alimentação e serviços.

Qualquer usuário tem acesso a login, cadastro e página de não encontrado.

Os usuários do tipo "empregado" terão acesso a telas de upload de solicitação e status.

Os usuários do tipo "gerente" terão acesso a telas de aprovação da solicitação e listagem de solicitações.

## Tecnologias

<div align="center">

![TypeScript](https://img.shields.io/badge/typescript-%23323330.svg?style=for-the-badge&logo=typescript&logoColor=FFFFFF&color=2F74C0)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB) 

![Prisma](https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white)
![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)
![Zod](https://img.shields.io/badge/zod-%233068b7.svg?style=for-the-badge&logo=zod&logoColor=white) 

</div>

- Node.js 20+
- TypeScript 5
- Express 4
- Prisma 6
- SQLite como banco de dados
- bcrypt para hash de senhas
- jsonwebtoken para autenticação JWT
- multer para upload de arquivos
- zod para validação de dados
- cors para controle de acesso

## Scripts

- `npm run dev` - Executa o servidor em modo de desenvolvimento com watch via TSX

## Instalação

1. Clone o repositório:

```bash
git clone <URL_DO_REPOSITORIO>
````

2. Instale as dependências:

```bash
npm install
```

3. Configure o banco de dados no arquivo `.env` e rode as migrations do Prisma:

```bash
npx prisma migrate dev
```

4. Inicie o servidor:

```bash
npm run dev
```

---

Projeto parte da formação [Rocketseat Fullstack](https://www.rocketseat.com.br/formacao/fullstack) 🚀

Made with ☕ by [@lvcaspacifico](https://github.com/lvcaspacifico) 👋