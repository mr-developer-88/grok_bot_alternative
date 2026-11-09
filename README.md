# Grok Bot Alternative

A modern, high-performance AI Chatbot Application inspired by Grok. Built with Next.js App Router, Tailwind CSS, Shadcn UI, and type-safe database integrations.

---

## 🛠️ Tech Stack

- **Framework:** [Next.js](https://nextjs.org/) (App Router & React 19)
- **Styling:** [Tailwind CSS](https://tailwindcss.com/) & [Shadcn UI](https://ui.shadcn.com/)
- **Database & ORM:** PostgreSQL with [Drizzle ORM](https://orm.drizzle.team/)
- **Authentication:** [NextAuth.js / Auth.js](https://authjs.dev/)
- **Email Delivery:** [Resend API](https://resend.com/)
- **Background Workflows:** [Inngest](https://www.inngest.com/)

---

## 🚀 Getting Started

Follow these steps to get the development environment running locally.

### Prerequisites

Ensure you have the following installed on your machine:
- Node.js (v18.x or higher)
- npm or pnpm / yarn

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/mr-developer-88/grok_bot_alternative.git
   cd grok_bot_alternative
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Configure Environment Variables:**
   Create a `.env.local` file in the root directory and add your required keys:
   ```env
   DATABASE_URL=postgresql://your_db_connection_string
   NEXTAUTH_SECRET=your_nextauth_secret
   RESEND_API_KEY=your_resend_api_key
   ```

4. **Run the development server:**
   ```bash
   npm run dev
   ```

5. **Access the app:**
   Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 💻 Development Workflow (Multi-Device Sync)

When working across multiple machines (e.g., PC and Laptop):

- **Before starting work:**
  ```bash
  git pull origin main
  ```
- **After committing changes:**
  ```bash
  git add .
  git commit -m "Update feature description"
  git push origin main
  ```
