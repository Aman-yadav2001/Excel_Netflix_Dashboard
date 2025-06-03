# 📊 Netflix Originals Analysis Dashboard

## 📋 Overview
This repository contains an Excel-based dashboard analyzing Netflix original content using the `NetflixOriginals.xlsx` dataset. The dashboard provides insights into Netflix originals, including runtime, IMDB scores, genres, premiere dates, and languages. It uses Excel features like PivotTables, charts, and slicers to explore trends such as average IMDB scores by genre, runtime distributions, and content diversity across languages.

## 📂 Files in This Repository
- `NetflixOriginals.xlsx`: The Excel file containing the dataset and dashboard with PivotTables, charts, and slicers.
- `.gitignore`: Excludes temporary Excel files and local settings from version control.
- `README.md`: This file, providing project documentation.

## 📈 Dataset Description
The `NetflixOriginals.xlsx` dataset includes 584 Netflix original titles with the following key fields:
- **Title**: Name of the Netflix original (e.g., "13th: A Conversation with Oprah Winfrey & Ava DuVernay").
- **Genre**: Categories like Documentary, Comedy, Thriller, etc.
- **Premiere**: Release date (month, day, year).
- **Runtime**: Duration in minutes (e.g., 4 to 209 minutes).
- **IMDB Score**: Ratings from 2.5 to 9.0.
- **Language**: Primary language(s) of the content (e.g., English, Hindi, Spanish).
- **Additional Fields**: Aggregated metrics like average runtime and IMDB scores by genre, year, and language.

## 🎨 Dashboard Features
The Excel dashboard includes:
- **PivotTable**: Summarizes average IMDB scores by genre (e.g., Documentary: ~7.4, Comedy: ~5.6) and language.
- **Bar Chart**: Visualizes average IMDB scores by genre.
- **Line Chart**: Shows the number of releases by year and month (e.g., peak releases in 2020).
- **Pie Chart**: Displays distribution of titles by language (e.g., English: 407 titles).
- **Histogram**: Illustrates runtime distribution (e.g., most titles range from 80–120 minutes).
- **Slicers**: Allows filtering by genre, year, or language for interactive analysis.
- **Table**: Detailed view of titles, genres, runtimes, and IMDB scores.

## 🛠️ Prerequisites
To use this Excel dashboard, ensure you have:
- **Microsoft Excel**: Version 2016 or later (Microsoft 365 recommended) to support PivotTables, charts, and slicers. Download from [Microsoft Office](https://www.microsoft.com/en-us/microsoft-365/excel).
- **Git**: Required for version control. Download from [Git](https://git-scm.com/downloads).
- **Visual Studio Code (VS Code)** (optional): For managing Git. Download from [VS Code](https://code.visualstudio.com/).

## ⚙️ Setup Instructions
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Aman-yadav2001/Excel_Netflix_Dashboard.git
   ```
   Use GitHub Desktop or VS Code for a simpler cloning process if preferred.

2. **Open the Excel File**:
   - Open `NetflixOriginals.xlsx` in Microsoft Excel.
   - Ensure macros are enabled if the dashboard includes VBA scripts (not required for standard PivotTables and charts).

3. **Verify Data**:
   - The dashboard uses data within `NetflixOriginals.xlsx`. No external data sources are required.
   - If you modify the dataset, refresh PivotTables and charts (Data > Refresh All) to update visuals.

## 🚀 Usage
- **Exploring the Dashboard**:
  - Open `NetflixOriginals.xlsx` and navigate to the dashboard sheet (e.g., "Dashboard" or similarly named).
  - Use slicers to filter data by genre, year, or language.
  - Interact with charts to explore trends (e.g., hover over bars to view IMDB scores).
  - Review PivotTables for summarized metrics like average runtime or IMDB scores.

- **Editing the Dashboard**:
  - Modify PivotTables or charts via Excel’s PivotTable Fields or Chart Design tools.
  - Add new data to the dataset sheet and refresh PivotTables (Data > Refresh All) to update the dashboard.
  - Customize slicers or add new visuals using Excel’s Insert > Charts or Insert > Slicer options.

- **Sharing the Dashboard**:
  - Save the Excel file and share it via email, cloud storage, or GitHub.
  - For static sharing, export the dashboard as a PDF (File > Save As > PDF).

## 🔄 Version Control
This project uses Git for version control:
- **Committing Changes**:
  - Commit updates to `NetflixOriginals.xlsx` using `git add NetflixOriginals.xlsx` and `git commit -m "Your message"`.
  - The `.gitignore` file excludes temporary Excel files (e.g., `~$*.xlsx`).

- **Collaboration**:
  - Create branches for new features or edits (`git checkout -b feature-branch`).
  - Submit pull requests to merge changes into the main branch.
  - Note: Excel files can cause merge conflicts. Coordinate with collaborators to avoid simultaneous edits.

## 🤝 Contributing
1. Fork this repository.
2. Create a branch for your changes.
3. Edit `NetflixOriginals.xlsx` (e.g., add new data, visuals, or sheets).
4. Submit a pull request with a clear description of your changes.
5. Follow the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).

## 📬 Contact
For questions or feedback, contact [Your Name/Email] or open an issue in this repository.
