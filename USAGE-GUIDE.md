# 📖 Usage Guide - OB-1 File Drop

## 🎯 Quick Start

1. **Navigate to the repository**: https://github.com/protechtimenow/ob1-file-drop
2. **Choose the right folder** for your file type
3. **Upload your file** via GitHub's web interface
4. **Reference it in chat**: "Please analyze `/data-files/my-file.csv`"

## 📂 Upload Methods

### Method 1: GitHub Web Interface (Easiest)
1. Go to https://github.com/protechtimenow/ob1-file-drop
2. Navigate to the appropriate folder
3. Click "Upload files" button
4. Drag & drop or select files
5. Commit the upload

### Method 2: Git Commands (Advanced)
```bash
git clone https://github.com/protechtimenow/ob1-file-drop.git
cd ob1-file-drop
# Add your files to appropriate folders
git add .
git commit -m "Add files for analysis"
git push
```

## 🔍 File Analysis Examples

### Smart Contract Analysis
```
Upload: smart-contracts/MyToken.sol
Chat: "Please review smart-contracts/MyToken.sol for security issues"
Result: Security analysis, gas optimization, best practices
```

### Data Analysis
```
Upload: data-files/trading-performance.csv
Chat: "Analyze my trading performance in data-files/trading-performance.csv"
Result: Statistical analysis, visualizations, insights
```

### Code Review
```
Upload: code/trading-bot.py
Chat: "Review code/trading-bot.py for bugs and optimization"
Result: Code quality assessment, bug detection, improvements
```

## ✅ Best Practices

### File Naming
- Use descriptive names: `defi-portfolio-2024.csv` not `data.csv`
- No spaces in filenames: use `trading_data.json` not `trading data.json`
- Include dates when relevant: `analysis_2024-06-09.md`

### File Organization
- Put files in the correct folders
- One analysis topic per file when possible
- Remove sensitive data before uploading

### Communication
- Always mention the full path: `/data-files/filename.csv`
- Describe what you want analyzed
- Ask specific questions about the data

## 🚨 Security Reminders

**Never Upload:**
- Private keys or seed phrases
- API keys or secrets
- Personal financial account info
- Proprietary trading algorithms

**Safe to Upload:**
- Sample data (anonymized)
- Open source code
- Public smart contracts
- General configuration templates

## 💬 Example Conversations

### Portfolio Analysis
```
You: "I uploaded my DeFi positions to data-files/portfolio-q4-2024.csv. 
      Can you analyze my performance and identify my best performing protocols?"

OB-1: *analyzes the data and provides detailed performance metrics,
      protocol breakdown, and recommendations*
```

### Smart Contract Review
```
You: "Please review smart-contracts/LiquidityPool.sol for potential 
      vulnerabilities and gas optimizations."

OB-1: *performs security analysis, identifies issues, suggests 
      optimizations, and creates a detailed report*
```

## 📊 Output Files

OB-1 will save analysis results to the `/outputs/` folder:
- Reports in markdown format
- Generated visualizations
- Processed data files
- Recommendation summaries

---

**Happy analyzing! 🚀**