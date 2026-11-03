# Costco Receipt Dashboard

A self-contained, offline dashboard for exploring JSON receipts from the [Costco Receipt Downloader](../Downloader/).

## Get started

1. Download the repository and open `Dashboard.html` in your browser.
2. Choose **Data → Load / Add JSON** and select a downloader export. You can import additional files to merge receipts.
3. Browse **Overview**, **Receipts**, and **Items**. Click an item on a receipt to see its purchase history or rename it.

Search receipts and notes, save individual receipts, add notes, rename members and products, filter purchases and returns, and print a receipt or save it as a PDF through your browser. Receipt layouts are reconstructed from available data.

## Saving your data

The dashboard stores its archive and settings in browser storage. Use **Data → Save app data** to create a portable JSON backup including receipts, notes, saved receipts, names, and preferences. Keep a separate backup: clearing browser data can remove the local archive.

Browsers that support direct file access can update a selected app-data file after changes, subject to file permissions. In other browsers, Save app data downloads a snapshot; export it again after changes. Import an app-data file using **Load / Add JSON**.

The dashboard runs locally without external scripts, fonts, or network access. The downloader is a separate tool and requires an internet connection.
