# Patient Financial Navigator

> **AI-powered financial assistance tool** that helps patients understand medical bills, discover financial aid programmes, and navigate insurance options.

---

## Tech Stack

| Layer       | Technology                  |
| ----------- | --------------------------- |
| Framework   | Next.js 16 (App Router)     |
| Language    | TypeScript                  |
| Styling     | Tailwind CSS 4              |
| Linting     | ESLint 9                    |
| Runtime     | Node.js ≥ 22                |

## Getting Started

### Prerequisites

- **Node.js** ≥ 22 and **npm** ≥ 10

### Installation

```bash
# Clone the repository
git clone https://github.com/<your-org>/patient-financial-navigator.git
cd patient-financial-navigator

# Install dependencies
npm install
```

### Running Locally

```bash
# Start the development server (http://localhost:3000)
npm run dev
```

### Available Scripts

| Command           | Purpose                              |
| ----------------- | ------------------------------------ |
| `npm run dev`     | Start the development server         |
| `npm run build`   | Create an optimised production build |
| `npm run start`   | Serve the production build           |
| `npm run lint`    | Run ESLint checks                    |

## Project Structure

```
patient-financial-navigator/
├── src/
│   └── app/            # Next.js App Router pages & layouts
├── public/             # Static assets
├── eslint.config.mjs   # ESLint configuration
├── next.config.ts      # Next.js configuration
├── tailwind.config.ts  # Tailwind CSS configuration (if customised)
├── tsconfig.json       # TypeScript configuration
└── package.json
```

## Team

This project is being built by a 4-person team during a 10-day hackathon sprint.

## Data Privacy

⚠️ **This application will handle sensitive patient financial data.**

- **Never** commit real patient documents, medical bills, or personally identifiable information (PII).
- All `.pdf`, `.docx`, `.xlsx`, and `.csv` files are excluded via `.gitignore`.
- Environment files (`.env*`) containing secrets are excluded from version control.

## Licence

This project is private and not currently licensed for public distribution.
