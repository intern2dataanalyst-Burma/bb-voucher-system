# Burma Burma Voucher System

The centralized voucher processing system.

## Live Dashboards
* [Employee Dashboard](https://intern2dataanalyst-burma.github.io/bb-voucher-system/employee.html) - Submit and track your vouchers.
* [Approver Dashboard](https://intern2dataanalyst-burma.github.io/bb-voucher-system/approver.html) - Approve or reject pending requests.
* [Accounts Dashboard](https://intern2dataanalyst-burma.github.io/bb-voucher-system/accounts.html) - Final processing and PDF generation.

## Troubleshooting
* **"Loading..." stuck forever:** Ensure the Google Apps Script Web App is deployed with "Anyone" access.
* **404 Error:** Ensure you are accessing the specific file (e.g., `/employee.html`) and not just the root folder.
* **Update Config:** If you update the Google Apps Script Web App URL, make sure to update the `WEB_APP_URL` constant in the `<script>` tag of each HTML file and commit the changes to GitHub.
