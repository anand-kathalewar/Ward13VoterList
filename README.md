# 🗳️ NMC Voter Search Portal - Ward 13

**नागपूर महानगरपालिका सार्वत्रिक निवडणूक २०२५-२०२६**

A modern, single-page Voter Search Portal for Nagpur Municipal Corporation Elections. Built with React and Tailwind CSS, designed for use at polling booths.

![Made with React](https://img.shields.io/badge/Made%20with-React-61DAFB?style=for-the-badge&logo=react)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-CSS-38B2AC?style=for-the-badge&logo=tailwind-css)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

## 🌟 Features

- ✅ **Zero Backend** - Works entirely in the browser, no server required
- ✅ **Excel/CSV Upload** - Upload voter list via drag & drop or file picker
- ✅ **Instant Fuzzy Search** - Search by Name or EPIC No. with partial matching
- ✅ **High Contrast Cards** - Detail cards optimized for phone photography
- ✅ **Mobile Responsive** - Perfect for tablets and smartphones at polling booths
- ✅ **Bilingual Interface** - Marathi + English support
- ✅ **Privacy First** - All data stays in your browser

## 📸 Screenshots

### Search Interface
- Clean government-official aesthetic with tricolor theme
- Toggle between Name and EPIC No. search modes
- Live results as you type

### Voter Detail Card
- High contrast design for easy photography
- Highlighted Serial Number
- Complete voter information with booth details

## 🚀 Live Demo

Visit: **[https://yourusername.github.io/voter-search-portal](https://yourusername.github.io/voter-search-portal)**

## 📋 Booth Details (Default Configuration)

| Field | Value |
|-------|-------|
| Zone | Dharampeth Zone |
| Ward/प्रभाग | १३/१३ |
| Booth | नूतन भारत विद्यालय |
| Room | १ |
| Address | अभ्यंकरनगर, नागपूर |
| Election Date | १५/०१/२०२६ |

## 🛠️ How to Use

### Option 1: GitHub Pages (Recommended)
1. Fork this repository
2. Go to Settings → Pages
3. Set source to "main" branch
4. Access at `https://yourusername.github.io/repository-name`

### Option 2: Local Usage
1. Download `index.html`
2. Open in any modern browser (Chrome, Firefox, Edge)
3. Upload your Excel file with voter data

### Excel File Format

Your Excel file should have these columns:

| Column Name | Description |
|-------------|-------------|
| Serial No. | Voter serial number |
| EPIC No. | Voter ID (EPIC card number) |
| Name of Voter | Full name of voter |
| Relative's Name (Relationship) | Father's/Husband's name |
| Age | Voter's age |
| Sex | Male/Female |

## ⚙️ Configuration

Edit the `CONFIG` object in `index.html` to customize for different wards:

```javascript
const CONFIG = {
    wardNo: "१३",
    wardNoEnglish: "13",
    zone: "Dharampeth Zone",
    prabhagNo: "१३/१३",
    boothName: "नूतन भारत विद्यालय",
    roomNo: "१",
    boothAddress: "अभ्यंकरनगर, नागपूर",
    electionDate: "१५/०१/२०२६",
    electionYear: "२०२५-२०२६",
    boothNo: "१३",
    designerName: "Anand Kathalewar",
    designerTitle: "Mathematics & Drawing Instructor, Govt. ITI Nagpur"
};
```

## 📱 Mobile Usage Tips

1. Open the portal URL on your phone/tablet
2. Upload the Excel file once (data stays in browser memory)
3. Search for voters as they arrive
4. Tap on a result to see the detail card
5. Take a photo of the detail card if needed

## 🔒 Privacy & Security

- **No Data Transmission** - All processing happens locally in your browser
- **No Server Storage** - Data is never uploaded to any server
- **Session-Based** - Data is cleared when you close the browser
- **HTTPS Ready** - Works on GitHub Pages with SSL

## 📁 Files Included

| File | Description |
|------|-------------|
| `index.html` | Main application (GitHub Pages compatible) |
| `voter-data.json` | Sample voter data in JSON format |
| `VOTER_LIST_13.xlsx` | Sample Excel file |
| `README.md` | This documentation |

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Designed by Anand Kathalewar**

- Mathematics & Drawing Instructor
- Government ITI Nagpur
- Maharashtra, India

---

<p align="center">
  Made with ❤️ for NMC Elections 2025-26
</p>

<p align="center">
  <img src="https://img.shields.io/badge/🇮🇳-India-FF9933?style=flat-square" />
</p>
