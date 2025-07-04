# Auto ChatGPT Content Generator 🧠✍️

A full-stack AI-powered content generation application built with Next.js 13.3, TypeScript, Prisma, TipTap, and the OpenAI API. Users can input prompts and instantly generate structured, editable content using a modern rich-text editor.

---

## 🚀 Features

- ✨ Generate intelligent content from prompts using ChatGPT (OpenAI API)
- 📝 Rich-text editor built with TipTap for smooth editing experience
- 🧠 Server Actions for secure and fast backend logic without API routes
- 💾 Prisma ORM + PostgreSQL for persistent content storage
- 🖥️ Responsive and accessible UI with Tailwind CSS
- ⚡ Edge-optimized rendering and fast load times with App Router

---

## 🛠️ Tech Stack

- **Frontend**: Next.js 13.3 (App Router), React, Tailwind CSS, TipTap
- **Backend**: Server Actions (Next.js), OpenAI API
- **Database**: PostgreSQL with Prisma ORM
- **Language**: TypeScript

---

## 📦 Installation & Setup

> Make sure you have **Node.js**, **npm** (or **yarn**), and **PostgreSQL** installed on your machine.

### 1. Clone the repository

```bash
git clone https://github.com/Anantshukla007/AMblogger.git
cd AMblogger
```

### 2. Install dependencies

```bash
npm install
# or
yarn install
```

### 3. Create a `.env` file and add your environment variables

```env
DATABASE_URL=postgresql://<username>:<password>@localhost:5432/<your-db-name>
OPENAI_API_KEY=your_openai_api_key
```

> Replace the placeholders with your PostgreSQL credentials and OpenAI API key.

### 4. Set up the database

```bash
npx prisma generate
npx prisma migrate dev --name init
```

### 5. Run the development server

```bash
npm run dev
# or
yarn dev
```

Now, open [http://localhost:3000](http://localhost:3000) in your browser to use the app.

---

## 🧪 Development Notes

- TipTap enables rich-text editing with support for Markdown and inline formatting.
- OpenAI’s API powers dynamic content generation based on user input.
- Prisma ORM offers type-safe queries and clean data modeling with PostgreSQL.
- Server Actions streamline backend logic and simplify the full-stack workflow.

---

## 📬 Contributing

Contributions are welcome! Feel free to fork this repo, create a feature branch, and submit a pull request. For bugs or suggestions, please open an issue.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
