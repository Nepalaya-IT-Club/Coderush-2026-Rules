# README Template — Documentation Standards

Every submitted project **must include a `README.md` file** in the root of the repository. The README should be clear enough that a judge unfamiliar with the project can understand it within a few minutes.

Copy the structure below into your own project's `README.md` and fill it in.

---

## Template

```markdown
# [Project Name]

[One-line tagline describing what your project does]

## Team Information

**Team Name:** [Your team name]

**Team Members:**

| Name | Email | GitHub Username |
|---|---|---|
| Full Name | email@example.com | @githubusername |
| Full Name | email@example.com | @githubusername |
| Full Name | email@example.com | @githubusername |

## Project Details

**Project Title:** [Full project name]

**Category:** [ ] FinTech &nbsp; [ ] EdTech &nbsp; [ ] E-Governance &nbsp; [ ] IoT &nbsp; [ ] Open Innovation

**Problem Statement:**
[2–4 sentences describing the real problem your project solves, and why it matters.]

**Solution Overview:**
[A clear paragraph explaining what your project does and how it solves the problem. Mention the main components/modules if there are several.]

## Technical Stack

| Layer | Technology |
|---|---|
| Frontend | e.g., React, Next.js, Tailwind CSS |
| Backend | e.g., Node.js, Express, Django |
| Database | e.g., PostgreSQL, MongoDB, Supabase |
| Other | e.g., APIs, libraries, cloud services used |

## Installation & Setup

### Prerequisites
- [List required software/tools, e.g., Node.js 18+, Python 3.10+]

### Steps

\`\`\`bash
# Clone the repository
git clone https://github.com/Nepalaya-IT-Club/<team-repo-name>.git

# Navigate to the project folder
cd <team-repo-name>

# Install dependencies
npm install

# Start the development server
npm run dev
\`\`\`

The app will be running at `http://localhost:3000` (or relevant port).

### Environment Variables (if applicable)

\`\`\`bash
cp .env.example .env.local
\`\`\`

| Variable | Required | Description |
|---|---|---|
| VARIABLE_NAME | Yes/No | What it's for |

## Demo Credentials (if applicable)

| Role | Access |
|---|---|
| e.g., Admin | Navigate to /admin, no login required for demo |

## Demo Flow

[Step-by-step walkthrough of how a judge should try out your project, e.g.:]

1. Open the app at `/`
2. [Do X]
3. [See Y result]

## Screenshots / Demo

[Add screenshots or a link to a short demo video here.]

## Project Structure

\`\`\`
project-name/
├── app/                  # Main application pages
├── components/           # Reusable UI components
├── lib/                  # Utilities and helper functions
├── public/                # Static assets
├── package.json
└── README.md
\`\`\`

## License

This project was built for **CodeRush 2026**, organized by Nepalaya IT Club.
```

---

## Why This Matters

A clear README helps judges evaluate your project fairly and quickly, even if they can't watch your live demo in detail. Teams with well-organized READMEs consistently score better on presentation and clarity.

---

⬅️ [Back: GitHub Workflow](./GITHUB_WORKFLOW.md) | ➡️ [Next: Submission Checklist](./SUBMISSION_CHECKLIST.md)
