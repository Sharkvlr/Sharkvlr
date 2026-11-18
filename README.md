<div align="center">

# Hi, I'm Gabriel 👋

### Full-stack developer who builds production software for real businesses: from the problem to the code to the deploy.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-connect-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gabriel-adley-fernandes-971392264/)
[![Portfolio](https://img.shields.io/badge/Portfolio-visit-F97316)](https://sharkvlr.github.io)
[![Email](https://img.shields.io/badge/Email-reach%20me-EA4335?logo=gmail&logoColor=white)](mailto:gabrieladley45@gmail.com)
![Location](https://img.shields.io/badge/São%20Luís-Brazil%20(BRT)-3FCF8E)

</div>

I work at an HVAC engineering group in São Luís, Brazil. When the operation hit walls that software could fix, I **built the software myself** and kept it running in production. Today that is **four systems used every day by the whole company**, including a full ERP that runs finance, HR, sales, field service, inventory and projects.

- 🏗️ **Flagship:** a company-wide ERP: 15+ modules, 4,300+ commits, 900+ database migrations, ~9,000 automated tests.
- 🔭 **Currently building:** maintenance contracts with QR-code service requests, construction scheduling, and quoting engines for HVAC projects.
- 💡 **How I work:** I don't wait for a spec. I live the business problem, model the data, ship the feature and support the people using it.
- 🌐 **Open to:** full-stack roles (remote-friendly) and freelance projects. PT-BR / EN.

---

## 🚀 Featured projects

> These systems run inside a private company, so their source code is private. Each one has a **full case study with screenshots** (fictitious sample data) on my portfolio: **[sharkvlr.github.io](https://sharkvlr.github.io)**.

### 🏢 Alphatherm ERP: company-wide ERP in production · [case study](https://sharkvlr.github.io/erp/)

<img src="https://sharkvlr.github.io/assets/shots/erp-home.webp" alt="ERP home screen with sample data" width="100%">

`React 19` `TypeScript` `PostgreSQL` `Supabase` `Deno Edge Functions` `Vite` `Vitest`

One system that replaced spreadsheets and disconnected tools across a group of three companies.

- **15+ business modules:** finance and billing, tax and accounting, HR and payroll, sales CRM and quoting, field service, projects and construction, inventory and purchasing, maintenance contracts, meetings, fleet and an executive cockpit.
- **Database-first security:** ~575 tables and 1,600+ SQL functions, with Row-Level Security on every table, role-based plus per-user module permissions, and an event trigger that applies access policies to every new table automatically.
- **80+ serverless functions and 90 scheduled jobs** integrating a cloud accounting platform (OAuth), Brazilian e-invoicing (NFS-e), bank statements, a time-clock API, cloud storage, email (SMTP/IMAP), WhatsApp and Web Push.
- **Finance engines:** bank reconciliation, a payment audit across multiple banks' statements with matching and duplicate detection, and accounts payable alarms.
- **Payroll engine** with current Brazilian tax tables: vacations, severance, overtime, 13th salary and cost per employee.
- **Document AI:** OCR plus LLM pipelines read invoices, bank statements, credit-card bills and receipts. Voice input fills forms, and LLM agents use tools under spend limits.
- **Operations:** Gantt with baseline and S-curve, a staffing capacity planner, HVAC quoting engines, and an inventory with weighted average cost and NF-e XML receipt.
- **Quality:** ~9,000 automated tests, including 270+ database tests that run real migrations in an in-process Postgres (PGlite) to verify access rules; a pre-push build gate; realtime updates across modules.

### 📱 Alphatherm Atendimento: offline-first field-service PWA · [case study](https://sharkvlr.github.io/atendimento/)
`React` `TypeScript` `Supabase` `PostgreSQL` `PWA`

Mobile app for technicians and back office that replaced a forms + 3,700-row spreadsheet + Word workflow. Later merged into the ERP as its field-service module.

- Offline-first: an outbox and sync queue, form drafts and cache warming for technicians without signal.
- Service orders with check-in, equipment, photos, client signature and PDF reports; proposals sent by email.
- Role-based dashboards enforced in the database with RLS; push notifications; integration with the accounting platform.

### 🤖 Alphaneo: RPA bot that closes work orders · [case study](https://sharkvlr.github.io/alphaneo/)
`Python` `Selenium` `pywebview / WebView2` `PyInstaller` `Inno Setup`

Windows desktop robot that bulk-closes preventive, corrective and patrol work orders in a third-party web CMMS. Used daily by the operations team. **v1.0.12**.

- 14k-line Python codebase; the bot runs in a separate worker process so the UI never freezes.
- UI migrated from Tkinter to a GPU-rendered WebView2 front end (60 fps).
- Self-updates through the GitHub Releases API; scripted build → installer → release pipeline.

### ⚙️ Alphatasker: RPA bot for bulk work-order creation · [case study](https://sharkvlr.github.io/alphatasker/)
`Python` `Selenium` `pywebview / WebView2` `PyInstaller` `Inno Setup`

Fills a spreadsheet-style grid and creates dozens of work orders in one run, with scheduling rules per order type. **v0.3.8**.

- Autocomplete over 500+ sectors; live monitor with pause, restart and stop.
- Custom browser-driver resolver that downloads the driver matching the installed browser and caches it.
- Credentials encrypted locally; same auto-update and release pipeline as Alphaneo.

---

## 🛠️ Tech I build with

![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?logo=postgresql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?logo=supabase&logoColor=white)
![Deno](https://img.shields.io/badge/Deno-000000?logo=deno&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?logo=vitest&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?logo=selenium&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?logo=vercel&logoColor=white)

---

<div align="center">

![Gabriel's GitHub stats](https://github-readme-stats.vercel.app/api?username=Sharkvlr&show_icons=true&hide_border=true&theme=tokyonight)

</div>
