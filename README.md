# 🌍 Social Problem Reporter App

A full-stack web application that enables users to report local social issues, view problems, and track resolutions in their community.

---

## 🚀 Tech Stack

| Area         | Tech                                      |
|--------------|-------------------------------------------|
| Framework    | [Next.js (App Router)](https://nextjs.org/) |
| Styling      | [Tailwind CSS](https://tailwindcss.com/) + [ShadCN UI](https://ui.shadcn.com) |
| Database     | [Supabase](https://supabase.com/) (Auth + DB) |
| Icons        | [Lucide Icons](https://lucide.dev/)       |
| Hosting      | [Vercel](https://vercel.com/)             |
| Versioning   | Git + GitHub (PR-based)                   |

---

## 📁 Folder Structure (App Router)

/app
/login → Auth page (Dev 1)
/register → Registration page (Dev 1)
/dashboard → User stats + recent activity (Dev 2)
/report → Report submission form (Dev 3)
/issues → Browse all problems (Dev 4)
/map → Map with location pins (Dev 5)
/profile → User details and history (Dev 6)
/admin → Admin panel for moderation (Dev 7)
/about → About page (Dev 8)
/contact → Contact form (Dev 8)
/components → Shared UI components (Dev 9)
/lib → Utility libraries
/styles → Global styles
/utils → Helper functions
/schemas → Schema validations

yaml
Copy
Edit

---

## 👥 Team & Responsibilities

| Member    | Tasks Assigned                            |
|-----------|--------------------------------------------|
| Dev 1     | `/login`, `/register` (Supabase Auth)      |
| Dev 2     | `/dashboard`                               |
| Dev 3     | `/report`                                  |
| Dev 4     | `/issues`                                  |
| Dev 5     | `/map`                                     |
| Dev 6     | `/profile`                                 |
| Dev 7     | `/admin`                                   |
| Dev 8     | `/about`, `/contact`                       |
| Dev 9     | Shared UI components (navbar, footer, etc) |
| Team Lead | Layout, config, PR reviews, deployment     |

---

## 🛠️ Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/your-username/social-problem-app.git
cd social-problem-app
2. Install dependencies
bash
Copy
Edit
npm install
3. Create environment variables
bash
Copy
Edit
cp .env.example .env
Ask the team lead for Supabase credentials and paste into .env.

4. Run development server
bash
Copy
Edit
npm run dev
🔄 Git Workflow
Create feature branch from dev:

bash
Copy
Edit
git checkout dev
git pull origin dev
git checkout -b yourname/feature-name
After coding:

bash
Copy
Edit
git add .
git commit -m "feat/ab: add report page"
git push origin yourname/feature-name
Create a Pull Request → Base: dev

Request review from another dev

After approval → Merge to dev

✅ No direct commits to main
✅ PR must be reviewed before merging
✅ Use proper commit message format:

Type	Example
feat/	feat/rp: add login page
fix/	fix/aj: resolve dashboard bug
chore/	chore/sk: update dependencies

🧠 Developer Tips
Use Tailwind + ShadCN for all UI

Reuse components across pages

Comment your code for clarity

Communicate blockers early

Keep UI consistent and clean

