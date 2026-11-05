Deploy this folder as a static site on Vercel.

Option 1 — GitHub:
1. Create a new GitHub repository.
2. Upload index.html and DBMS_OP_PLSQL_4.pdf (README is optional).
3. In Vercel, choose Add New > Project and import that repository.
4. Framework Preset: Other. Build Command: leave empty. Output Directory: ./
5. Deploy. Your PDF will be available at /DBMS_OP_PLSQL_4.pdf.

Option 2 — Vercel CLI:
Install Node.js, then run: npm i -g vercel
Open a terminal in this folder and run: vercel
Follow the prompts, then run: vercel --prod
