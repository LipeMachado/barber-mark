# Barber Appointment

## Português (PT-BR)

Este é um projeto de **Agendamento de Barbearia** desenvolvido com [Next.js](https://nextjs.org), [Prisma ORM](https://www.prisma.io/) e PostgreSQL. Permite que usuários agendem horários em barbearias, gerenciem serviços e contas.

### Funcionalidades

- Cadastro e autenticação de usuários
- Gerenciamento de barbearias (nome, endereço, telefones, descrição, imagem)
- Gerenciamento de serviços (nome, descrição, preço, imagem)
- Agendamento de horários com data e hora
- Interface responsiva com [Tailwind CSS](https://tailwindcss.com/)
- Backend type-safe com Prisma

### Primeiros Passos

1. **Instale as dependências:**
   ```sh
   npm install
   # ou
   yarn
   # ou
   bun install
   ```

2. **Configure seu banco de dados:**
   - Defina o `DATABASE_URL` no arquivo `.env`.

3. **Rode as migrações:**
   ```sh
   npx prisma migrate dev
   ```

4. **Inicie o servidor de desenvolvimento:**
   ```sh
   npm run dev
   ```

5. Acesse [http://localhost:3000](http://localhost:3000) no seu navegador.

### Scripts

- `dev` – Inicia o servidor de desenvolvimento
- `build` – Gera build para produção
- `start` – Inicia o servidor em produção
- `lint` – Executa o ESLint

---

## English

This is a **Barber Appointment** project built with [Next.js](https://nextjs.org), [Prisma ORM](https://www.prisma.io/), and PostgreSQL. It allows users to book appointments at barbershops, manage barbershop services, and handle user accounts.

### Features

- User registration and authentication
- Barbershop management (name, address, phones, description, image)
- Service management (name, description, price, image)
- Booking appointments with date and time
- Responsive UI with [Tailwind CSS](https://tailwindcss.com/)
- Type-safe backend with Prisma

### Getting Started

1. **Install dependencies:**
   ```sh
   npm install
   # or
   yarn
   # or
   bun install
   ```

2. **Configure your database:**
   - Set your `DATABASE_URL` in `.env`.

3. **Run migrations:**
   ```sh
   npx prisma migrate dev
   ```

4. **Start the development server:**
   ```sh
   npm run dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser.

### Scripts

- `dev` – Start development server
- `build` – Build for production
- `start` – Start production server
- `lint` – Run ESLint