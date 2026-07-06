# Job Cost Estimator

A single-file web app for putting together quick job cost estimates — line up
materials, labour, and other costs, apply markup, contingency, and tax, and get
a quote total.

## Use it

Open `index.html` in any browser. No install, no build step, no dependencies.

## Features

- **Line items** with description, type (materials / labour / other), quantity,
  and unit cost — line totals calculate as you type.
- **Separate markup** percentages for materials and labour.
- **Contingency and tax/GST** applied on top.
- **Autosave** — the estimate persists in your browser's local storage.
- **Export to CSV** for spreadsheets, or **print / save as PDF** with a clean
  print layout.
- Light and dark mode follow your system theme.

## Notes

Data is stored only in your own browser (`localStorage`); nothing is sent
anywhere. Use "Clear all" to start a fresh estimate.
