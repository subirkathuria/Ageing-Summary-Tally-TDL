# Aging Summary Tally TDL

A Tally Prime / Tally.ERP 9 TDL add-on that adds an **Advanced Aging Analysis** and **Bank Configuration** panel to the bottom of the Ledger Outstanding report.

## Features

- **Automated Aging Analysis**: Automatically categorizes bills into buckets (0-30, 30-60, 60-90, 90-120, 120+ days).
- **Dynamic Ledger Detection**: Automatically detects if the ledger is a Debtor (Dr) or Creditor (Cr) and adjusts labels accordingly.
- **Contra Handling**: Separates "Main" bills (e.g., Invoices) from "Contra" entries (e.g., Advances or Returns) and subtracts them to show a true Net Balance.
- **Multi-Company Bank Config**: displays specific Bank Details (Name, A/c, IFSC) based on which Company is currently active.
- **Visual Alerts**: Highlights overdue bills (60+ days) in Red.

## Setup & Configuration

1. Download the `Aging_Analysis.txt` file.
2. Open the file in a text editor (Notepad, VS Code).
3. **Configure Company Names**: 
   Search for the `[Define Companies]` section and replace `"Your Company Name A"` with your exact Company Name as it appears in Tally.
4. **Configure Bank Details**:
   Update the Bank Name, Account Number, and IFSC codes in the `[Bank Config]` section.
5. Save the file.

## Installation in Tally

1. Open Tally Prime.
2. Go to **F1: Help** > **TDL & Add-On** > **F4: Manage Local TDLs**.
3. Set "Load selected TDL files on startup" to **Yes**.
4. Select the path where you saved `Aging_Analysis.txt`.
5. Accept the screen.

## Usage

Go to **Display > Account Books > Ledger** (or any Ledger Outstanding report). You will see the new analysis box at the bottom of the screen.

## License

MIT License. Free to use and modify.
