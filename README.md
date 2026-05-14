# UK-HAM-STATION-COMMANDER
UK HAM STATION COMMANDER Antenna &amp; Transformer Lab builder
hi i have made this so pepole can use it on SOTA/POTA/BOTA.


# 📡 UK Ham Station Commander v0.1

A lightweight, single-file web dashboard designed for UK-based Amateur Radio operators. This tool provides real-time antenna calculations, operating references, and a simple ADIF-compatible logbook.

## ✨ Features

- **Antenna & Transformer Lab**: 
  - Calculate lengths for 1/2λ Dipoles, EFHW, Delta Loops, and 1/4λ Verticals.
  - Transformer winding calculator (Secondary turns based on impedance ratio).
  - Real-time visual representation of antenna geometry.
- **Operating References**:
  - Essential Q-Codes and Morse references.
  - UK Regional Identifier guide (2nd letter of callsigns).
  - NATO Phonetic Alphabet quick-ref.
- **Station Logbook**:
  - Log contacts with Call, RST, Band, and Mode.
  - Automatic UTC timestamping.
  - **ADIF Export**: Download your logs in `.adi` format for easy import into QRZ, LoTW, or eQSL.
- **Compliance & Safety**:
  - UK Band Plan reference (Ofcom FAT) showing access levels (Foundation/Intermediate/Full).
  - RF Safety Distance calculator based on power input (ERP estimation).
  - Ofcom power limit reminders.

## 🚀 Getting Started

1. Save the code as an `.html` file (e.g., `ham-commander.html`).
2. Open the file in any modern web browser (Chrome, Firefox, Edge, Safari).
3. No internet connection is required after the initial load, making it ideal for field days or "SOTA/POTA" activations.

## 🛠️ Technical Details

- **Technology Stack**: HTML5, CSS3 (CSS Grid & Variables), Vanilla JavaScript.
- **Storage**: Uses `localStorage` to save your logbook entries locally in your browser. Clearing your browser cache may delete your logs, so export to ADIF regularly!
- **Formulas Used**:
  - Wire Length: Standard metric wire formulas ($142.5 / f$ for dipoles).
  - Safety Distance: $0.13 \times \sqrt{P \times G}$.

## 📋 License

This project is open-source. Feel free to modify it for your own station needs.

---
*73 de M7JTV*
