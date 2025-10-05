# 📊 Stock Analysis

A simple Python project for analyzing and visualizing stock portfolio data from an Excel file.  
It reads your stock holdings, calculates total quantities, and generates a bar chart showing your portfolio distribution.

---

## 🚀 Features

- Reads stock holdings from an Excel file.  
- Aggregates total quantities per stock symbol.  
- Generates a bar chart to visualize portfolio composition.  
- Lightweight and easy to use.

---

## 📂 Repository Structure

```
.
├── README.md
├── acoes.py
└── (input Excel file – not included)
```

- **acoes.py** – main Python script that performs data loading, aggregation, and visualization.  
- **Excel file** – user-provided portfolio data (not included for privacy reasons).

---

## 💡 How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/FernandaDeFR/Stock_analysis.git
   cd Stock_analysis
   ```

2. Prepare your Excel file with columns similar to:
   - `ticker` – stock symbol  
   - `quantity` – number of shares  

3. Run the script:
   ```bash
   python acoes.py path/to/your_excel_file.xlsx
   ```

4. A bar chart will be displayed showing the total quantity of each stock in your portfolio.

---

## ⚙️ Technologies Used

- **Python 3**  
- **pandas** – for data manipulation  
- **matplotlib** – for visualization  
- **openpyxl** – for Excel file support

---

## 🎯 Purpose

This project was created to:
- Analyze how a portfolio is distributed across different stocks.  
- Provide a quick visual overview of stock concentration.  
- Serve as a base for more advanced portfolio analysis and visualization tools.

---

## 📈 Future Improvements

- Include total investment value per stock (based on current price).  
- Support CSV and JSON input formats.  
- Add export options for charts (PNG, PDF).  
- Develop a simple web dashboard using Streamlit or Dash.

---

## 👩🏻‍💻 Author

**Fernanda de Faria Rodrigues**  
🔗 [GitHub Profile](https://github.com/FernandaDeFR)

---

## 🪪 License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.
