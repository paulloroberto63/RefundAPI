# 💰 API de Reembolso de Despesas

> Sistema para controle e solicitação de reembolsos corporativos de forma segura, simples e eficiente.

---

## 🚀 Tecnologias Utilizadas

⚙️ **Back-end**  
- 🟢 Node.js  
- 🔷 TypeScript  
- ⚡ Express  

🗄️ **Banco de Dados**  
- 🟣 Prisma ORM  
- 📦 SQLite  

🔐 **Segurança & Validação**  
- 🔑 Bcrypt  
- ✅ Zod  

🎨 **Front-end (quando aplicável)**  
- 🌈 TailwindCSS  
- 📄 HTML / CSS / JavaScript  

---

## 📁 Estrutura do Projeto

📦 api-reembolso
┣ 📂 prisma
┣ 📂 src
┣ 📄 package.json
┣ 📄 tsconfig.json
┣ 📄 README.md

---
 ## 📦 Instale as dependências
npm install

 ## 🛠️ Configure o banco de dados
npx prisma migrate dev

---
## ▶️ Execute o servidor
npm run dev

---
## Rotas da API

🔐 Autenticação

➕ POST /register → Criar conta

🔑 POST /login → Acessar sistema

💵 Reembolso

📤 POST /refund → Criar solicitação

📄 GET /refund → Listar

✏️ PUT /refund/:id → Atualizar status

❌ DELETE /refund/:id → Excluir
