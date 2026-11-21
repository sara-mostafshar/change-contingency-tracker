# Change & Contingency Tracker

**▶ Use it free:** https://sara-mostafshar.github.io/change-contingency-tracker/

A free browser tool for project controllers and project managers. Upload your change log (Excel) and see in seconds:

- How much contingency is used and how much is left – today and after the likely pending changes
- The **burn index**: is contingency being used faster than the project progresses?
- Client change orders: new contract value and margin on changes
- Management reserve and the claimed schedule impact
- Pending changes that have waited too long for a decision
- A plain-English summary for management (copy it or print/save as PDF)

## How to use
1. Open the link and click **Try the sample project**, or download the sample Excel template.
2. Fill in the sheets `Project` (budget, contingency, % complete) and `Changes` (one row per change).
3. Drop the file on the page.

**From your ERP (SAP or others):** export your change or claim list to Excel and paste it into the `Changes` sheet – the template uses common ERP column names (WBS Element, Notification, User Status, Amount, Created On). **From any other source:** fill in the same sheet from a change register or spreadsheet; your own column names (Change ID, Status, Cost Impact…) work too. Take Percent Complete from your schedule, e.g. Primavera P6. The tool supplements your ERP – it does not replace it.

## Good to know
- The burn index limits (amber 1.00×, red 1.25×) are a rule of thumb and can be changed in the template. Early in a project contingency is often used faster than progress.
- "If today's rate continues" is a straight-line warning sign, not a forecast. Compare the remaining contingency with the open risks in your risk register.
- Schedule impact is a simple sum of days, not a critical-path analysis.

🔒 Your file is read in your browser only. The sample project is fictional.

## What's new
**Version 1.0 – 21 Nov 2026**
- First release.

## Use the online version
Please use the online version for the latest tested release: https://sara-mostafshar.github.io/change-contingency-tracker/ – downloaded copies do not receive fixes and updates.

## License
Free to use, share and adapt under the [MIT License](LICENSE). Please keep the credit to Sara Mostafshar.

Built by [Sara Mostafshar](https://sara-mostafshar.github.io) · AI agents and free tools for project controllers and project managers
