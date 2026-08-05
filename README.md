<h1 align="center">📊 Financial Audit Automation using n8n</h1>

<p align="center">
An end-to-end financial auditing workflow built with <b>n8n</b> that automatically processes Excel transaction files received via Gmail, analyzes financial risks, generates professional audit reports, converts them into PDF format, and emails the results back to the sender.
</p>

---

<h2>🚀 Overview</h2>

<p>
This project demonstrates how <b>n8n</b> can be used to automate financial auditing tasks with minimal human intervention.
The workflow accepts an Excel spreadsheet sent via Gmail, extracts transaction data, performs automated audit checks, generates an executive summary, creates a professional HTML report, converts it into PDF using Gotenberg, and sends the audit report back to the requester automatically.
</p>

---

<h2>✨ Features</h2>

<ul>
<li>📥 Automatically monitors Gmail for incoming audit requests</li>
<li>📎 Downloads Excel attachments (.xlsx)</li>
<li>📊 Extracts financial transaction data</li>
<li>🔍 Performs automated financial audit checks</li>
<li>⚠ Detects duplicate invoices</li>
<li>💰 Identifies unusually large transactions</li>
<li>✅ Detects missing approvals</li>
<li>📄 Finds missing supporting attachments</li>
<li>🏢 Flags new vendors</li>
<li>💳 Detects duplicate payments</li>
<li>📅 Identifies invalid transaction dates</li>
<li>📈 Calculates overall risk levels</li>
<li>📝 Generates executive audit summaries</li>
<li>🌐 Creates professional HTML reports</li>
<li>📄 Converts HTML reports into PDF using Gotenberg</li>
<li>📧 Sends the audit report back via Gmail automatically</li>
</ul>

---

<h2>🛠 Technologies Used</h2>

<ul>
<li>n8n</li>
<li>Docker</li>
<li>Gmail API</li>
<li>Google OAuth2</li>
<li>Gotenberg</li>
<li>HTML & CSS</li>
<li>JavaScript</li>
</ul>

---

<h2>📋 Audit Checks</h2>

<ul>
<li>Duplicate Invoice Detection</li>
<li>Large Transaction Detection</li>
<li>Missing Approval Detection</li>
<li>Missing Attachment Detection</li>
<li>New Vendor Detection</li>
<li>Duplicate Payment Detection</li>
<li>Invalid Transaction Date Detection</li>
<li>Risk Classification (Low / Medium / High / Critical)</li>
</ul>

---

<h2>📄 Generated Report</h2>

<p>The generated report contains:</p>

<ul>
<li>Executive Summary</li>
<li>Risk Assessment</li>
<li>Issue Summary</li>
<li>Key Findings</li>
<li>Top Risk Transactions</li>
<li>Recommendations</li>
<li>Professional PDF Output</li>
</ul>

---

<h2>🎯 Workflow</h2>

<pre>
Gmail Trigger
      │
      ▼
Download Attachment
      │
      ▼
Extract Excel Data
      │
      ▼
Financial Audit Engine
      │
      ▼
Generate Executive Summary
      │
      ▼
Generate HTML Report
      │
      ▼
Convert HTML → PDF (Gotenberg)
      │
      ▼
Send Audit Report via Gmail
</pre>

---

<h2>💡 Use Cases</h2>

<ul>
<li>Financial Auditing</li>
<li>Accounting Automation</li>
<li>Internal Control Review</li>
<li>Finance Operations</li>
<li>Workflow Automation</li>
<li>Business Process Automation</li>
</ul>

---

<h2>👨‍💻 Author</h2>

<p>
<b>Nurma Maha Bayu</b><br>
Automation Developer | Workflow Automation | n8n | AI Integration | Financial Process Automation
</p>
