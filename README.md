# Personal-Finance-Manager-and-report-generator
A simple Personal Finance Tracker implemented in C++ that allows users to manage their income, expenditures, and investments. This application provides an easy way to track financial transactions and generate a detailed HTML report of the financial status.

## Features

- **Transaction Management**: 
  - Add income and expenditure transactions with descriptions.
  - Keep track of the overall balance.
  
- **Investment Tracking**: 
  - Support for different types of investments: 
    - Systematic Investment Plan (SIP)
    - Fixed Deposit (FD)
  - Calculate expected returns based on user-defined interest rates and durations.
  
- **HTML Report Generation**: 
  - Generate a comprehensive HTML report summarizing financial transactions and investments.

## Technologies Used

- C++
- Standard Template Library (STL)
- File I/O (for generating HTML reports)
- CSS

## How to Run the Project

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/personal-finance-tracker.git
   cd personal-finance-tracker
   ```

2. **Compile the Code**:
   You can compile the code using any C++ compiler. For example, using `g++`:
   ```bash
   g++ -o finance_tracker finance_tracker.cpp
   ```

3. **Run the Executable**:
   ```bash
   ./finance_tracker
   ```

4. **Follow the Prompts**:
   - Enter transactions as prompted.
   - Input investment details and expected interest rates.
   - Choose to generate an HTML report when prompted.

5. **View the Report**:
   - After generating the report, open `finance_report.html` in your web browser to view your personal finance summary.

## Sample Output

The generated HTML report will contain sections for:
- Monthly Summary
- Income and Expenditure details
- Investment details and expected returns


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
